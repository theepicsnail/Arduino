Arduino touch screen project

Install
---
```bash
git clone git@github.com:theepicsnail/Arduino.git sketchbook
cd sketchbook
git submodule update --init

# Enable the USE_ADAFRUIT_SHIELD_PINOUT
sed -i "s_//#_#_" libraries/TFTLCD/Adafruit_TFTLCD.h
# Or you can just uncomment that line manually.
```
