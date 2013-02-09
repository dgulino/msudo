I develop a lot on OSX and there are times I need to run a GUI app as root, like a gui editor of a systems file, or running Wireshark. I could just run it from a terminal using "sudo", but that's not very cool. There is the Pseudo app, which is quite cool, and only $15, but I figured it wouldn't be too hard to script something together. Well, Many Hours Later, I've got something! An AppleScript droplet that can be added to your dock and when you drag another App on it, a GUI popup will ask for your password, and voila!  You have a GUI app running as root.

The full application bin is at bin/MSudo.app

To make it yourself:

Open Applications..Utilities..AppleScriptEditor, paste the text from src/msudo.script, and then save it as MSudo.app, as an Application.  Then drag it onto your Dock

You can add a nice icon for this: http://stackoverflow.com/questions/8371790/how-to-set-icon-on-file-or-directory-using-cli-on-os-x
The icon is at resources/superman-icon.png (
http://icons.iconarchive.com/icons/iconshock/super-heros/128/superman-icon.png)
