# i3-plasma

git clone https://github.com/peterge1998/i3-plasma && cd i3-plasma

## Move Config:

`mv i3/config ~/.config/i3/config`

`mv plasma-i3.desktop /usr/share/xsessions/`

## Install required programs:

`pacman -S i3-gaps i3status #rofi` 

## For Screenshots:

`pacman -S xclip scrot`





# Generic Arch/Manjaro setup. Not releated to i3-plasma at all:



yay -S spotify firefox teamspeak3

### Spotify:

If Spotify gets muted on desktop "beeps", comment out "module-role-cork" in pulse audio configuration file:

`/etc/pulse/default.pa`

`load-module module-role-cork `

Or simply unload it with: `pactl unload-module module-role-cork`


### Firefox:

Enable Mousewheel scrolling: Preferences -> General -> Use autoscrolling
