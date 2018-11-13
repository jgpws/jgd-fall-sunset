# JGD-FallSunset
A dark GTK theme collection with an orange, brown and blue color scheme based on JGD-SpringAwakening.

* [Theme Homepage](https://www.jasong-designs.com/2018/11/11/jgd-fallsunset/)

## How to Install
1. Download the latest file from the [downloads](https://github.com/jgpws/jgd-fall-sunset/tree/master/downloads) directory
2. Open a Terminal application
3. Navigate to your Downloads folder in the terminal (usually titled Downloads). Type `cd Downloads`
4. Type `ls` and look for `jgd-fall-sunset-MM-DD-YY.tar.gz`, where month, day and year represent when the file was last updated
5. Untar the file by typing `tar -zxvf jgd-fall-sunset-01-01-18.tar.gz`, substituting the current version's date numbers
6. type `cd` again to get to your home folder; type `ls -a` and see if there is a **.themes** directory
7. If one does not exist, create one: `mkdir .themes`
8. `cd Downloads`
9. `cp JGD-FallSunset ../.themes`

### To Install JGD-FallSunset Globally
1. Follow steps 1-5 above
2. `cd /usr/share/themes`
3. `sudo cp -r ~/Downloads/JGD-FallSunset /usr/share/themes`
4. Enter sudo password
5. `ls` to check that the theme folder is present

### To Install on Arch Linux:
You can install JGD-FallSunset from the Arch User Repository with Yay:
`yay -S jgd-fall-sunset`

## Theme Switching / Post Install
Once installed, you can use a theme switching application such as **LXAppearance** or **Gnome Tweaks** to change the theme to JGD-FallSunset.

### Metacity ###
Metacity users can switch the theme from the command line:
`gsettings set org.gnome.desktop.wm.preferences theme JGD-FallSunset`

The above setting worked in a Compiz environment in Arch. For other desktop environments, see the article [Gnome Appearance modify command in Linux / How to change theme using command line in GNOME](http://www.pc-freak.net/blog/gnome-appearance-modify-command-in-linux-how-to-change-theme-using-command-line-in-gnome/).

### Openbox ###
Openbox users can change the the theme with the **Openbox Configuration Manager** (obconf). Here are the recommended font selections that work best with this theme, found under the Appearance tab:
* Active window title: DejaVu Serif Bold
* Inactive window title: DejaVu Serif Bold
* Menu header: DejaVu Serif Bold
* Menu item: DejaVu Sans Condensed
* Active On-screen display: DejaVu Sans Condensed
* Inactive On-screen display: DejaVu Sans Condensed

## How to Install the Required Theme Engines ##
JGD-FallSunset requires the Murrine theme engine.

### Ubuntu and derivatives: ###
`sudo apt-get install gtk2-engines-murrine`

### Arch Linux and derivatives: ###
`sudo pacman -S gtk-engine-murrine`

---

Note: The GTK3 version of this theme was tested in version 3.24.
