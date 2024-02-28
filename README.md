# A Simple 32-bit Calculator Using WebAssembly

This is a practice project that showcases a Simple Calculator written in WebAssembly Text Format (WAT). The complied binary is run using **wasmtime** - A fast a secure runtime for WebAssembly.

## Demo:

$ wat2wasm calculator.wat

$ wasmtime calculator.wasm --invoke add 10 5

15

$ wasmtime calculator.wasm --invoke sub 10 5

5

$ wasmtime calculator.wasm --invoke mul 10 5

50

$ wasmtime calculator.wasm --invoke div 10 5

2
