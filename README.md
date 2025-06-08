# Pre-requisites:
- Neovim 0.11
- Nerd Font as your terminal font (make sure the font doesn't end with Mono)
- ripgrep (for searching with telescope)
- delete old neovim folders
  ```bash
  rm -rf ~/.config/nvim
  rm -rf ~/.local/state/nvim
  rm -rf ~/.local/share/nvim
  ```

# Install
## 1. Clone config
```bash
git clone https://github.com/elmasibrahim/nvim-conf.git ~/.config/nvim
```
## 2. Start Neovim
```bash
nvim
```
## 3. Install packages
```
:MasonInstallAll
```
## 4. Delete .git from nvim folder
