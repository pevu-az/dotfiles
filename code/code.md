# VS Code & Kiro
This folder contains shared configuration files for VS Code and Kiro (both are Code OSS based).

## Setup

### VS Code
```bash
ln -s ~/dotfiles/code/keybindings.json ~/Library/Application\ Support/Code/User/keybindings.json
ln -s ~/dotfiles/code/settings.json ~/Library/Application\ Support/Code/User/settings.json
```

### Kiro
```bash
ln -s ~/dotfiles/code/keybindings.json ~/Library/Application\ Support/Kiro/User/keybindings.json
ln -s ~/dotfiles/code/settings.json ~/Library/Application\ Support/Kiro/User/settings.json
```

Note: Back up or remove existing files before creating symlinks.

## Shared Configuration
Both editors use the same `settings.json` and `keybindings.json`. Editor-specific settings are included in the shared config:
- Kiro-specific: `kiroAgent.*` settings (ignored by VS Code)
- VS Code-specific: `telemetry.*` settings (ignored by Kiro)

## Extensions to install
TODO: automatic syncing and installing
1. VSCode NeoVim
2. One Dark Pro
3. VSCode Icons
4. Remote SSH

## Things to note
* Mac Keybindings: https://gist.github.com/gplusplus314/863afdbe1f5a32be4486521306e9217c
