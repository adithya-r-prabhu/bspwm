# BSPWM Setup and Theme for EndeavourOS
**BSPWM EndeavorOS Community Edition**


## To Install manually

    git clone https://github.com/EndeavourOS-Community-Editions/bspwm.git

    cd bspwm

    bash bspwm-install.sh
   
## Contained In The Script
    cp -R .config/* ~/.config/
        
    cp .gtkrc-2.0 ~/.gtkrc-2.0
    
    chmod -R +x ~/.config/bspwm/scripts
        
    yay -Syu --needed --noconfirm - < packages-repository.txt
    
    dbus-launch dconf load / < xed.dconf
    
## Get involved at our forum:
https://forum.endeavouros.com/c/desktop-environments/bspwm/75

## Tutorial for bspwm-wm settings:
- Background handled by nitrogen
- Gtk3 theme handled by lxappearance-gtk3
- Filebrowser = Thunar
- Default Terminal-Emulator = Termite
- Text-Editor = xed
- Application Launcher = Rofi


![bspwm](https://raw.githubusercontent.com/EndeavourOS-Community-Editions/bspwm/main/bspwm.png)


## To change icons on polybar

### [GNOME Character Map](https://en.wikipedia.org/wiki/GNOME_Character_Map) 
`gucharmap` is a convenient utility for browsing selected fonts. Filter `View > By Unicode Block + Show only glyphs from this font` and navigate to Private Use Area.
If you find an icon in `gucharmap` but don't know which font it's from, you can hover over it and right click to display the font.

#### reference 

https://github.com/polybar/polybar/wiki/Fonts
