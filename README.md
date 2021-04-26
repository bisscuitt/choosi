Choose profile for google chrome when clicking a link

Features:
 - Only lists active profiles
 - Popup appears at mouse location to reduce friction


# Install
Install the required files:
```
$ sudo cp choosi /usr/bin
$ sudo cp choosi.desktop /usr/share/applications
$ su

```

# Set as the default browser
In the shell:
```
$ sudo update-alternatives --install /usr/bin/x-www-browser x-www-browser /usr/bin/choosi 500
$ sudo update-alternatives --set x-www-browser /home/bisscuitt/bin/choosi
```

In your Desktop Env:
**KDE**:
* Go to "System Settings > Applications > Default Applications > Web Browser" (or run: $ kcmshell5 componentchooser)
* Set Web Browser to "Choosi Browser"
