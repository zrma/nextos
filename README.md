# NextOS

## Setup

```bash
rustup override add nightly
cargo install cargo-xbuild
rustup component add rust-src
rustup component add llvm-tools-preview
```

## Build

```bash
xargo bootimage
```
