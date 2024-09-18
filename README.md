# Wasm example

Wasm (WebAssembly) allows you to run Rust code in Web and NodeJS apps. It's possible because of V8 engine that supports both ECMAScript and WebAssembly and is part of Chromium and NodeJS. This project is an example of how you can use Rust code in Web App.

## Prerequisits

1. [Install `cargo`](https://doc.rust-lang.org/cargo/getting-started/installation.html)
2. Install `wasm-pack`:

    ```bash
    cargo install wasm-pack
    ```

## Run the example

1. Build the project:

    ```bash
    wasm-pack build --target web
    ```

2. Serve the Web Page

    ```bash
    python3 -m http.server 8080
    ```

3. Open in browser <http://localhost:8080/www/index.html>
