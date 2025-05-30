# Custom Oh My Posh Themes Collection

This repository contains custom Oh My Posh themes optimized for development environments with support for multiple languages and tools.

## 🎨 Available Themes

- `34ohmyposh.json` - Modern theme with extensive development tooling support
- `ohmyposh.json` - Clean and minimalistic theme with Spotify integration
- `ohmyposhv3-v2.json` - Version 3 compatible theme with enhanced Git status
- `stelbent-compact.minimal.omp.json` - Compact theme with essential information

## 🚀 Installation

### Windows

1. Install Oh My Posh using winget:
```powershell
winget install JanDeDobbeleer.OhMyPosh
```

2. Install a Nerd Font (recommended Hack):
```powershell
oh-my-posh font install Hack
```

3. Add to your PowerShell profile:
```powershell
notepad $PROFILE
```

Add this line:
```powershell
oh-my-posh init pwsh --config 'PATH_TO_THEME.json' | Invoke-Expression
```

### macOS

1. Install Oh My Posh using Homebrew:
```bash
brew install jandedobbeleer/oh-my-posh/oh-my-posh
```

2. Install a Nerd Font:
```bash
brew tap homebrew/cask-fonts
brew install --cask font-hack-nerd-font
```

3. Add to your shell profile (~/.zshrc or ~/.bashrc):
```bash
eval "$(oh-my-posh init zsh --config PATH_TO_THEME.json)"
```

### Linux

1. Install Oh My Posh:
```bash
curl -s https://ohmyposh.dev/install.sh | bash -s
```

2. Install a Nerd Font:
```bash
# Download and install manually from https://www.nerdfonts.com/
```

3. Add to your shell profile (~/.bashrc or ~/.zshrc):
```bash
eval "$(oh-my-posh init bash --config PATH_TO_THEME.json)"
```

## ✨ Features

- Git status integration
- Language version displays (.NET, Python, Node.js, Java)
- Framework detection (Spring Boot, Angular, React)
- Docker context
- Execution time
- Root user indicator
- Directory path
- Error status
- Spotify integration (in supported themes)

## 🛠️ Configuration

To use any of the themes, copy the desired `.json` file to your Oh My Posh themes directory and update your shell profile to point to the theme.

## 🎨 Terminal Configuration

For the best experience:
- Use a Nerd Font compatible terminal
- Enable font ligatures if supported
- Configure your terminal to use the installed Nerd Font

## 📝 License

Feel free to modify and use these themes as you like!