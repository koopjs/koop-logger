# Koop-Logger

## DEPRECATED - now migrated to a package in the [Koop monorepo](https://github.com/koopjs/koop/).

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)
[![Build Status](https://travis-ci.org/koopjs/koop-logger.svg?branch=master)](https://travis-ci.org/koopjs/koop-logger)
[![Greenkeeper badge](https://badges.greenkeeper.io/koopjs/koop-logger.svg)](https://greenkeeper.io/)

* A shared logger for Koop

## Usage
`npm install @koopjs/logger`
```javascript
const Logger = require('@koopjs/logger')
const config = require('config')
const log = new Logger(config)

log.info('foo')
log.debug('bar')
log.error('baz')
log.warn('bing')
```
