# Glass Buttons

A small GNOME Shell extension (GNOME 49–51) that makes the buttons in Quick Settings, the calendar/notification popup and app folders translucent. They then match glassy popups from [Blur my Shell](https://github.com/aunetx/blur-my-shell) (popup blur on), instead of showing solid grey or accent-colored buttons.

It also rotates the `>` arrows of Quick Settings items to a `V` while their submenu is open.

Most of the look is in `stylesheet.css`. Change the alpha values there to taste. The selectors come from GNOME Shell's default (Adwaita) shell theme.

## Install

```sh
git clone https://github.com/inxomnyaa/glass-buttons ~/.local/share/gnome-shell/extensions/glass-buttons@inxomnyaa
# log out and back in, then:
gnome-extensions enable glass-buttons@inxomnyaa
```
