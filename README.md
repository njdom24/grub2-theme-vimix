# Grub2 Theme Vimix
###### AUTHOR: [vinceliuice](http://gnome-look.org/content/show.php/Grub-themes-vimix?content=169954)

# Installation
### Arch Linux
##### Place files in directory :
```shell
Place the 'Vimix' folder in /boot/grub/themes/
```
##### Edit /etc/default/grub :
```shell
GRUB_THEME="/boot/grub/themes/Vimix/theme.txt"
```
##### Update grub :
```shell
$ grub-mkconfig -o /boot/grub/grub.cfg
```
### Fedora 28/29
##### Place files in directory :
```shell
Place the 'Vimix' folder in /boot/grub/themes/
```
#### Copy this at the bottom 
```shell
$ GRUB_THEME="/boot/grub2/themes/Vimix/theme.txt"
```
#### Place # marker in front 
```shell
$ GRUB_TERMINAL_OUTPUT="console"
```
##### Update grub :
```shell
$ sudo grub2-mkconfig -o /etc/grub2.cfg
```

# Screenshot
![screenshot](/preview.jpg?raw=true)
