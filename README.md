# homebrew-aixgate

Homebrew tap for [aixgate](https://github.com/aixgo-dev/aixgate) — a deny-by-default sandbox for AI coding agents.

## Install

```bash
brew install aixgo-dev/aixgate/aixgate
```

Or, equivalently:

```bash
brew tap aixgo-dev/aixgate
brew install aixgate
```

## Usage

```bash
aixgate run -- claude
aixgate run -- aider
aixgate run -- cat .env   # → "Operation not permitted"
```

See the [aixgate README](https://github.com/aixgo-dev/aixgate#readme) for documentation.

## How this tap is updated

The formula in `Formula/aixgate.rb` is generated and pushed automatically by [GoReleaser](https://goreleaser.com/) on every tagged release of [aixgate](https://github.com/aixgo-dev/aixgate). Do not edit it by hand — changes will be overwritten on the next release.

## License

[MIT](LICENSE).
