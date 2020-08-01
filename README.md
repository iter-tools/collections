# @iter-tools/collections

The iter tools data collection classes, made available as a single package. Includes typescript libdefs. Suitable for node or browser environments. Supports native es imports in `node > 13.2`.

## Usage

```js
import {
  List,
  Map,
  Queue,
  Set,
} from '@iter-tools/collections';

// OR

const {
  List,
  Map,
  Queue,
  Set,
} = require('@iter-tools/collections');
```

Until Typescript supports [package exports](https://github.com/microsoft/TypeScript/issues/33079) you must enable `esModuleInterop` to use this module.

## API

API documentation is provided individually for [List](https://github.com/iter-tools/list#api), [Map](https://github.com/iter-tools/map#api), [Queue](https://github.com/iter-tools/queue#api), and [Set](https://github.com/iter-tools/set#api).
