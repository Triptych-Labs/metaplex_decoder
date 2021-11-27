# Simple Metaplex Decoder (WIP)

## Install From Source

Install [Rust](https://www.rust-lang.org/tools/install).

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Clone the source:

```bash
git clone git@github.com:samuelvanderwaal/metaplex_decoder.git
```

Change directory and install or build with Rust:

```bash
cd metaplex_decoder
```

```bash
cargo install --path ./
```

or

```bash
cargo build --release
```

## Example Usage
Run the program:

```
./metaplex_decoder <mint_account> <network>
```

This will yield the metadata as single line JSON to stdout.
