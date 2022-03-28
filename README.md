# rust-wasm-ts-template

[![License](https://img.shields.io/badge/Licence-MIT-blue.svg)](https://github.com/utilForever/rust-wasm-ts-template/blob/main/LICENSE) [![Check](https://github.com/utilForever/rust-wasm-ts-template/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/utilForever/rust-wasm-ts-template/actions/workflows/main.yml)

This repository is a template of Rust + WebAssembly with TypeScript (🦀 + 🕸️ = 💖).

## Requirements

* [The Rust Toolchain](https://www.rust-lang.org/tools/install)
* [wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)
* [npm](https://docs.npmjs.com/getting-started)

## Quick Start

### Rust + WebAssembly

1. Run this command inside the project directory:

```sh
wasm-pack build
```

### WebAssembly with TypeScript

1. Ensure that the local development server and its dependencies are installed by running this command within the `www` subdirectory:
```sh
npm install
```

2. Run this command from within the `www` subdirectory:
```sh
npm run start
```

3. Go to `http://localhost:8080/`

## Contact

You can contact me via e-mail (utilForever at gmail.com). I am always happy to answer questions or help with any issues you might have, and please be sure to share any additional work or your creations with me, I love seeing what other people are making.

## License

<img align="right" src="http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png">

The class is licensed under the [MIT License](http://opensource.org/licenses/MIT):

Copyright &copy; 2022 [Chris Ohk](https://github.com/utilForever).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
