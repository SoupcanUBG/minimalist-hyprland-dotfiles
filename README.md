# To install do:

`stow --ignore='gtk' -t ~ hypr kitty rofi swaync waybar wallpaper`

## manually put the folders inside gtk in the right place and i recommend using nwg-look or lxappearance


### these are my dotfiles for hyprland

# GTK THEMES

#### ICONS

To do the icons install "lxappearance" and then at the icons bit press install then select gtk/icons/yamis.tar.gz and apply it using "nwg-look"

#### THEME

For the theme cd into /gtk/theme/ and move the numix folder to /usr/share/themes - this is the command: `sudo mv gtk/theme/numix /usr/share/themes/`

# configuration

When i used a VM this is what i had to edit and install

`sudo pacman -R dunst && sudo pacman -S swaync && sudo pacman -S rofi-wayland && sudo pacman -S swww && sudo pacman -S lxappearance && sudo pacman -S nwg-look && sudo pacman -S thunar && sudo pacman -S nerd-fonts && sudo pacman -S git && sudo pacman -S stow && sudo pacman -S firefox &&`
