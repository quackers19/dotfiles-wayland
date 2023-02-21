# Dotfiles
All the dotfiles are in folder 

- Windows Manager: Hyprland
- Theme: breeze-gtk
- Run: Fuzzel
- Editor: nano
- Bar: Waybar
- Shell: zsh with powerline10k
- Terminal: alacritty 
- File manger: Thunar
- Wallpaper manger: swaybg


List of packages that need to be installed
dunst - notifcations
polkit-kde-agent - auth
Fuzzel
Waybar-hyprland
Thunar
swaybg
alacritty

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
