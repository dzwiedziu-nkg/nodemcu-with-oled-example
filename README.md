# HW-364A OLED Display example

I bought a nice dev board with ESP8266 and OLED Display and I spend a lot of hours getting it to work because the sellers haven't published any documentation or sample codes. In addition, the I2C pins were signed incorrectly.

But it worked, so I'm posting a working example :)

Environment: Visual Studio Code with PlatormIO

My board: HW-364A v2.1.0 with MicroUSB
* NodeMCU ESP8266 Development Board
* 0.96 Inch OLED Display 128x64 pixels
* CH340 Driver Module

The display was connected as:
* I2C on D5/D6 pins (GPIO14/GPIO12) as SDA/SCL
* Address: 0x3C

Tested on board bought in: https://www.aliexpress.com/item/1005006011203112.html (MicroUSB version)

If I helped you and saved you a few hours, please buy me a coffee :)
https://www.paypal.com/paypalme/nkgmn/10
