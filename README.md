# BSPWM Setup and Theme for EndeavourOS
**BSPWM EndeavorOS Community Edition**

<!-- <img src="https://user-images.githubusercontent.com/83577193/151338147-81198c76-1e74-4dea-84a3-063717ef6ce3.png" alt="bspwm" style="width:200%;"/>
 -->
 
 ![image](https://user-images.githubusercontent.com/83577193/151557941-c7a88bc2-9e47-4a93-9b9e-d7e72cea26ae.png)

<!-- Code that was here by default  -->

<!-- ## To Install manually

    git clone https://github.com/EndeavourOS-Community-Editions/bspwm.git
    cd bspwm
    bash bspwm-install.sh
   
## Contained In The Script
    cp -R .config/* ~/.config/
        
    cp .gtkrc-2.0 ~/.gtkrc-2.0
    
    chmod -R +x ~/.config/bspwm/scripts
        
    yay -Syu --needed --noconfirm - < packages-repository.txt
    
    dbus-launch dconf load / < xed.dconf -->
    
<!--  Code that was here by default  ends -->

 Install Endevour os bspwm edition then 
 
    git clone https://github.com/adithya-r-prabhu/bspwm.git

    cd bspwm

    bash setup.sh
  
 
## Get involved at our forum:
https://forum.endeavouros.com/c/desktop-environments/bspwm/75

## Fonts used 
Inter-Regular
IosevkaTermNerdFontComplete

## To change icons on polybar

### [GNOME Character Map](https://en.wikipedia.org/wiki/GNOME_Character_Map) 
`gucharmap` is a convenient utility for browsing selected fonts. Filter `View > By Unicode Block + Show only glyphs from this font` and navigate to Private Use Area.
If you find an icon in `gucharmap` but don't know which font it's from, you can hover over it and right click to display the font.

#### reference 

https://github.com/polybar/polybar/wiki/Fonts


## Hardlink files to the git folder to push
```
cp -r -l /home/$USER/.config/bspwm /home/$USER/Documents/GitHub/bspwm/.config/
cp -r -l /home/$USER/.config/dunst /home/$USER/Documents/GitHub/bspwm/.config
cp -r -l /home/$USER/.config/gtk-3.0  /home/$USER/Documents/GitHub/bspwm/.config/
cp -r -l /home/$USER/.config/nitrogen  /home/$USER/Documents/GitHub/bspwm/.config/
cp -r -l /home/$USER/.config/polybar  /home/$USER/Documents/GitHub/bspwm/.config/
cp -r -l /home/$USER/.config/rofi  /home/$USER/Documents/GitHub/bspwm/.config/
cp -r -l /home/$USER/.config/sxhkd  /home/$USER/Documents/GitHub/bspwm/.config/
cp -r -l /home/$USER/.config/termite  /home/$USER/Documents/GitHub/bspwm/.config/
cp -r -l /home/$USER/.config/xfce4  /home/$USER/Documents/GitHub/bspwm/.config/
cp -r -l /home/$USER/.config/picom.conf /home/$USER/Documents/GitHub/bspwm/.config/
```

## sxhkd-helper-menu

https://github.com/fiskhest/sxhkd-helper-menu

## Fix X shaped cursor bspwm
Install xsetroot
```Fix X shaped cursor bspwm```

Run the command to change to normal mouse cursor

```xsetroot -cursor_name left_ptr```

#### References
https://www.reddit.com/r/bspwm/comments/8gwwlc/cursor_displays_x_when_not_over_window/

https://www.reddit.com/r/bspwm/comments/fb5z6j/is_it_possible_to_bind_shell_aliases_with_sxhkd/

## Right click Context menu not working
Run
```
xprop
```
and click on terminal

#### Reference 
https://github.com/baskerville/bspwm/issues/232
