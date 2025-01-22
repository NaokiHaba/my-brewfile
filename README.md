# Development Environment Setup

## 1. Xcode Installation

```bash
# Install Command Line Tools
$ xcode-select --install

# Install Homebrew
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## 2. Brewfile Setup

1. Create `.Brewfile` in your home directory
2. Install required packages:

```bash
$ brew bundle --global
```

## 3. Brewfile Management

When adding new packages:

```bash
# Export current package list to .Brewfile
$ brew bundle dump --force --global

# Install packages from Brewfile
$ brew bundle --global
```
