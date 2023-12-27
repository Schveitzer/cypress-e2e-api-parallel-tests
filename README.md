# cypress-e2e-api-parallel-tests

In this project I demonstrate some features of Cypress framework in version 13, for automation E2E and API tests.

This project includes:

- Frameworks:
    - Cypress


- Features:
    - Tests in multiple browser
    - Api testing
    - Authenticated test sessions with session cookies
    - Test setup
    - PageObject Pattern
    - Tag test for execution
    - Intercepting page requests (Network Events)
    - Mock page requests

## Requirements
- Node >= 20.0 - [How install Node](https://nodejs.org/en)
- NVM (Optional, but recommended) [How install NVM](https://github.com/nvm-sh/nvm#installing-and-updating)

## Getting Started
Create a virtual environment (optional):

```bash
$ nvm install 20
$ nvm use 20
```

## Application under test
For these tests I use a application named as Ngx-Admin Angular 8 which can be found here: [Sauce Demo](https://github.com/bondar-artem/ngx-cypress-test/tree/master)

# Setup application:
Clone repository:

```Bash
$ git clone git@github.com:bondar-artem/ngx-cypress-test.git
```

Install dependency's:
```Bash
$ npm install --force
```

Start application:
```Bash
$ npm start
```

Access application from browser:
> http://localhost:4200/

Install dependencies for tests:

```bash
$ npm install --force-dev
```

## To run tests, 
```bash
$ npm cypress open
```