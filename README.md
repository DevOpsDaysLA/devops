# devops 💻

[![test](https://github.com/DevOpsDaysLA/devops/actions/workflows/test.yml/badge.svg)](https://github.com/DevOpsDaysLA/devops/actions/workflows/test.yml) [![Lint](https://github.com/DevOpsDaysLA/devops/actions/workflows/lint.yml/badge.svg)](https://github.com/DevOpsDaysLA/devops/actions/workflows/lint.yml) [![CodeQL](https://github.com/DevOpsDaysLA/devops/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/DevOpsDaysLA/devops/actions/workflows/codeql-analysis.yml) [![ci](https://github.com/DevOpsDaysLA/devops/actions/workflows/ci.yml/badge.svg)](https://github.com/DevOpsDaysLA/devops/actions/workflows/ci.yml)

A DevOpsDaysLA workshop for building and deploying a wordle clone

## Running Locally 🔨

For running locally, you have two options:

- npm
- docker-compose

### npm

Simply run the following commands to start the app with npm:

```bash
npm install
npm run start
```

> Checkout the application running in your browser at [localhost:3000](http://localhost:3000)

### docker-compose

To run the application locally with docker-compose, run the following command:

```bash
make run
```

This project uses a Makefile to wrap the docker-compose commands into a one liner

> Checkout the application running in your browser at [localhost:3000](http://localhost:3000)
