<div align="center">

  <h1><code>wasm-game-of-life</code></h1>

  <strong>Conway's Game of Life implemented in Rust and WebAssembly using <a href="https://github.com/rustwasm/wasm-pack">wasm-pack</a>.</strong>
</div>

## About

This was made by following the [tutorial from the rustwasm book](https://rustwasm.github.io/docs/book/game-of-life/introduction.html).

## 🚴 Usage

### 🛠️ Build

```
wasm-pack build
```

### 💻 Serve

```
cd www
npm run start
```

Open [https://localhost:8080 in your browser](https://localhost:8080)

### 🔬 Test in Headless Browsers with `wasm-pack test`

```
wasm-pack test --headless --firefox
```

## 🔋 Batteries Included

* [`wasm-bindgen`](https://github.com/rustwasm/wasm-bindgen) for communicating
  between WebAssembly and JavaScript.
* [`console_error_panic_hook`](https://github.com/rustwasm/console_error_panic_hook)
  for logging panic messages to the developer console.
* [`wee_alloc`](https://github.com/rustwasm/wee_alloc), an allocator optimized
  for small code size.
