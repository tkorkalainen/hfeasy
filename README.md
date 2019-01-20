# hfeasy
HF-LPx100 firmware for Ankuoo devices

If you like this project please [donate](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=5SMU6YE5XG6JG&source=url)!

# Implemented Features:
* MQTT client
* HTTP config, control and status webpages

After flashing hfeasy, you'll have access to the following web pages:
* Config:
  * http://\<deviceip\>/config
* Status:
  * http://\<deviceip\>/status
* Control:
  * status: http://\<deviceip\>/state
  * on: http://\<deviceip\>/state?sw=1
  * off: http://\<deviceip\>/state?sw=0

# Supported devices (so far...)
* Wifi Plug (http://www.lumitek.cn/en/productsd.php?pid=1095)
![Wifi Plug](http://www.lumitekgroup.com/upload/2015062911265369.jpg)

* Wifi Module (http://www.lumitek.cn/en/productsd.php?pid=1093)
![Wifi Module](http://www.lumitekgroup.com/upload/2015062315503112.jpg)


# Firmware
* [Plug](https://drive.google.com/open?id=1eRtJjA7Dd28m64O0pGRHo6_lasVvcpur)
* [Module](https://drive.google.com/open?id=1KVt4QvOLIY-WCWgONfWG1eNCMGK019AO)

In case you want to go back, the latest official firmware is here:
* [Plug](http://lumitek.yunext.com/files/DF_1_5114.bin)
* [Module](http://lumitek.yunext.com/files/D1_1_V1.5116.bin)


# Device info
All devices have a firmware flash webpage at: http://\<deviceip\>/iweb.html

This webpage allows to configure the device wifi parameters and flash new firmware.
No matter which firmware you flash, this webpage is always there (make the device almost "unbrickable").

There is another webpage at: http://\<deviceip\>/

In here you can setup the wifi parameters, change the access user/pass and flash new firmware too.
The access to there webpages is password protected.
The user/pass defaults to admin/admin.
If you upgrade to the latest official firmware, the user/pass is changed to admin/Lumlink@100

# TODO
* Add timers/countdowns (configurable by webpage)
* Add mqtt authentication
* ... and suggestions are welcome (open an issue)