# react-native-gzip-new-architecture

Fast gzip to compress strings for android & ios in React Native with New Architecture (Fabric & TurboModules) support.

### Thanks to lorenc-tomasz https://github.com/ammarahm-ed/react-native-gzip/issues/4#issuecomment-2624546187


This is a fork of [react-native-gzip](https://github.com/ammarahm-ed/react-native-gzip) that has been updated to support React Native's New Architecture.

## Features

- ✨ Supports React Native New Architecture
- 🚀 Fast gzip compression and decompression
- 📱 Works on both Android and iOS
- 💪 Type-safe with TypeScript definitions

## Installation

```sh
pnpm add react-native-gzip-new-architecture
# or using npm
npm install react-native-gzip-new-architecture
```

## Usage

```js
import { deflate, inflate } from 'react-native-gzip-new-architecture';

const data = `hello world`;
const compressed = await deflate(data); // Returns a base64 string of compressed data
const decompressed = await inflate(compressed); // Decompress the data to original string value
```

## New Architecture Support

This package has been updated to support React Native's New Architecture (Fabric & TurboModules). It will automatically use the New Architecture when your app is configured to use it.

### Requirements

- React Native >= 0.70.0
- Enabled New Architecture in your app

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT

---

This is a fork of [react-native-gzip](https://github.com/ammarahm-ed/react-native-gzip) enhanced with New Architecture support.
Made with [create-react-native-library](https://github.com/callstack/react-native-builder-bob)
