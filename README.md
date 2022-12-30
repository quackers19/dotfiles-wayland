# Dotfiles
All the dotfiles are in folder 

- Windows Manager: Hyprland
- Theme: breeze-gtk
- Run: Fuzzel
- Editor: nano
- Bar: Waybar
- Shell: zsh with powerline10k
- Terminal: foot
- File manger: Thunar
- Wallpaper manger: Hyprpaper


List of packages that need to be installed
dunst - notifcations
polkit-kde-agent - auth
hyprpaper-git
Fuzzel
Waybar
Thunar
swaybg

Wll add screen shots later


Notes about post-install tweaks
- install breeze-gtk for theme
- make sure to install pacman-contrib and enable paccache.timer this clear pacman cache every week
  - use systemctl enable paccache.timer
- enable parallel downloads in pacman.conf
- install reflector to sync pacman download mirrors
  - enable reflector.service so it syncs on boot
- edit .desktop file for hyprland so you can passthrough enviroment varibles https://wiki.hyprland.org/Configuring/Environment-variables/
- enable disk triming enable fstrim.timer
