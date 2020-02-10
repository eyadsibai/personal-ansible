# Steps
- `sudo pacman -Syu yay`
- `yay ansible`
- `yay ansible-aur`
- `ansible-playbook prepare_laptop.yml -K -c local -vvv`
- upgrade nvidia drivers
- uncomment color from `/etc/pacman.conf`


# for dell laptop
- sudo pacman -S fwupd
