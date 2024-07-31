# Dotfiles

My personal dotfiles to ✨spice✨ my system up a bit. Not really fleshed out but I'm trying. 

## 🗒️ Installation

1. Clone this repo

```bash
git clone https://github.com/nerometa/dotfiles.git
cd dotfiles
```

1. Install GNU Stow and tmux

Ubuntu

```bash
sudo apt install stow tmux
```

Arch Linux

```bash
sudo pacman -S stow tmux
```

1. Install TPM (Tmux Plugin Manager)

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

1. Run `stow .` to symlink config (make sure you're in the `dotfiles` directory)

```bash
stow .
```

## 🧱 Components

- `wezterm` - Trusty terminal
- `.config/nvim` - (Neovim) Text editor. Looking to transition from VSCode
- `.config/tmux` - Terminal multiplexer, one term for coding, one term for `npm run start`

## 🛣 Roadmap

- [x] installation script (Kinda. Use [Stow](https://www.gnu.org/software/stow/) to manage the configs.)
- [ ] rice shell (zsh, fish, etc.)

More to come
