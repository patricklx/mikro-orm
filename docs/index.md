---
layout: homepage
---

[![NPM version](https://img.shields.io/npm/v/mikro-orm.svg)](https://www.npmjs.com/package/mikro-orm)
[![Chat on slack](https://img.shields.io/badge/chat-on%20slack-blue.svg)](https://join.slack.com/t/mikroorm/shared_invite/enQtNTM1ODYzMzM4MDk3LTBmZDNlODBhYjcxNGZlMTkyYzJmODAwMDhjODc0ZTM2MzQ2Y2VkOGM0ODYzYTJjMDRiZDdjMmIxYjI2OTY0Y2U)
[![Downloads](https://img.shields.io/npm/dm/mikro-orm.svg)](https://www.npmjs.com/package/mikro-orm)
[![Dependency Status](https://david-dm.org/B4nan/mikro-orm.svg)](https://david-dm.org/B4nan/mikro-orm)
[![Build Status](https://travis-ci.com/B4nan/mikro-orm.svg?branch=master)](https://travis-ci.com/B4nan/mikro-orm)
[![Coverage Status](https://img.shields.io/coveralls/B4nan/mikro-orm.svg)](https://coveralls.io/r/B4nan/mikro-orm?branch=master)
[![Maintainability](https://api.codeclimate.com/v1/badges/27999651d3adc47cfa40/maintainability)](https://codeclimate.com/github/B4nan/mikro-orm/maintainability)

MikroORM is TypeScript ORM for Node.js based on Data Mapper, Unit of Work and Identity Map patterns.

Currently it supports MongoDB, MySQL and SQLite databases, but more can be supported via custom drivers right now. It has first class TypeScript support, while staying back compatible with Vanilla JavaScript.

> Heavily inspired by [Doctrine](https://www.doctrine-project.org/) and [Nextras Orm](https://nextras.org/orm/).

## Table of contents

- Overview
  - [Installation & Usage](installation.md)
  - [Defining entities](defining-entities.md)
  - [Persisting, cascading and fetching entities with `EntityManager`](entity-manager.md)
  - [Using `EntityRepository` instead of `EntityManager`](repositories.md)
- Fundamentals
  - [Identity Map and Request Context](identity-map.md)
  - [Entity references](entity-references.md)
  - [Using entity constructors](entity-constructors.md)
  - [Collections](collections.md)
  - [Cascading persist and remove](cascading.md)
- Advanced features
  - [Smart nested populate](nested-populate.md)
  - [Updating entity values with `IEntity.assign()`](entity-helper.md)
  - [Property validation](property-validation.md)
  - [Lifecycle hooks](lifecycle-hooks.md)
  - [Naming strategy](naming-strategy.md)
  - [Metadata cache](metadata-cache.md)
  - [Debugging](debugging.md)
- Usage with different drivers
  - [Usage with MySQL and SQLite](usage-with-sql.md)
  - [Usage with MongoDB](usage-with-mongo.md)
- Recipes
  - [Usage with NestJS](usage-with-nestjs.md)
  - [Usage with Vanilla JS](usage-with-js.md)