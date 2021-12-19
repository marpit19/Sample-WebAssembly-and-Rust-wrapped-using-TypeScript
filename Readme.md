# Sample-WebAssembly-and-Rust-wrapped-using-TypeScript

I used a Rust TS template and did some expirents to get used to webassembly and rust.

## How to use

1. Clone this repo
2. Have the [rust toolchain](https://www.rust-lang.org/tools/install) installed
3. Have [wasm-pack](https://rustwasm.github.io/wasm-pack/installer/) installed
4. Run `yarn install`. If you dont have it, you can get it [here](https://yarnpkg.com/lang/en/docs/install/)
5. Run `wasm-pack build`
6. Run `yarn link` inside the `pkg` folder
7. Run `yarn link ilovewasm` on the project root (this is the project name on the _config.toml_ file)
8. Run `yarn run dev-server`
9. Go to `http://localhost:8080/`

To run the test suite do the steps 1 to 7 above and then:

1. Run `yarn runtest-server`
2. Go to `http://localhost:8080/test.html`

## License

This is available under the MIT-0 license. See [LICENSE](LICENSE) for more information.

[![forthebadge](https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=WebAssembly&logoColor=white)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-typescript.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-rust.svg)](https://forthebadge.com)
