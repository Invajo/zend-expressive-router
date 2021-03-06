# zend-expressive-router

> ## Repository abandoned 2019-12-31
>
> This repository has moved to [mezzio/mezzio-router](https://github.com/mezzio/mezzio-router).

[![Build Status](https://secure.travis-ci.org/zendframework/zend-expressive-router.svg?branch=master)](https://secure.travis-ci.org/zendframework/zend-expressive-router)
[![Coverage Status](https://coveralls.io/repos/github/zendframework/zend-expressive-router/badge.svg?branch=master)](https://coveralls.io/github/zendframework/zend-expressive-router?branch=master)

Router subcomponent for [Expressive](https://github.com/zendframework/zend-expressive).

This package provides the following classes and interfaces:

- `RouterInterface`, a generic interface to implement for providing routing
  capabilities around [PSR-7](http://www.php-fig.org/psr/psr-7/)
  `ServerRequest` messages.
- `Route`, a value object describing routed middleware.
- `RouteResult`, a value object describing the results of routing.

## Installation

Typically, you will install this when installing Expressive. However, it can be
used standalone to provide a generic way to provide routed PSR-7 middleware. To
do this, use:

```bash
$ composer require zendframework/zend-expressive-router
```

We currently support and provide the following routing integrations:

- [Aura.Router](https://github.com/auraphp/Aura.Router):
  `composer require zendframework/zend-expressive-aurarouter`
- [FastRoute](https://github.com/nikic/FastRoute):
  `composer require zendframework/zend-expressive-fastroute`
- [zend-router](https://github.com/zendframework/zend-router):
  `composer require zendframework/zend-expressive-zendrouter`

## Documentation

Expressive provides [routing documentation](https://docs.zendframework.com/zend-expressive/features/router/intro/).
