# Web Frontend for Goblint

Originally developed by Alex Micheli for his Bachelor's thesis at TUM i2.

Based on [jsoo-react](https://github.com/jchavarri/jsoo-react).


## Building

`opam switch create . 4.10.1 --deps-only -y`
`opam install ocaml-lsp-server -y`
`eval (opam env)`
`npm install`
`cd vendor/goblint && make && cd ../..`
`dune build`
