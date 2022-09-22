# Express Boilerplate

A boilerplate/starter project for quickly building RESTful APIs using Node.js and Express with some pre-built features.

## Features

- **Logging**: using [morgan](https://github.com/expressjs/morgan)
- **Environment variables**: using [dotenv](https://github.com/motdotla/dotenv)
- **Security**: set security HTTP headers using [helmet](https://helmetjs.github.io/)
- **Santizing**: sanitize request data against xss and query injection using [xss-clean](https://github.com/jsonmaur/xss-clean)
- **CORS**: Cross-Origin Resource-Sharing enabled using [cors](https://github.com/expressjs/cors)
- **Compression**: gzip compression with [compression](https://github.com/expressjs/compression)
- **Git hooks**: with [husky](https://github.com/typicode/husky) and [lint-staged](https://github.com/okonet/lint-staged)
- **Linting**: with [eslint](https://eslint.org/) and [prettier](https://prettier.io/)

## Get Started

- Clone this repo
  ```bash
  git clone https://github.com/irfnd/express-boilerplate
  ```
- Rename this boilerplate to whatever you want and move to that folder
  ```bash
  cd <your-project-name>
  ```
- Delete .git folder
- Reinitialize your git
  ```bash
  git init .
  git add .
  git commit -m "Your initialize commit"
  ```
- Install all packages
  ```bash
  npm install
  ```
  or
  ```bash
  yarn
  ```
- Project ready.
- You can push/publish to your own github by changing some configuration in `package.json` based on the configuration you want.
