# pot-o-extensions

DeFi, staking, and external-chain extensions for the PoT-O validator.

## Usage

```toml
[dependencies]
pot-o-extensions = "0.1"
```

Depends on `pot-o-core`, `ai3-lib`, and `pot-o-mining`.

## Versioning

Releases follow semantic versioning. To publish:

1. Bump `version` in `Cargo.toml`.
2. Create a tag: `git tag v0.1.1 && git push origin v0.1.1`.
3. CI will publish to crates.io and GitHub Packages.

## License

MIT
