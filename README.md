--Notes--

Heres a command that should automatically configure everything (hopefully, im still working on this)

``` sudo pacman -S --needed git hyprland swww kitty waybar wofi sddm zsh nerd-fonts dolphin firefox bluez bluez-utils pipewire pavucontrol && sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" && sudo systemctl enable sddm && git clone https://github.com/Skye-The-Time-Beast/Dotfiles_teehee.git && mkdir ~/.config && cd ~/Dotfiles_teehee/ && cp -r ~/Dotfiles_teehee/* ~/.config && cp .zshrc ~/  ```

Ensure you reboot! <3
