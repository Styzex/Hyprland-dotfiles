# Hyprland-dotfiles
My hyprland dotfiles are based on the kanagawa theme for vim.

# Dependencies
- `hyprland`: window manager
- `hyprpaper`: wallpaper manager
- `wlogout`: logout menu
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

# How to change the wallpaper
- Got to `~/.config/hypr` and open the `hyprpaper.conf`.
- Change the wallpaper directory in `hyprpaper.conf` to your wallpaper directory.

### Example of the hyprpaper.conf
```
preload = ~/wallpaper/ghibli-japanese-walled-garden.png
wallpaper = ,~/wallpaper/ghibli-japanese-walled-garden.png
```
