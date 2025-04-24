# @MegMacD/hello

A simple npm package that provides a greeting functionality. This package is published to GitHub Packages registry.

## Description

This package exports a simple greeting function that takes a name as input and returns a personalized hello message.

## Installation

Since this package is published to GitHub Packages, you'll need to configure npm to use the GitHub registry:

```bash
npm config set @MegMacD:registry https://npm.pkg.github.com
```

Then install the package:

```bash
npm install @MegMacD/hello
```

## Usage

```javascript
const greet = require('@MegMacD/hello');

console.log(greet('World')); // Output: Hello, World!
```

## Development

This project uses a Docker development container for consistent development environments. To start development:

1. Ensure you have Docker and VS Code with the "Remote - Containers" extension installed
2. Clone the repository
3. Open the project in VS Code
4. Click "Reopen in Container" when prompted, or run the "Remote-Containers: Reopen in Container" command

## Scripts

- `npm run build` - Installs dependencies

## License

ISC