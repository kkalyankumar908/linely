# linely

Fast line/byte counter written in Rust

## What it does

- Reads stdin or multiple files
- Parallel over files with std threads
- Counts lines, words and bytes like wc
- Zero dependencies outside std

## Getting started

```bash
cargo build --release
```

## Examples

```bash
./target/release/linely src/*.rs
cat README.md | ./target/release/linely
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   └── usage.md
├── src/
│   └── main.rs
├── .gitignore
├── CODE_OF_CONDUCT.md
├── Cargo.toml
└── LICENSE
```

## Development

```bash
cargo build
cargo clippy -- -D warnings
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas

## License

MIT - see [LICENSE](LICENSE).
