[![Build Status](https://travis-ci.org/Artsdatabanken/lapskaus.svg?branch=master)](https://travis-ci.org/Artsdatabanken/lapskaus) [![Coverage Status](https://coveralls.io/repos/github/Artsdatabanken/lapskaus/badge.svg?branch=master)](https://coveralls.io/github/Artsdatabanken/lapskaus?branch=master)
![Dependencies](https://david-dm.org/artsdatabanken/lapskaus.svg)
[![Greenkeeper badge](https://badges.greenkeeper.io/Artsdatabanken/lapskaus.svg)](https://greenkeeper.io/)
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)
[![contributions welcome](https://camo.githubusercontent.com/926d8ca67df15de5bd1abac234c0603d94f66c00/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636f6e747269627574696f6e732d77656c636f6d652d627269676874677265656e2e7376673f7374796c653d666c6174)](https://github.com/Artsdatabanken/lapskaus/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md#pull-requests)

[![Screenshot](screenshot.png "lapskaus screenshot")](http://outgoing-front.surge.sh/)

# Lapskaus

Brief description

* [Demo](https://lapskaus.surge.sh)
* [Storybook](https://lapskaus.surge.sh/storybook)

## Getting started / Installing

Clone the repo and then run:

```javascript
yarn
```

to install dependencies.  Or if using npm: `npm install`

```javascript
yarn start
```

to start lapskaus.  It should automatically open in a new browser tab.  Or with npm: `npm start`

## Developing

See [developing](DEVELOPING.md) for more on developing.

### Built With

 * [material-ui](https://github.com/callemall/material-ui)
 * [create-react-app](https://github.com/facebookincubator/create-react-app)
 * [react](https://github.com/facebook/react)

### Prerequisites

 * [npm](https://nodejs.org/en/download/) or [yarn](https://yarnpkg.com/en/)

### Setting up Dev

```javascript
git clone https://github.com/Artsdatabanken/lapskaus.git
cd lapskaus/
yarn
```

### Building
```javascript
yarn build
```
### Deploying / Publishing

Builds are triggered for each commit.  Deployment is done automtically by travis on a successful build.

### Configuration

### Tests

We use [jest](https://facebook.github.io/jest/) for testing.  To run the tests run:

```javascript
yarn test
```
### Style guide

We use [Prettier[(https://github.com/prettier/prettier). Run

```javascript
prettier --write src/**
```

to automatically fix most style issues.   Style is improved automatically on commit.

### Api Reference

### Database

### Licensing

The MIT License (MIT)
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
