# .dotfiles

My dotfile configurations

## Prerequisites:

- [Homebrew](https://brew.sh/)
- Xcode Command Line Tools 

### Pre-Installation

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

To install yadm temporarily, then clone the .dotfiles repo and bootstrap the system, run the following command:

```bash
curl -sL https://github.com/Supakornn/.dotfiles/raw/main/pre_bootstrap.sh | bash
```

### Update plugins with submodules

```bash
yadm submodule update --remote
```
