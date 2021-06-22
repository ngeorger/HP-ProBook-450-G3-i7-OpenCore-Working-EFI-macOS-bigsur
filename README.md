# HP ProBook 450 G3 i7 OpenCore Working EFI macOS bigsur

HP ProBook 450 G3 Core i7 - OpenCore macOS BigSur 11.4 working EFI

This is my very first and amateu config for OpenCore 0.7 which is actually working and functional, at least as a minimum for being usable and stable with bigsur 11.4, except for:
- Native wireless adapter and bluetooth (Broadcom is a pain in the ass, even in Linux)
- Figerprint reader (Really is somebody using this feature on this machine?)
- SD Card reader (I almost never use it, so I haven't gave even a chance)

What's added, in order to compensate the lack of wireless:
- Fully working HoRNDIS.kext in order to support any USB tethering with android devides
- And... I don't remember what else.

I've used many other eople's work (obviously), mostly all what you can find when you search "bigsur opencore efi probook g3 i7" here on github, I promise I'll add the sources and mentions ASAP, my idea is to provide this working solution for whoever needs it and don't have the time to do the research.

NOTICE: The config might be buggy, every feedback is appreciated.

All the credits goes to the creators of OpenCore, the sourced kexts, they're the brilliant people, I'm just a guy who made a config.

Screenshots:
![Screenshot 2021-06-21 at 20.41.34](/assets/Screenshot%202021-06-21%20at%2020.41.34.png)

![Screenshot 2021-06-21 at 20.41.34](/assets/Screenshot%202021-06-21%20at%2020.42.05.png)

Detalied info of my computer report under macos:

MacBook Pro HP g3 i7.spx
