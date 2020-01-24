# Tour of Heroes

[![Angular Style Guide][angular-style-guide-badge]][angular-style-guide-url]

## Prerequisites

- [Node](https://nodejs.org/en/) >= 10.9.0
- [Yarn](https://yarnpkg.com/lang/en/) >= 1.21.1

## Setup

### Install dependencies

```bash
cd <ngx-toh>

yarn install
```

### Run server

```bash
yarn start
```

Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Run tests

```bash
# Unit test
yarn test

# e2e test
yarn run e2e
```

### Docker support

```bash
# Run server
docker-compose up [--detech/-d]

Visit http://localhost:4201/ in your browser.
```

[angular-style-guide-badge]: https://mgechev.github.io/angular2-style-guide/images/badge.svg
[angular-style-guide-url]: https://angular.io/styleguide
