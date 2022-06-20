# devops 💻

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
