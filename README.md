<p align="center">
  <img src="https://cdn-images-1.medium.com/max/1200/1*feM_-VHhK670LlEQekesKg.png" width="320" alt="Logo" />
</p>
  
<p align="center">A Node.js CQRS/ES Swagger API Microservice Boilerplate</p>


## Description

This is an application boilerplate that demonstrates how to use Nest.js and Event Store to create a RESTful Users API microservice.

Please note that commands have been implemented and they do write into the Event Store, however, queries for denormalized views have some boilerplate but it is up to you to implement them using your favorite database technology of choice.

## Test

```bash
# unit tests
$ yarn test

# e2e tests
$ yarn test:e2e

# test coverage
$ yarn test:cov
```