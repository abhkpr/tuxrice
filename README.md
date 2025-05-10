# tuxrice
Custom .bashrc with developer-friendly aliases, colorful prompts, Kitty theme switchers, and fuzzy theme preview using fzf.

## Custom `.bashrc` for Devs & Kitty Users

A personalized `.bashrc` config focused on enhancing terminal productivity and theming—perfect for developers and Kitty terminal users. Includes helpful aliases, colored prompts, fzf-powered Kitty theme switching, and improved command history behavior.

---

## Features

- **Kitty Theme Manager** with `fzf` preview and auto-switching
- Aliases for faster file navigation (`ll`, `la`, `l`)
- Smart history controls (`HISTCONTROL`, `histappend`)
- Color-enhanced `ls`, `grep`, `egrep`, etc.
- Alert alias for long-running tasks
- Auto-sourcing `.bash_aliases` and Bash completion
- Optional greet script for Kitty terminal first tab

---

## Requirements

- [Kitty Terminal](https://sw.kovidgoyal.net/kitty/)
- [fzf](https://github.com/junegunn/fzf)
- A folder of themes: `~/.config/kitty/themes/themes/*.conf`

---

## Installation

```bash
# 1. Clone this repository
git clone https://github.com/yourusername/bashrc-dev-config.git

# 2. Backup your existing bashrc
cp ~/.bashrc ~/.bashrc.backup

# 3. Replace with the new one
cp bashrc-dev-config/.bashrc ~/.bashrc

# 4. Reload the shell
source ~/.bashrc

```

---

## Kitty Theme Commands
kittythemes         # List available themes
kittytheme          # Fuzzy-pick a theme with preview using fzf
kittytheme Dracula  # Manually switch to a theme

Make sure your Kitty themes are stored at:
~/.config/kitty/themes/themes/*.conf




