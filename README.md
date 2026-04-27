# flux-isa-v3

> ISA v3 edge encoder/decoder — variable-width 1-3 byte instructions with confidence fusion.

## What It Is

Pure C11 implementation of the FLUX ISA v3 instruction encoder and decoder. Variable-width encoding (1-3 bytes) designed for edge-constrained environments where code density matters.

## Build

```bash
make test
```

## Fleet Context

Part of the [FLUX ecosystem](https://github.com/Lucineer/flux-runtime-c) of agent runtimes. Related:
- [flux-runtime-c](https://github.com/Lucineer/flux-runtime-c) — C11 VM with 200 opcodes
- [cuda-instruction-set](https://crates.io/crates/cuda-instruction-set) — Rust ISA with assembler

## License

MIT / Apache-2.0
