operation-log
=============

A node implementation of a log for currency market operations.


## Features

## Installation

```
npm install operation-log
```

## API

```javascript
```

## Roadmap

- Should assign an arbitrarily large integer sequence ID to the operation
- Should serialize the operation to a log file
- Should callback once serialized
- Should maintain the order of operations in callbacks

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality.

The CoffeeScript source is located in the `src/` directory and tests in the `test/` directory. Do not edit the contents of the `lib/` directory as this is compiled from the CoffeeScript source.

Before commiting run `npm test` to perform a clean compile of the source and run the tests. This ensures that everything commited is up to date and tested and allows people to `npm install` directly from the git repository (useful for integrating development branches, etc).

## License
Copyright (c) 2013 Peter Halliday  
Licensed under the MIT license.