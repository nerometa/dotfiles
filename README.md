# Dotfiles

My personal dotfiles to ✨spice✨ my system up a bit. Not really fleshed out but I'm trying. 

## 🗒️ Installation

Clone this repo

```sh
git clone https://github.com/nerometa/dotfiles.git
cd dotfiles
```

Install GNU Stow and tmux

### Ubuntu

```bash
sudo apt install stow tmux
```

### Arch Linux

```bash
sudo pacman -S stow tmux
```

Install TPM (Tmux Plugin Manager)

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Install Neovim from pre-built packages

```bash
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz
sudo rm -rf /opt/nvim
sudo tar -C /opt -xzf nvim-linux64.tar.gz
```

Run `stow .` to symlink config (make sure you're in the `dotfiles` directory)

```bash
stow .
```

## Structure

- `wezterm` - Trusty terminal
- `.config/nvim` - Text editor.
- `.config/tmux` - Terminal multiplexer, one term for coding, one term for `npm run start`

## 🛣 Roadmap

- [x] installation script (Kinda. Use [Stow](https://www.gnu.org/software/stow/) to manage the configs.)
- [ ] rice shell (zsh, fish, etc.)

More to come...
