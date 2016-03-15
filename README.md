VirtualDesktopManager
======
About
------------------------
This program was made for people who are using Windows 10's built-in Virtual Desktops, but who don't like the default key-binding, don't like how you can't cycle through your desktops (If you are on your last one you don't want to hotkey over to the first one 8 times), and don't like not knowing what desktop # they are on.

Install
------------------------
There is no installation. Just download the .zip from the Releases, extract it and then run VirtualDesktopManager.exe.

You can use Task Scheduler to make it launch when you login so you don't have to launch it manually every reboot.

Usage
------------------------

You can continue to use the default hotkey to change desktops (Ctrl+Win+Right/Left), but you won't get any of the benefit of the program except knowing which desktop you are on. 

I have added a listener to the hotkey of Ctrl+Alt+Right/Left. With this hotkey, you can cycle through your virtual desktops.


Limitations
------------------------
 * Due to not wanting to make lots of tray icons, this program only supports up to 9 virtual desktops (it will crash if you go above that).
 * It needs more testing to see how well it will handle suspend/hibernation events.
 * You will need to relaunch the program if explorer.exe crashes.
 * Hotkeys are statically coded in, so if you want to configure them, you'll have to modify the source.
 * It doesn't handle it very well when you add or create virtual desktops while it's running. You'll need to relaunch it.

I'm trying to work on these issues, but if you have a solution, just throw in a PR and I'll take a look.