# Vale WASM

WASM version of https://vale.sh/.

- [Vale](https://vale.sh/) is a syntax-aware linter for prose built with speed and extensibility in mind.
- This project compiles Vale to WebAssembly so it can be run in environments that support WASM, such as web browsers or serverless platforms.
- This project is not affiliated with or endorsed by the original Vale project or its maintainers.
- Runs slightly slower than native Vale due to the overhead of WebAssembly.
- Some features of native Vale may not be available in the WASM version due to limitations of the WebAssembly environment. Around 90% of Vale's features work in this version.