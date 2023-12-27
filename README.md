# VAURA

![VAURA](https://pub-e3247d7e22b447139019854186942a65.r2.dev/0xn1-dev/LAB/vaura/vaura-1.png)

An audio reactive application made using Quartz Composer and ported as app in Xcode.

## Features

- Dual mode, V1 and V2
- OSC support
- Comes with controller app (VAURACtrl) to control visual through OSC

## Controls

- CMD + F = Fullscreen
- CMD + I = Intensity Multiplier

## OSC connection

```
IP : Your Machine IP, refer Network Preferences
Port Number : 7477

/vaura/saturation
saturation (float value = 0.0 - 1.0)

/vaura/color
change color (float value = 0.0 - 1.0)

/vaura/v2/effect1
change effect for V2 (float value = 0.0 - 1.0)

/vaura/info
toggle info on/off (value = 0,1)

/vaura/version
switch between V1 and V2 (value = 0,1)
```

## Download

Check the releases page

## Installing

Due to this application was developed in older macOS version. It might not work first time around. Just make sure you right click and press open.

## Thanks

Great thanks to

- Assoc. Prof. Dr Wong (Media Art Coordinator, MMU Cyberjaya)
- Benoit Lahoz (Xcode QC)
- Quartz Composer Community
