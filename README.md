# cute-prompt-site
The website for the description of cute-prompt project.


## Commands to run

### Build

```
$ cargo +nightly build --target=wasm32-unknown-unknown
$ cargo +nightly build --target=wasm32-unknown-unknown --release
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
