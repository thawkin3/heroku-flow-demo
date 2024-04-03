# Heroku Flow Demo

Demo app using Heroku Flow for CI/CD

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone https://github.com/thawkin3/heroku-flow-demo.git
$ cd heroku-flow-demo
$ npm install
$ npm start
```

Your app should now be running on [localhost:5001](http://localhost:5001/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku main
$ heroku open
```

or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Resources

For more information about Heroku and Heroku Flow, see:

- https://devcenter.heroku.com/articles/getting-started-with-nodejs
- https://devcenter.heroku.com/articles/heroku-cli-commands
- https://www.heroku.com/flow
