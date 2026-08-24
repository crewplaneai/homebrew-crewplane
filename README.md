# Homebrew Tap for Crewplane

This is the official Homebrew tap for [Crewplane](https://github.com/crewplaneai/crewplane), a Markdown-native control plane for AI coding CLIs.

## Install

Install Crewplane with one fully qualified command:

```bash
brew install crewplaneai/crewplane/crewplane
crewplane --help
```

The fully qualified name lets Homebrew add this tap while trusting only the Crewplane formula.

## Upgrade

```bash
brew upgrade crewplane
crewplane --version
```

## Uninstall

```bash
brew uninstall crewplane
```

## Formula maintenance

[The Crewplane source repository](https://github.com/crewplaneai/crewplane) owns release preparation. It generates and validates `packaging/homebrew/Formula/crewplane.rb` against the published PyPI source distribution before that formula is copied into this tap.

Formula updates should therefore be prepared in the source repository and published here after the matching PyPI artifact is live. Avoid editing `Formula/crewplane.rb` independently because a later generated update would overwrite those changes.

For product documentation, bug reports, and feature requests, use the [Crewplane repository](https://github.com/crewplaneai/crewplane).

## License

Crewplane and this tap are available under the [Apache License 2.0](LICENSE).
