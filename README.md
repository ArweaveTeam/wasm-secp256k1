# wasm-secp256k1

The [libsecp256k1 C library](https://github.com/bitcoin-core/secp256k1) compiled to WASM and wrapped with an ultralight TypeScript API.

# Building

Project uses and requries following dependencies:
- Bun: https://bun.sh/docs/installation
- Docker: https://docs.docker.com


```
# Display usage and targets
make sense

# Build
git submodule update --init --recursive
make build

# Publish
make publish
```
