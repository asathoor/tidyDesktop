# Tidy Desktop

Clutter on the Desktop sucks. Here's a one click move all files to the trash bin. 

Note: you may have to change the Dansish Skrivebord to Desktop - or whatever such at thing is called in your language.

## Icons

Add an icon file to `/usr/share/pixmaps`. Let's say that the name is `desktop.png`. Then you can edit the launcher along somewhat like this:

~~~~
[Desktop Entry]
Name=TidyDesktop
Version=1.0
Exec=tidyDesktop
Comment=One click: move all desktop files to trash.
Icon=desktop
Type=Application
Terminal=true
StartupNotify=true
Encoding=UTF-8
Categories=Tools
~~~~
