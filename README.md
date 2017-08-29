# AWS Lambda Cookbook

## Coding Standard
The JavaScript Code Standard is a JavaScript style guide, with linter & automatic code fixer.

[![JavaScript Style Guide](https://cdn.rawgit.com/standard/standard/master/badge.svg)](https://github.com/standard/standard)

Use this badge in the project README.md file:

[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## IDE
[The preferred IDE is IntelliJ IDEA](https://www.jetbrains.com/idea/)

IntelliJ and WebStorm support the JacaScript Code Standard and provide [setup instructions](https://blog.jetbrains.com/webstorm/2017/04/using-javascript-standard-style/).

## Lambdas

Lambdas should be placed in a sub-directory named after the function name under the  [lambda](example/lambda) directory. For example [lambda/example-aws-lambda/](example/lambda/example-aws-lambda).

## Node Lambda
The [Node Lambda](https://www.npmjs.com/package/node-lambda) npm package is used to generate template AWS Lambdas and to test locally and deploy.

### Installation

```bash
npm install -g node-lambda
```
