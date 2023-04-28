# pretty_dotfiles
the dotfiles for my linux theme. managed by chezmoi, built for arch.

## Screenshots

`coming soon`

## Programs used

- WM: Bwpsm
- Keypress Daemon: Sxhkd
- Compositor: picom
- Bar: Polybar
- Notifications: Dunst
- Menus: Rofi
- Terminal: Alacritty
  - Fetch: Macchina & Neofetch
  - Prompt: Starship

## Setup Information:

I've never tried copy-pasting this config onto another device, so there might be some minor issues, especially inside the Bwpsm config (since it expects to specific display names) and Polybar (which also expects multiple displays).

Also note that there is no `.bashrc` included in the repo, meaning you need to manually add the call to neofetch/macchina/starship to your local config.
