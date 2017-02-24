# wasm workshop

**A beginner level intro to WebAssembly!**

WebAssembly is a binary format for executing code on the web.

## Agenda

* What?
  * What is WebAssembly?
  * What is it good for?
  * How does it work?
* Why?
  * Why do we need it?
* The roadmap
  * Current status
  * The MVP
* Next step


## What?

WebAssembly is a portable, size- and load-time-efficient binary format for executing code on the web. Initially it focuses on C/C++ with a new backend being developed in upstream clang/LLVM.

### What is `emscripten`?

Emscripten is a a LLVM-based project, a LLVM-to-JavaScript compiler. It works as a back-end to the LLVM compiler.

The main tool is the [Emscripten Compiler Frontend](kripken.github.io/emscripten-site/docs/tools_reference/emcc.html#emccdoc) (emcc). It uses Clang to convert C/C++ files to LLVM bitcode, and [Fastcomp](http://kripken.github.io/emscripten-site/docs/building_from_source/LLVM-Backend.html#llvm-backend) to compile the bitcode to asm.js and then to WebAssembly.


## Why?

...


## The MVP

_"A Minimum Viable Product (MVP) for the standard with roughly the same functionality as asm.js, primarily aimed at C/C++"_

### The Roadmap

...



## Getting started

Before we get started compiling our first program to WebAssembly we need to compile the LLVM from source. [This guide](http://webassembly.org/getting-started/developers-guide/) will run you through the whole setup process.


## Links

* [Emscripten](http://kripken.github.io/emscripten-site/)
* [Emscripten SDK](https://github.com/juj/emsdk)
* [The WebAssembly binary toolkit](https://github.com/WebAssembly/wabt)
* [wast2wasm online demo](https://cdn.rawgit.com/WebAssembly/wabt/e528a622caa77702209bf0c3654ca78456c41a52/demo/index.html)

## Presentations

For presentation slides, check out the `gh-pages` branch or visit [tmn.github.io/wasmws](https://tmn.github.io/wasmws)
