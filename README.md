# Call Recorder - SKVALEX
Call recording app to record both sides from the line with a power of root and magisk.

This module allows the app ([Call Recorder - SKVALEX](https://callrecorder.skvalex.com/get)) to use advanced root features, such as:
- Record both sides (including Android 9 Pie and Android 10)
- Start recording when a call get actually answered

If you already have installed the main app, install this module to get advanced features. If not, this module will install the app for you.

## How to use it
After successful installation of this module, a star `★` will be shown prior audio source name selected in `Settings` → `Recording` → `Standard API`.

It's recommended to use Standard API recording method with `★ Voice call uplink + downlink` audio source. In case it doesn't work for you as expected, try luck with other audio sources.

## Notes
- In most cases [the app](https://callrecorder.skvalex.com/get) will work fine by just providing root access. So you may install app first and if you can see a star prior audio source name in `Settings` → `Recording` → `Standard API`, then Magisk module will not make any difference
- On Xiaomi devices you should allow auto-start before installing this module, otherwise you won't find this option. If you already installed this module, then uninstall it to allow auto-start
- The module makes the app system, so it might also help to get the app not killed by the system. But as the practice shows the most important thing is to allow auto-start/auto-launch and lock the app in recents. Please read [best practices](https://skvalex.org/help/best-practices) page and [dontkillmyapp.com](https://dontkillmyapp.com) for more specific advices

## Links
Download the app: https://callrecorder.skvalex.com/get

Support threads:
* XDA: https://forum.xda-developers.com/showthread.php?t=1441643

* 4pda.ru (in russian): https://4pda.ru/forum/index.php?showtopic=263718

Terms of Use and Privacy Policy: https://skvalex.org/terms

## Changelog
### v.2.1.1 (3.5.0)
* support Magisk 24 update mechanism

### v.2.1.0 (3.4.7)
* main app is system again

### v.2.1.0 (3.4.5)
* main app is not system anymore as it brings more problems than benefits: it's still being killed by battery optimizers and some ROMs don't allow to install apk updates

### v.2.1.0 (3.2.5)
* main app is now system: might help to not being killed by the system  

## Changelog for Add-on
### v.2.1.0
* updated magisk module format
* moved the code for the ROOT method to the main app, so it's removed from the add-on
* removed self-update mechanism from add-on as the main app can now have it itself

### v.2.0.8
* improved ability to detect answer on outgoing calls
* fixed bug with recording on Android 9

### v.2.0.7
* recording issue fixed on Samsung devices

### v.2.0.6
* fixed crash for pre-Pie devices

### v.2.0.5
* created Magisk module
