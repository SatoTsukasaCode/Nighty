# Nighty
An i3 rice with a night feel for Arch Linux
![screenshot](https://github.com/SatoTsukasaCode/Nighty/blob/main/1_002.png)

# Dependencies:
### Mains
i3,
polybar,
nitrogen,
picom,
alacritty,
ibhagwan,

## Extras
neofetch


# Installtion
install ibhagwann like this:
```
$ git clone https://github.com/ibhagwan/picom-ibhagwan-git
$ cd picom-ibhagwan-git
$ makepkg -si
```

install all the other dependencies using pacman like this:
```
$ sudo pacman -S <pacakge_name>
```

use nitrogen to set up your background (mine is included here "9w9.jpg")

extarct all the directories into `~/.config~`

reboot and you are done!
