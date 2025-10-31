# Install 404README

This is a single-file CLI written in Python. No build required.

## Requirements
- Python 3.8+ (check with `python3 --version`)

## Option A — Run locally (no install)
1. Make sure the file is executable:
   - `chmod +x ./404README/404README`
2. Run it:
   - `./404README/404README`

## Option B — Install to your PATH (recommended)
1. Create a local bin directory if it doesn’t exist:
   - `mkdir -p ~/.local/bin`
2. Copy the tool and make it executable:
   - `cp ./404README/404README ~/.local/bin/404README`
   - `chmod +x ~/.local/bin/404README`
3. Ensure `~/.local/bin` is on your PATH. For example:
   - Bash: `echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc && source ~/.bashrc`
   - Zsh:  `echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.zshrc && source ~/.zshrc`
4. Test:
   - `404README --help` or just `404README`

## Upgrade
- Re-copy the new file over the old one:
  - `cp ./404README/404README ~/.local/bin/404README && chmod +x ~/.local/bin/404README`

## Uninstall
- Remove the binary:
  - `rm ~/.local/bin/404README`
