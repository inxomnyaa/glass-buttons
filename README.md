# Glass Buttons

A small GNOME Shell extension (GNOME 49–51) for a glassier shell, made to go with [Blur my Shell](https://github.com/aunetx/blur-my-shell)'s blurred popups.

## Features

- **Translucent buttons:** Quick Settings toggles, the calendar/notification popup and app folders get translucent glass buttons that match the blurred popups behind them, instead of solid grey or accent-colored ones.
- **Rotating submenu arrows:** the `>` arrow on a Quick Settings item (Wi-Fi, Bluetooth, power mode, …) turns smoothly into a `V` while its submenu is open and turns back when it closes. This also works for items that other extensions add.

Most of the look is in `stylesheet.css`. Change the alpha values there to taste. The selectors come from GNOME Shell's default (Adwaita) shell theme. The arrow animation is in `extension.js`.

## Install

```sh
git clone https://github.com/inxomnyaa/glass-buttons ~/.local/share/gnome-shell/extensions/glass-buttons@inxomnyaa
# log out and back in, then:
gnome-extensions enable glass-buttons@inxomnyaa
```
