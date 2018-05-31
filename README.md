# cute-prompt-site
The website for the description of cute-prompt project.


## Commands to run

### Build

```
$ cargo +nightly build --target=wasm32-unknown-unknown
$ cargo +nightly build --target=wasm32-unknown-unknown --release
```

```
$ rustc +nightly --target wasm32-unknown-unknown -O --crate-type=cdylib src/hoge.rs -o hoge.big.wasm
$ wasm-gc hoge.big.wasm hoge.wasm
```

### Run

```
$ python3 -m http.server 8000
```

### Compile to WebAssembly using Rust's native WebAssembly backend

```
$ cargo web start --target=wasm32-unknown-unknown
```
Visit `localhost:8000` with your browser.
