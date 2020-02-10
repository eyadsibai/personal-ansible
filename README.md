# Steps
- `sudo pacman -Syu yay`
- `yay ansible`
- `yay ansible-aur`
- `ansible-playbook prepare_laptop.yml -K -c local -vvv`
- upgrade nvidia drivers
- uncomment color from `/etc/pacman.conf`
- `yay -S --mflags --skipinteg yakyak`


# for dell laptop
- sudo pacman -S fwupd
