## Installing Ubuntu with Crouton
Crouton is an addon to ChromeOS which adds the ability to run code roots (Chroots) inside of Chrome, only requiring developer mode. This is the safest bet by far - It does not permanently change anything on the device, and the device can be powerwashed with no trace of crouton at all. This method takes about 30 - 60 mins, so you will have to have some time on your hands. There are different types of chroots, and you can even mess around and make your own! 

These are the steps for downloading Ubuntu 16.04 LTS with Crouton:
 1. Download [Crouton](https://goo.gl/fd3zc)
 2. Open a shell (`Ctrl + Alt + T` and type `shell`) in chrome and type `sudo install -Dt /usr/local/bin -m 755 ~/Downloads/crouton`
 3. Type `sudo crouton -t unity`
 4. Wait for it to download
 5. Type `sudo startunity`

To switch between the chroot and Chrome, press `ctrl + alt + shift + F1` (<-- button at the top), and to go back to Ubuntu, press `ctrl + alt + shift + F1` (--> button at the top).

If you want to have a different Ubuntu distribution, then change the -t parameter to one of the following: unity-desktop, xfce, xfce-desktop, lxde, lxde-desktop, gnome, gnome-desktop, kde and kde-desktop. If you want to know what these look like, search it up on google.

If you want a newer version, they do work but they require some more steps. The most-supported version is 18.04, Bionic beaver, which to get it at the "sudo crouton -t unity" type "sudo crouton -r bionic -t audio,cli-extra,x11,extension,keyboard,xorg,lxde -u" and the process should take 50 - 90 mins so you need some free time.

There are other linux distros available, like Debian and Kali, and to get it all you need to do is say is when you are about to download, instead of the standard command line, say `sudo crouton -t xfce -r bookworm` for debian, and for kali say `sudo crouton -t xfce -r kali-rolling`. Other supported debian releases are (From old to new) buster, bullseye, bookworm and sid and there are no other kali releases.
