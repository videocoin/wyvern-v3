Wyvern v3
---------

![Project Wyvern Logo](https://media.githubusercontent.com/media/ProjectWyvern/wyvern-branding/master/logo/logo-square-red-transparent-200x200.png?raw=true "Project Wyvern Logo")

[![https://img.shields.io/github/license/wyvernprotocol/wyvern-v3.svg](https://img.shields.io/github/license/wyvernprotocol/wyvern-v3.svg)](https://opensource.org/licenses/MIT) [![Build Status](https://travis-ci.org/wyvernprotocol/wyvern-v3.svg?branch=master)](https://travis-ci.org/wyvernprotocol/wyvern-v3) [![Coverage Status](https://coveralls.io/repos/github/wyvernprotocol/wyvern-v3/badge.svg?branch=master)](https://coveralls.io/github/wyvernprotocol/wyvern-v3?branch=master)

See [DESIGN.md](DESIGN.md) for the rationale behind Wyvern v3. Read [DOCS.md](DOCS.md) for a protocol usage guide.

Deployed contract addresses can be found in [config.json](config.json).

**This code has not been audited. Do not use it in production.**

### Development

#### Setup

Install dependencies with [Yarn](https://yarnpkg.com/en/):

```bash
yarn
```

#### Testing

Run testrpc (ganache-cli) to provide a simulated EVM:

```bash
yarn testrpc
```

In a separate terminal, run the testuite:

```bash
yarn test
```

#### Linting

Lint all Solidity files with;

```
yarn lint
```

#### Deployment

Edit [truffle.js](truffle.js) according to your deployment plans, then run:

```
yarn run truffle deploy --network [network]
```
