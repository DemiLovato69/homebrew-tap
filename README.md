# Foundry OpenCode Homebrew tap

This tap packages the macOS CLI and setup wizard for [Foundry OpenCode](https://github.com/DemiLovato69/Foundry-OpenCode).

## Install

Once the first release with Homebrew support adds `Formula/foundry-opencode.rb` to this repo, run:

```sh
brew install DemiLovato69/tap/foundry-opencode
foundry-opencode-gui
```

Homebrew builds both executables from source on Apple Silicon or Intel. Installing the formula does not modify your OpenCode configuration. The GUI walks you through first-time setup.

## Upgrade or remove the installer

```sh
brew upgrade DemiLovato69/tap/foundry-opencode
```

Use `foundry-opencode update --dry-run` to preview a separate configuration update. To remove only the installer executables and keep your configs, tokens, and sessions:

```sh
HOMEBREW_NO_AUTOREMOVE=1 brew uninstall DemiLovato69/tap/foundry-opencode
```
