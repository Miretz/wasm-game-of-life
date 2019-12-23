# WebAssembly Game of Life tutorial


Game of Life in Rust + WebAssembly.


Based on tutorial from [Rust WebAssembly book](https://rustwasm.github.io/docs/book/).


Setup: https://rustwasm.github.io/docs/book/game-of-life/setup.html


Compile rust:
```
wasm-pack build
```

Install web dependencies:
```
cd www/
npm install
```

Run dev server in the www directory:
```
npm run start
```

Check the app in the browser: http://localhost:8080/