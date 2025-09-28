# Melvi-l

Most of the time, I touch grass and live life. Then sometimes, i do little silly useless but fun project and I obsess over node editors.

The current one is a [rust-wgpu node editor](https://github.com/melvi-l/node-editor), a direct successor to the TypeScript version.

The last one was my little silly overengineered [webgpu-typescript node editor](https://github.com/melvi-l/node-editor-webgpu). This was my first iteration on my node editor journey. I chose typescript and webgpu because I come from (and currently work in) a ThreeJS/WebGL environment and I wanted to learn a nearly “raw” graphics API -- as WebGL has started to show some limitations. This project gave me the oportunity to learn WebGPU basics and to experiment with Instancing, QuadTree, GPUPicking and more, by overengineering a simple problem. 
As a fun side quest I built a small declarative Snabbdom-like frontend framework, [kuai-ts](https://github.com/melvi-l/kuai-ts), and used it to build a little [color-picker using webgpu](https://github.com/melvi-l/color-picker-webgpu). In order to add text support, I went down the the font rendering rabbit hole and came back with the idea to compile [Viktor Chlumský](https://github.com/Chlumsky) msdf-gen C++ library to WASM, to build a msdf text renderer from TTF, generating the MSDF atlas in a WebWorker on-the-fly. [Here is the unfinished project](https://github.com/melvi-l/msdf-webgpu)

I code on nvim-tmux with a [corn](https://github.com/foostan/crkbd), all of this runs inside WSL in my c*rporate girlie™ time between 9 and 5 or inside whatever distro I am on in my neverending distrohopping journey.
