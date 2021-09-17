## ESP Framework

First attempt to make firmware for my ESP-8226.

### Installation 
Download latest esptool from https://github.com/espressif/esptool

Download latest `firmware.bin` from "releases" tab and run 

```
esptool.py write_flash 0x0 ./firmware.bin
```
