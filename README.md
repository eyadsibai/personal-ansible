# README

## Steps

- `sudo pacman -Syu yay`
- `yay ansible`
- `yay ansible-aur`
- `ansible-playbook -i inventory site.yml -K -c local -vvv`
- upgrade nvidia drivers
- uncomment color from `/etc/pacman.conf`
- `yay -S --mflags --skipinteg yakyak`
- `sudo systemctl enable bluetooth.service`
- `echo "include /usr/share/nano/*.nanorc" >> ~/.nanorc`
- `cp /usr/share/oh-my-zsh/zshrc ~/.zshrc`
- `rm -rf ~./'.moonchild productions'`
- `# pacman -Rdd dmenu-manjaro`

## for dell/thinkpad laptop

- sudo pacman -S fwupd

## list of explicit packages installed on ur system

- pacman -Qqe  > pkgs.txt

## resources

https://linuxhint.com/pulseaudio_arch_linux/
