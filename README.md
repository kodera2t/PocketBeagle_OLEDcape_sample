# PocketBeagle_OLEDcape_sample
Sample program for OLED display on PocketBeagle Cape

This program is a modified version of the original
https://github.com/deeplyembeddedWP/SSD1306-OLED-display-driver-for-BeagleBone

I2C bus connection and SSD1306 display connection are tailored to my PocketBeagle Cape

This repository contains compiled binary "oled" but also we can compile on PocketBeagle by
```
cc I2C.c SSD1306_OLED.c example_app.c Main.c -o oled2
```

