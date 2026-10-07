# ass — AArch64 Assembly Practice

ARM64 assembly exercises using `write(2)` system calls. Files include:
- `hello.s` — Hello world via sys_write
- `fileio.s` — File I/O operations
- `gpiomem.s` — GPIO memory access
- `shift.s` — Bit shift operations

## Build

Requires GNU toolchain for AArch64 (`gcc-aarch64-linux-gnu`). Run from this directory:

```sh
chmod +x setup.sh && ./setup.sh
```

This handles the full autotools pipeline: `aclocal → autoreconf → configure → make`.

⛧ Draft by **n0ctilucent** | [bitsmasher.net/research](https://www.bitsmasher.net/research/)
