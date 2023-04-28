# pretty_dotfiles
The dotfiles for my Linux theme. Managed by chezmoi, built for Arch.

With a focus on productivity (small gaps and maximized screen real estate) while still adding sprinkles of minimalistic and modern design, this theme will be interesting for anyone looking to get into Bwpsm fast and uncomplicated.

## Screenshots

<p align="center">
  <img alt="empty desktop with PolyBar" src="img/bspwm_theme-desktop.png" style="border-radius: 1rem; box-shadow: 4px 4px 12px black">
  <br>
  An empty desktop using PolyBar
</p>

<p align="center">
  <img alt="screenshot of multiple terminals" src="img/bspwm_theme-terminal.png" style="border-radius: 1rem; box-shadow: 4px 4px 12px black">
  <br>
  The Alacritty terminal with Starship, Macchina and Neofetch
</p>

<p align="center">
  <img alt="screenshot of notifications with differing urgency" src="img/bspwm_theme-notifications.png" style="border-radius: 1rem; box-shadow: 4px 4px 12px black">
  <br>
  The Alacritty terminal with Starship, Macchina and Neofetch
</p>

## Programs used

- WM: Bwpsm
- Keyboard Daemon: sxhkd
- Compositor: picom
- Bar: PolyBar
- Notifications: Dunst
- Menus: Rofi
- Terminal: Alacritty
  - Fetch: Macchina & Neofetch
  - Prompt: Starship

## Setup Information:

I've never tried copy-pasting this config onto another device, so there might be some minor issues, especially inside the Bwpsm config (since it expects to specific display names) and PolyBar (which also expects multiple displays).

Also note that there is no `.bashrc` included in the repo, meaning you need to manually add the call to neofetch/macchina/starship to your local config.

## Credits

- The main OS config files (mainly bspwm, Starship and sxkhd) are based on the stock config of the EndeavourOS Bspwm theme, but have been modified a lot.
- The Dunst notification design is heavily based on the [Dracula Theme](https://github.com/dracula/dunst) with minor adjustments. 