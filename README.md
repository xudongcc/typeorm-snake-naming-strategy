# typeorm-snake-naming-strategy

> Snake naming strategy for TypeORM.

## Install

```javascript
npm i typeorm-snake-naming-strategy
// or
yarn add typeorm-snake-naming-strategy
```

## Usage

```javascript
// ormconfig.js

const { SnakeNamingStrategy } = require("typeorm-snake-naming-strategy");

module.exports = {
  // ...
  namingStrategy: new SnakeNamingStrategy()
  // ...
};
```
