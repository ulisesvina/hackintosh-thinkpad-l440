# Hackintosh on the Thinkpad L440 and T440p

![](https://raw.githubusercontent.com/ulisesvina/hackintosh-thinkpad-l440/main/Captura%20de%20Pantalla%202022-02-22%20a%20la(s)%202.47.33%20p.m..png)

**NOTE:** Hackintosh-ing is a process that's against the Apple® macOS™ End-User License Agreement (EULA). I am not responsable for any legal problems you may or may not be involved in for installing macOS™ on non-Apple hardware, as I'm not providing the media for installing macOS™, but rather, open-source software that can be used for the purpose of Hackintoshing, which is not against to the EULA for it's own.</br>

## What works (as of now, feb. 22, 2022):
- Bluetooth (1)
- Wi-Fi (2)
- Graphics acceleration
- Trackpad and gestures
- SD card reader
- Battery management
- Continuity (3)

Notes:</br>
1. Bluetooth on this installation does not have the common issue across other EFIs, which is weak signal.
2. Wi-Fi works out-of-the-box with the AirPort™ utility and native Wi-Fi menu.
3. Not all Continuity features work. AirDrop™ is known to not work with Intel® Wi-Fi cards, Handoff™ does not work as of now, but it will be fixed.

## What DOES NOT work:
- TouchID™ (fingerprint scanner) (1)
- AirDrop™ (2)
- Microphone and speaker (3)
- TrackPoint (3)

Notes:</br>
1. TouchID **will NEVER work**, because non-Apple computers does not have the Apple® T2 chip, responsable for security in the Mac™ devices.
2. AirDrop **will NEVER work** with the integrated Intel® Wi-Fi card, you can buy a Broadcom® Wi-Fi card (here: https://es.aliexpress.com/item/32464748097.html), with that, all the Continuity features will work.
3. This are known issues that are to be fixed soon.
