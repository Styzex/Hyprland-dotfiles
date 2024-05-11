# Hyprland-dotfiles
These are my hyprland dotfiles.
Also the color scheme is from the kanagawa theme.

# Dependencies
- `hyprland`: window manager
- `hyprpaper`: wallpaper manager
- (optional) `wlogout`: logout menu
- `rofi-wayland`: app launcher
- `alacritty`: terminal emulator
- `thunar`: file manager
- `neovim`: text editor
- `brave`: web browser
- `grim, slurp`: screenshots
- `viewnior`: image viewer

# Shortcuts
- `SUPER+Q`: launches alacritty
- `SUPER+D`: logout menu
- `SUPER+SPACE`: rofi app launcher
- `SUPER+E`: thunar
- `SUPER+X`: kill active window
- `SUPER+F`: brave
- `SUPER+B`: grim select area
- everything else is default

# How to change the wallpaper
- Got to `~/.config/hypr` and open the `hyprpaper.conf`.
- Change the wallpaper directory in `hyprpaper.conf` to your wallpaper directory.

### Example of the hyprpaper.conf
```
preload = ~/wallpaper/ghibli-japanese-walled-garden.png
wallpaper = ,~/wallpaper/ghibli-japanese-walled-garden.png
```
