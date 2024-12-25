# Neovim Configuration

This repository contains my personalized Neovim configuration, primarily written in Lua, leveraging [LazyVim](https://github.com/LazyVim/LazyVim) as the starter template. This is highly tailored for Python development.

## Prerequisites

- **Neovim**: Ensure you have Neovim version 0.8.3 or above installed. You can download it from the [official Neovim releases page](https://github.com/neovim/neovim/releases).

- **Node.js and npm**: Required for installing certain language servers. It's recommended to use Node Version Manager (nvm) to install the latest LTS version.

  ```bash
  nvm install --lts
  nvm use --lts
  npm --version
  ```

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/blakeridgway/nvim-config.git ~/.config/nvim
   ```
2. **Verify the Setup**:

   Open Neovim and check if the plugins and language servers are correctly installed. You can use `:LspInfo` to verify LSP configurations.

## Key Mappings

The key mappings are defined in `nvim/lua/core/keymaps.lua`.

**Note**: The `<leader>` key is set to spacebar by default.

## Additional Resources

- **LazyVim Documentation**: For more details on the LazyVim starter template, refer to the [LazyVim documentation](https://lazyvim.github.io/).

- **Neovim Lua Guide**: To understand more about configuring Neovim with Lua, check out the [Neovim Lua Guide](https://github.com/nanotee/nvim-lua-guide).

- **Neovim LSP Configuration**: For setting up language servers, consult the [nvim-lspconfig repository](https://github.com/neovim/nvim-lspconfig).
