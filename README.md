# Wasm game of life

A simple web app that runs [Conway's Game of Life](https://www.wikiwand.com/en/Conway%27s_Game_of_Life) built using Rust and WebAssembly.
The project was done while reading the [Rust and WebAssembly Tutorial](https://rustwasm.github.io/docs/book/game-of-life/introduction.html).

## Creation

[Learn more about `cargo generate` here.](https://github.com/ashleygwilliams/cargo-generate)

```
cargo generate --git https://github.com/rustwasm/wasm-pack-template.git --name my-project
cd my-project
```

## Building

```
wasm-pack build
```
