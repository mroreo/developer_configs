# Neovim Configuration

Simple Python development setup with conda support.

## Structure

```
~/.config/nvim/
├── init.lua                    # Main config (settings & keymaps)
├── lua/
│   └── plugins/
│       ├── colorscheme.lua     # Catppuccin theme
│       ├── ui.lua              # nvim-tree, bufferline
│       ├── telescope.lua       # Fuzzy finder
│       ├── treesitter.lua      # Syntax highlighting & neogen
│       ├── completion.lua      # nvim-cmp
│       ├── lsp.lua             # LSP config (Pyright)
│       └── repl.lua            # Iron REPL
├── README.md
└── CHEATSHEET.md
```

## Plugins

- **catppuccin** - Colorscheme
- **nvim-tree** - File explorer
- **telescope** - Fuzzy finder
- **bufferline** - Buffer tabs
- **treesitter** - Syntax highlighting
- **neogen** - Docstring generator (numpy style)
- **nvim-lspconfig + mason** - LSP (Pyright)
- **nvim-cmp** - Auto-completion
- **iron.nvim** - Python REPL

## Installation

1. **Backup existing config:**
   ```bash
   mv ~/.config/nvim ~/.config/nvim.backup
   ```

2. **Copy this config to ~/.config/nvim/**

3. **Install dependencies:**
   - Neovim >= 0.11
   - ripgrep (for live grep): `brew install ripgrep`
   - A Nerd Font for icons

4. **Start Neovim:**
   ```bash
   nvim
   ```
   lazy.nvim will automatically install all plugins on first launch.

## Usage with Conda

```bash
conda activate your_env
nvim file.py
```

LSP automatically detects the activated conda environment.
