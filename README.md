# BLIKVM-Notes
Notes for the BLIKVM which is based upon PiKVM but using a Rpi CM4

Purchased IO Board from:
https://www.aliexpress.com/item/1005003262886521.html

Device works with a Raspberry Pi Compute Module 4 Lite. This is the module with no EMMC Memory and 2gb RAM

I downloaded the Raspberry Pi 4, v3 HAT platform image from here:

https://pikvm.org/download/

https://files.pikvm.org/images/v3-hdmi-rpi4-latest.img.xz

To get the OLED Screen to work, I had to log in to the terminal and issue the commands:
```
su
rw
systemctl enable --now kvmd-oled
ro
```
