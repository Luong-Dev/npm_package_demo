# npm_package_demo

A TypeScript utility package with mathematical functions and type definitions.

## Installation

```bash
npm install luongtd_npm_package_demo
```

## Usage

### ESM (Recommended)

```javascript
import { sum, DemoParamsType } from "luongtd_npm_package_demo"

// Use the sum function
const result = sum(5, 3) // 8

// Use the type
const user: DemoParamsType = {
  name: "John",
  age: 25
}
```

### CommonJS

```javascript
const { sum, DemoParamsType } = require("luongtd_npm_package_demo")

const result = sum(5, 3) // 8
```

## API

### Functions

- `sum(a: number, b: number): number` - Adds two numbers

### Types

- `DemoParamsType` - Interface for demo parameters

## Development

```bash
# Install dependencies
npm install

# Build the package
npm run build

# Run tests (when available)
npm test
```

## License

ISC
