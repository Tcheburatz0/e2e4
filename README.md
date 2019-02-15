# e2e4
[![Build Status](https://travis-ci.org/Tcheburatz0/e2e4.svg?branch=master)](https://travis-ci.org/Tcheburatz0/e2e4)
[![Coverage Status](https://coveralls.io/repos/github/Tcheburatz0/e2e4/badge.svg?branch=master)](https://coveralls.io/github/Tcheburatz0/e2e4?branch=master)


Set of base classes and utilities to build unobtrusive list models. 
This is abstract codebase which can be used to implement bridges to end-user frameworks (such as [Angular bridge](https://github.com/eastbanctechru/right-angled)).

## Documentation
Documentation is available [here](http://Tcheburatz0.github.io/e2e4)

## How to build the project

To build the project, follow these steps:

1. Ensure that [NodeJS](http://nodejs.org/) is installed. This provides the platform on which the build tooling runs.

2. From the project folder, execute the following command to install project dependencies:

  ```shell
  npm install
  ```
3. From the project folder, execute the following command to build the source code:

  ```shell
  npm build
  ```
## How to run tests

You can run tests in Chrome with watch mode by executing the following command: 

  ```shell
  npm test:watch
  ```
  or execute single run:
  
  ```shell
  npm test
  ```

You can also use [Yarn](https://yarnpkg.com/)
