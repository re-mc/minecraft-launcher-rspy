# minecraft-launcher-rspy
Minecraft launcher written in rust and python

Each release has 3 files, minecraft-installer.exe, minecraft-launcher.exe, and minecraft-launcher-console.exe
It is recommended to use minecraft-installer.exe, it should work on any windows machine with chrome installed.
Both minecraft-launcher.exe and minecraft-launcher-console.exe are smaller files, but require you to have python 3.11 installed.
minecraft-installer.exe bundles python with it, and lets you choose the install path, and which version to install (console shown / console hidden)

As of v1.0.0, after install has finished, the launcher will be in bin/python-3.11.7-mc/
the default instance is located in bin/python-3.11.7-mc/.minecraft

Make sure to set the minecraft loader (beside the 'Create Instance' button) when creating an instance!

If you want to sign in to your minecraft account, or choose a different username, click on 'Set Account'.

!You Need Chrome (or firefox) For The Launcher To Work!

## Known bugs
* After instances reload, they will no longer do anything when clicked, you have to restart the launcher.
* Windows will not automatically close, you must close them yourself after you have finished using them.
* You need to have either chrome (or chromium) or firefox installed for it to load, I would bundle nwjs with the launcher, but it has issues.
* You also need to have internet when openning the launcher, after it has opened, you don't need internet.
* Two windows quickly popup and dissapear when using the hidden console version, there's not really much I can do about that.
