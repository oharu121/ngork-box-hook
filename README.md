# ngork-box-hook


[![npm version](https://badge.fury.io/js/ngork-box-hook.svg)](https://badge.fury.io/js/ngork-box-hook)
![License](https://img.shields.io/npm/l/ngork-box-hook)
![Types](https://img.shields.io/npm/types/ngork-box-hook)
![NPM Downloads](https://img.shields.io/npm/dw/ngork-box-hook)
![Last Commit](https://img.shields.io/github/last-commit/oharu121/ngork-box-hook)
![Coverage](https://codecov.io/gh/oharu121/ngork-box-hook/branch/main/graph/badge.svg)
![CI Status](https://github.com/oharu121/ngork-box-hook/actions/workflows/ci.yml/badge.svg)
![GitHub Stars](https://img.shields.io/github/stars/oharu121/ngork-box-hook?style=social)
A new npm package created with forge-npm-pkg.

## Installation

```bash
npm install ngork-box-hook
```

## Usage

```typescript
import { greet } from 'ngork-box-hook';

console.log(greet('World')); // Hello, World!
```

## Development

### Build

```bash
pnpm build
```

### Test

```bash
pnpm test
```

### Lint

```bash
pnpm lint
pnpm format
```

### Validate Package Exports

```bash
pnpm check:exports
```

## Release Workflow

This package uses automated publishing via GitHub Actions.

### Creating a Release

1. **Make your changes** and commit them
2. **Update the version:**
   ```bash
   pnpm version patch  # for bug fixes
   pnpm version minor  # for new features
   pnpm version major  # for breaking changes
   ```
3. **Push the changes and tags:**
   ```bash
   git push && git push --tags
   ```
4. **Package automatically publishes to npm** 🎉

The GitHub Actions workflow will automatically:
- Run all tests
- Build the package
- Publish to npm when a git tag is pushed


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Issues

If you encounter any issues, please report them [here](https://github.com/oharu121/ngork-box-hook/issues).


## License

MIT © oharu121
