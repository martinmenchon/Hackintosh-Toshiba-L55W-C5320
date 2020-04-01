# Hackintosh-Toshiba-L55W-C5320

## Notebook Specs:
<img src="images/image.png" width="200">

Processor: 2,39 GHz Dual-Core Intel Core i7 5500u

Memory: 12 GB 1600 MHz DDR3

Graphics: Intel HD Graphics 5500 1536 MB


## Perfectly Working Features:

- [x] Audio
- [x] Microphone
- [x] Integrated Intel Graphics (hd 5500)
- [x] Multitouch gestures
- [x] Full keyboard working (Using "US-International PC" input sources)
- [x] Keyboard backight control
- [x] Volumen Keyboards
- [x] Num keys
- [x] USB 3.0
- [x] Web camera
- [x] Wifi and Bluetooth using this card and adaptor (Sodial Bcm94360Cs2 - Adaptator BCM94360CS2 BCM943224PCIEBT2 A M2 (M.2 NGFF) A E Key)
- [x] Sleep with DSDT Patches
- [x] Battery Percentage
- [x] Siri
- [x] AirDrop
- [X] Night Shift


## Not Working:

    Card reader (I don't use it, so I didn't try to fix it)
    HDMI audio (I will try to fix it in the next days)
    IMessage and FaceTime (I will try to fix it in the next days)
    
## Kexts:

- AppleALC
- VoodooPS2Controller
-  ACPIBatteryManager.kext
-  FakeSMC.kext
-  WhateverGreen.kext
-  Lilu.kext
-  USBPorts.kext

## EFI:
[EFI](EFI.zip)

![Display](images/Screen_Shot.png)

## Sleep Configurations

It's important to disable "Wake for Wi-Fi network access to avoid wifi problems"
<img src="images/energy1.png">
<img src="images/energy2.png">

It's important to disable "Allow Bluetooth devices to wake this computer"
<img src="images/energy3.png">

## Keyboard 
<img src="images/keyboard.png">

## Gallery
<img src="https://ae01.alicdn.com/kf/Udeb369199cb14cf492d7283287dda7d0q.jpg" width='150'>
<img src="https://ae01.alicdn.com/kf/U2684e4e6b2fe4fd1b88d39f3a8e919f8B.jpg" width='150'>

<img src="images/memory.png">
<img src="images/usb.png">
<img src="images/graphics.png">

## Credits

- [Acidanthera](https://github.com/acidanthera)
  - [AppleALC](https://github.com/acidanthera/AppleALC)
  - [Lilu](https://github.com/acidanthera/Lilu)
  - [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
  - [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [RehabMan](https://github.com/RehabMan)
- [VoodooI2C Developer Team](https://voodooi2c.github.io/#Credits%20and%20Acknowledgments/Credits%20and%20Acknowledgments)
