# @5minlab/tsconfig-5minlab

[![Build Status](https://travis-ci.org/5minlab/tsconfig-5minlab.svg?branch=master)](https://travis-ci.org/5minlab/tsconfig-5minlab)

tsconfig.json for 5minlab

## prerequisites

.npmrc

```
//npm.pkg.github.com/:_authToken=${AUTH_TOKEN}
@5minlab:registry=https://npm.pkg.github.com/
```

## installation

```sh
$ npm install @5minlab/tsconfig-5minlab --save-dev
```

## usage

tsconfig.json

```json
{
  "extends": "./node_modules/@5minlab/tsconfig-5minlab/tsconfig.json"
}
```

## publish

```sh
$ npm version patch
$ npm publish
```
