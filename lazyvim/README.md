# LazyVim configuration for WSL Debian
This folder contains **customisations**, not the complete LazyVim starter distribution or a backup of the current PC.

## Install
1. Follow the [LazyVim starter instructions](https://www.lazyvim.org/installation).
2. Copy `lua/config/options.lua` and `lua/plugins/python.lua` from this folder into the matching paths under `~/.config/nvim/`.
3. Start `nvim`, allow plugins to sync, and run `:checkhealth`, `:Lazy`, and `:Mason`.

The Python extra provides language tooling integration. Install a Python virtual environment separately per project. Before replacing any existing config, back it up and merge changes. Clipboard integration may require a compatible WSL clipboard provider; remove `unnamedplus` if it is not available.

The complete WSL/Python walkthrough is in the associated Notion page:
https://app.notion.com/p/401482b2363781999d47efe171c18657
