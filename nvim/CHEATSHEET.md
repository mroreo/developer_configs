# Hotkey Cheatsheet

`<leader>` = `space`

## Navigation
| Key | Action |
|-----|--------|
| `<space>ff` | Find files |
| `<space>fg` | Search text in files |
| `<space>fb` | Find buffers |
| `<space>e` | Toggle file explorer |
| `<Tab>` | Next buffer |
| `<S-Tab>` | Previous buffer |
| `<space>x` | Close buffer |

## LSP & Code
| Key | Action |
|-----|--------|
| `gd` | Go to definition |
| `K` | Hover documentation |
| `<space>ca` | Code action |
| `<space>rn` | Rename |
| `<space>d` | Generate docstring (numpy style) |

## Completion (Insert Mode)
| Key | Action |
|-----|--------|
| `<C-Space>` | Trigger completion |
| `<Tab>` | Next item |
| `<S-Tab>` | Previous item |
| `<CR>` | Confirm |
| `<C-e>` | Cancel |

## REPL
| Key | Action |
|-----|--------|
| `<space>sl` | Send line |
| `<space>sc` | Send selection |
| `<space>sq` | Quit REPL |
| `<space>cl` | Clear REPL |

## File Explorer
Press `<space>e` to open, then:
| Key | Action |
|-----|--------|
| `a` | New file/folder (end with `/` for folder) |
| `d` | Delete |
| `r` | Rename |
| `<CR>` | Open file |
| `q` | Close explorer |

## File Commands
| Command | Action |
|---------|--------|
| `:e filename` | Create/edit new file |
| `:w` | Save |
| `:q` | Quit |
| `:wq` | Save and quit |
| `:LspRestart` | Restart LSP server |

## Text Objects
| Key | Action |
|-----|--------|
| `vi"` | Select inside quotes |
| `va"` | Select around quotes |
| `ci(` | Change inside parens |
| `di{` | Delete inside braces |
| `viw` | Select word |

## Basic Vim Navigation
| Key | Action |
|-----|--------|
| `h` `j` `k` `l` | Left, Down, Up, Right |
| `w` | Next word |
| `b` | Previous word |
| `e` | End of word |
| `0` | Start of line |
| `$` | End of line |
| `gg` | First line |
| `G` | Last line |
| `{` `}` | Previous/next paragraph |

## Basic Editing
| Key | Action |
|-----|--------|
| `i` | Insert before cursor |
| `a` | Insert after cursor |
| `o` | New line below |
| `O` | New line above |
| `dd` | Delete line |
| `yy` | Copy line |
| `p` | Paste |
| `u` | Undo |
| `<C-r>` | Redo |
