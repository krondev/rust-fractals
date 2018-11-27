# Rust Fractals

## Feaures

- [ ] Concurrency (Rayon, Crossbeam, etc)
- [ ] WebAssembly
- [ ] Swagger (?)
- [ ] Protobuf (?)
- [ ] Travis (?)
- [ ] AppVeyor (?)
- [ ] ReactJS
- [ ] Wasm Multithreads

## Type of fractals

- [ ] Mandelbrot set [wiki](https://en.wikipedia.org/wiki/Mandelbrot_set)
- [ ] Julia set [wiki](https://en.wikipedia.org/wiki/Julia_set)
- [x] Newton fractal [wiki](https://en.wikipedia.org/wiki/Newton_fractal)

## Example

![Newtone](fractal-example.png)

## How to run

    cargo run newton-fractal.png 100x100 -0.7,-1.0 1.0,0.7 10

## How to run WebAssembly version

    wasm-pack build & wasm-pack start
