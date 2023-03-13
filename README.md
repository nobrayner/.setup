# .setup

```bash
curl -sSf https://raw.githubusercontent.com/nobrayner/.setup/main/ansible-run | sh
```

## Available Tags
- `install` - sets up a system from scratch
- `app-setup` - sets up repos
- `apps` - installs/updates apps
- `asdf` - installs/updates asdf
- `bspm` - installs/updates bspwm
- `core` - installs/updates core packages, fonts, starship
- `dotfiles` - installs/updates dotfiles
    - `stow` - Stows dotfiles
- `git` - Sets up git config
- `node` - installs/updates node and related packages
- `nvim` - installs/updates neovim
- `rust` - installs/updates rust
- `ssh` - sets up ssh keys
- `zsh` - installs/updates zsh
