# Noir Lang WASM JavaScript Package

This JavaScript package enables users to compile a Noir program, i.e. generating its artifacts.

The package also handles dependency management like how Nargo (Noir's CLI tool) operates, but the package is used just for compilation, not proving, verifying and simulating functions.

## Building from source

Outside of the [noir repo](https://github.com/noir-lang/noir), this package can be built using the command below:

```bash
nix build -L github:noir-lang/noir/master#wasm
```

If you are within the noir repo and would like to build local changes, you can use:

```bash
nix build -L #wasm
```

## Tracking
Built from [noir-lang/noir@a1e6d5dc5c5663b9b5c1da8473c793da3d59cb88](https://github.com/noir-lang/noir/tree/a1e6d5dc5c5663b9b5c1da8473c793da3d59cb88)
