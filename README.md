# linely

Fast line/byte counter written in Rust

## Features

- Reads stdin or multiple files
- Parallel over files with std threads
- Counts lines, words and bytes like wc
- Zero dependencies outside std

## Usage

```bash
./target/release/linely src/*.rs
cat README.md | ./target/release/linely
```

## Getting started

```bash
cargo build --release
```

## Project structure

```text
├── .github/
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── main.rs
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── Cargo.toml
├── LICENSE
└── SECURITY.md
```

## Development

```bash
cargo test
cargo clippy -- -D warnings
```

## License

MIT - see [LICENSE](LICENSE).
