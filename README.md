# 🔎 Dotfiles
My dotfiles :)  
These are my dotfiles on [Arch Linux](https://archlinux.org/). I did this by reading the official documentation, taking examples from other dotfiles and modifying them to my personal taste. Mainly based on the theme Isabel by [gh0stzk](https://github.com/gh0stzk/dotfiles).
# 🖼️ Gallery 
 <img src="https://github.com/Urlesst/dotfiles/blob/master/assets/home.png" alt="Rice" title="Home" width="75%" height="75%"> <img src="https://github.com/Urlesst/dotfiles/blob/master/assets/cava.png" alt="Rice" title="cava" width="75%" height="75%"> <img src="https://github.com/Urlesst/dotfiles/blob/master/assets/rice.png" alt="Rice" title="rice" width="75%" height="75%"> <img src="https://github.com/Urlesst/dotfiles/blob/master/assets/normal.png" alt="Rice" title="Normal" width="75%" height="75%">
# 📚 Dependencies 
• [BSPWM](https://wiki.archlinux.org/title/Bspwm). Used as windows manager.  
• [Polybar](https://polybar.github.io/). Bar  
• [Sxhkd](https://wiki.archlinux.org/title/Sxhkd). X hotkey daemon.  
• [Dunst](https://dunst-project.org/). Notifications.  
• [Rofi](https://wiki.archlinux.org/title/Rofi). Menu.  
• [NetworkManager_dmenu](https://github.com/firecat53/networkmanager-dmenu). Network Menu.  
• [Termite](https://wiki.archlinux.org/title/Termite). Terminal emulator.  
• [Checkupdates](https://aur.archlinux.org/packages/checkupdates+aur). Updates.  
• [Playerctl](https://github.com/altdesktop/playerctl). Control media players.  
• [Picom](https://wiki.archlinux.org/title/Picom). Compositor.      
• [Xfce4-screenshooter](https://archlinux.org/packages/extra/x86_64/xfce4-screenshooter/), [Xfce4-settings](https://archlinux.org/packages/extra/x86_64/xfce4-settings/) and [Thunar](https://wiki.archlinux.org/title/Thunar). Xfce used.  
• [Betterlockscreen](https://github.com/betterlockscreen/betterlockscreen). Screen locker.  
• [Fish](https://fishshell.com/). Shell
• [Pavucontrol](https://archlinux.org/packages/extra/x86_64/pavucontrol/). Audio control.  
• [Waterfox](https://aur.archlinux.org/packages/waterfox-g5-bin). Open source browser based on Firefox.  
• [Spotify](https://aur.archlinux.org/packages/spotify). Songs 🎵.  
• [Feh](https://wiki.archlinux.org/title/Feh). Set wallpaper.
# 💿 Installation 
First install the dependencies. You can make use of the Arch package manager to install them. However, note that some dependencies are not in the additional repositories, but in the [AUR](https://aur.archlinux.org/)(Arch User Repository). You can clone via git and use the [makepkg](https://wiki.archlinux.org/title/Makepkg) script to install those not found in the official repositories. That would be one way, and the other is the one I recommend. Use an [AUR helper](https://wiki.archlinux.org/title/AUR_helpers) since these install packages obtained in the official repositories and also from the AUR if they are not in the first mentioned ones. In this case you can use [yay](https://aur.archlinux.org/packages/yay). To install this AUR helper you just need to have git installed and use the makepkg script.  
```  
git clone https://aur.archlinux.org/yay.git  
cd yay  
makepkg -si  
```  
Once yay is installed you can proceed to install the dependencies.  
```
yay -S bspwm polybar sxhkd dunst rofi networkmanager-dmenu-git termite checkupdates+aur playerctl picom xfce4-screenshooter xfce4-settings betterlockscreen fish pavucontrol waterfox spotify feh  
```
With the dependencies ready, you should clone this repository.
``` 
git clone https://github.com/Urlesst/dotfiles
```

