# homebrew-tap

Homebrew tap for [migration-machine](https://github.com/callmesukhi/migration-machine), a tool to move your whole Mac setup to a new machine without Migration Assistant or Time Machine.

## Install

```bash
brew install callmesukhi/tap/migration-machine
migrate wizard
```

To track the latest `main` instead of the tagged release:

```bash
brew install --HEAD callmesukhi/tap/migration-machine
```

The guided setup uses [swiftDialog](https://github.com/swiftDialog/swiftDialog). `migrate wizard` offers to install it for you, or grab it yourself with `brew install --cask swiftdialog`.

## What is in this repo

`Formula/migration-machine.rb` is the only thing here. It is a copy of the source of truth in the main repo at `packaging/homebrew/migration-machine.rb`; that file is edited there and copied here on each release.

## Issues and contributions

Please file bugs and feature requests on the [main repository](https://github.com/callmesukhi/migration-machine/issues). This repo only hosts the formula, so anything opened here will be redirected there.

## License

[MIT](https://github.com/callmesukhi/migration-machine/blob/main/LICENSE), same as migration-machine.
