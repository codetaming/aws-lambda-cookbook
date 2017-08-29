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

### Organisation
Lambdas should be placed in a sub-directory named after the function name under the  [lambda](example/lambda) directory. For example [lambda/example-aws-lambda/](example/lambda/example-aws-lambda).

## Package.json
To create a new package.json

```bash
npm init
```

The [package.json](example/lambda/example-aws-lambda/package.json)

## Node Lambda
The [Node Lambda](https://www.npmjs.com/package/node-lambda) npm package is used to generate template AWS Lambdas and to test locally and deploy.

### Adding to project

```bash
npm install node-lambda --save-dev
```

### Adding standard
```bash
npm install standard --save-dev
```
and add to test
```json
  "scripts": {
    "test": "standard"
  }
```

### Initialising
Inititalise Node Lambda to create the template files required.

```bash
node-lambda setup
```

### Installation

```bash
npm install -g node-lambda
```

## Add index.js
[index.js](example/lambda/example-aws-lambda/index.js)

## Add aws-sdk
Add the latest version of the aws-sdk for Node.
```bash
npm install aws-sdk@latest --save
```

## Run Locally

```bash
node-lambda run
```
