## ESP Framework

First attempt to make firmware for my ESP-8226.

### Installation 
Download latest esptool from https://github.com/espressif/esptool

[Download](https://github.com/yuksbg/esp8226-firmware/releases/latest/download/firmware.bin) latest `firmware.bin` from "releases" tab and run

```
esptool.py write_flash 0x0 ./firmware.bin
```

![Sreenshot](.github/shot_2.png?raw=true "Screenshot")
![Sreenshot](.github/shot_3.png?raw=true "Screenshot")