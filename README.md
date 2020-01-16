# ASUS gl553vd-dm432 Manjaro KDE

### Package Sync
```
sudo pacman -Sy
```

### Packages I Use
```
pamac install yay aria2 speedtest-cli telegram-desktop kdenlive inkscape virtualbox flameshot deepin-terminal neofetch gtop gedit ttf-ubuntu-font-family telegram-desktop soundconverter obs-studio simplescreenrecorder filezilla qbittorrent etcher opera pinta materia-theme ttf-font-awesome ttf-font-awesome-4 ttf-roboto skypeforlinux-stable-bin all-repository-fonts ttf-wps-fonts wps-office wps-office-extension-turkish-dictionary laptop-mode-tools powertop thermald discord pycharm-community-eap
```

### Dual-boot Wrong time problem
```
timedatectl set-local-rtc 1 --adjust-system-clock
```

### If You Have an SSD
```
sudo systemctl enable fstrim.timer
```

### Enable TLP and LMT and Thermald
```
systemctl enable --now tlp
systemctl enable --now tlp-sleep.service
sudo systemctl enable --now laptop-mode.service
sudo systemctl enable --now thermald
```
