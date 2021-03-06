# Design a REST API

This repository is a brief example of building a basic REST API. We use NodeJS and Koa along with some common Koa middlewares to accomplish this. If you're not familiar with Koa, you can reference the project created from our previous lesson, [Build an API Server using NodeJS and Koa](https://github.com/CodeSeoul/api-node-koa).

## Supporting Materials
* [Presentation](https://docs.google.com/presentation/d/1HmiSYPzIQeT8ZB0IgOpzIQCZII8kp0mfa6LO3jnx_PI/edit?usp=sharing)
* [Class Notes]()
* [YouTube Video](https://youtu.be/jj2zHj1aer0)

## Dependencies and Their Purpose
* [koa](https://koajs.com/) - web framework
* [koa-bodyparser](https://github.com/koajs/bodyparser) - parses HTTP request body for our use
* [koa-joi-router](https://github.com/koajs/joi-router) - router integrated with Joi input/output validation
* [koa-joi-router-docs](https://github.com/chuyik/koa-joi-router-docs) - OpenAPI JSON generator integrated with koa-joi-router
* [koa2-swagger-ui](https://github.com/scttcper/koa2-swagger-ui) - Swagger UI for documentating and experimenting with our API

## How to Run
* Use `npm run start` to run the Koa server

## How to Check it Out
1. Run the server
2. Visit [the spec address](http://localhost:3000/_api.json) to see the OpenAPI JSON spec generated by our dependencies
3. Visit [the swagger console](http://localhost:3000/swagger) to see the Swagger Console and test out your API
4. Add stuff! Change things! Experiment!
