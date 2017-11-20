# Modern Node Package

Modern stack to build server-side Node.js packages

# What's included?

## Testing

Requirements:
- Parallel tests
- Async / Await support
- Assertion counting
- Coverage reports

:star2: [tap](https://github.com/tapjs/node-tap)
```
npm run test
```
## Linting & Formatting

**Requirements:**
- StandardJs
- Opinionated Code Formatter

:star2: [prettier-standard](https://github.com/sheerun/prettier-standard)
:star2: [standard](https://github.com/standard/standard)
```
npm run format
npm run lint
```
## Code coverage
**Requirements:** Support for common report formats

:star2: Integrate coverage support of [tap](https://github.com/tapjs/node-tap)
```
npm run coverage
```
:star2: Send coverage report with [coveralls](https://github.com/nickmerwin/node-coveralls) to [coveralls.io](https://coveralls.io)
```
npm run coveralls
```
## Publishing
**Requirements:** Painless NPM publishing

:star2: [np](https://github.com/sindresorhus/np)
```
np patch
```

## Git-Hooks
**Requirements:** Define hooks as npm scripts

:star2: [Husky](https://github.com/typicode/husky)

## Continuous Integration

**Requirements:** Free CI for OS

* [Travis](https://travis-ci.org/) for Unix
* [Appveyor](https://ci.appveyor.com) for Windows

## Ignore files

- Use a .npmignore file to keep stuff out of your package.
- Use .gitignore  file to keep stuff out of your repository.

## Badges

[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](#badge)
[![Build Status](https://travis-ci.org//hemerajs/modern-node-package.svg?branch=master)](https://travis-ci.org//hemerajs/modern-node-package)
[![Build status](https://ci.appveyor.com/api/projects/status/58ldk1x962nviv03?svg=true)](https://ci.appveyor.com/project/hemerajs/modern-node-package)
[![Coverage Status](https://coveralls.io/repos/github/hemerajs/modern-node-package/badge.svg?branch=master)](https://coveralls.io/github/hemerajs/modern-node-package?branch=master)
[![NPM version](https://img.shields.io/npm/v/bootme.svg?style=flat)](https://www.npmjs.com/package/modern-node-package)
