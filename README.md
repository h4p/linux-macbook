# linux-macbook

I've installed [Linux Mint Cinnamon Edition](https://linuxmint.com/download.php) on my system.


## Keyboard
To use the same mac keybindings (⌘+C for copying, ⌘+V for pasting, ⌘+L to jump in the adress bar, ..) you can use the program [kinto](https://github.com/rbreaves/kinto). It runs in the system tray and works without configuration splenditly. 

## Touchpad
To use multi-touch gestures on your touchpad I have installed [touchegg](https://github.com/rbreaves/kinto)


## MS Teams
MS Teams was installed from the graphical Software Center `mintinstall`

## MS Outlook 365
Outlook itself is not available for Linux but [prospect-mail] works great. It feels like the program is showing an iFrame of the actual Outlook Web-App, but is very responsive.

I had to activate `snap` in order to install this mail client

    $ sudo rm /etc/apt/preferences.d/nosnap.pref
    $ sudo apt update
    $ sudo apt install snapd
    $ sudo snap install prospect-mail
