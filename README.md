# Steps
- `sudo pacman -Syu yay`
- `yay ansible`
- `yay ansible-aur`
- `ansible-playbook prepare_laptop.yml -K -c local -vvv`
- upgrade nvidia drivers
- uncomment color from `/etc/pacman.conf`
- `yay -S --mflags --skipinteg yakyak`
- `sudo systemctl enable bluetooth.service`
- cat /usr/share/nano/nanorc.nanorc > ~/.nanorc


# for dell laptop
- sudo pacman -S fwupd


# list of explicit packages installed on ur system
- pacman -Qqe  > pkgs.txt
