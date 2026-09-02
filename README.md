# Neovim Setup

## Step 1 — Install lazy.nvim

```bash
git clone --filter=blob:none --branch=stable \
https://github.com/folke/lazy.nvim.git \
~/.local/share/nvim/lazy/lazy.nvim
```

## Step 2 — Install your config

```bash
mkdir -p ~/.config/nvim
mv init.lua ~/.config/nvim/init.lua
```

## Step 3 — Start Neovim

```bash
nvim
```

Your `init.lua` will load your settings and lazy.nvim will install the configured plugins.
