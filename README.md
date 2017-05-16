# linuxTheme

This is a guide to make debian looks like macOs. (tested with cinnamon)

1- MODIFY PANEL
  1.1 - Cinnamon comes with the panel on the bottom of the screen by default. Right click on panel, choose 'Panel Settings' and select bottom position. You need to restart to see the effects of this.
  1.2 - Right click on panel - add applet and remove "Panel launchers" and "Window list".
  
2- DOCK
  2.1 - Install Docky
        sudo apt-get install docky
  2.2 - Configure docky to auto startup
  2.3 - Change Docker therme to Glass or Air. Alternative there is this theme (https://www.gnome-look.org/content/show.php/Finery+Docky+Theme?content=124808)
  2.4 - Start app you want to docker, right click on it and "pin to doc".
  2.5 - Alternative to Docky there is Plank (apt-get install plank)
  
  
3- CHANGE CINNAMON THEME
  3.1 - Download macOs Sierra theme from https://github.com/B00merang-Project/macOS-Sierra and extract.
  3.2 - From terminal: mkdir $HOME/.themes
  3.3 - Copy extracted theme folder to $HOME/.themes
  3.4 - Go to System Settings - Themes and you'll find macOs Sierra-master on the list.
  3.5 - Right click on macOs Sierra theme and "apply this theme"
  3.6 - Go to System Settings - Themes - Other settings -> Select macOs Sierra-master in control and window borders.
  
  ICON
  
  Icon can be download from “Vivacious-NonMono-Light-Blue” or from https://github.com/ActusOS/GnomeYosemiteIcons. Alternative use default elementaryXbuntu.
  
  3.7 - Go to System Settings - Themes - Other settings - icon -> Select elementaryXbuntu-dark.
  

Thanks to:
http://www.makeuseof.com/tag/make-linux-look-like-macos/
