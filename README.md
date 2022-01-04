# BLIKVM-Notes
Notes for the BLIKVM which is based upon PiKVM but using a Raspberry Pi Compute Module 4

<img src="https://user-images.githubusercontent.com/12605257/148127711-fbdd234d-ae97-4118-88fc-e55455b4c62e.jpg" alt="BLIKVM Picture" width="400"/>


I purchased the BLIKVM IO Board from:
https://www.aliexpress.com/item/1005003262886521.html

I purchased a Raspberry Pi Compute Module 4 from a local Australian Reseller.
The model I chose will work with a Raspberry Pi Compute Module 4 Lite. This is the module with no EMMC Memory and 2gb RAM

I used a 32GB U1 MicroSD Card and downloaded the Raspberry Pi 4, v3 HAT platform image from here:

https://pikvm.org/download/

https://files.pikvm.org/images/v3-hdmi-rpi4-latest.img.xz

To get the OLED Screen to work, I had to log in to the terminal and issue the commands:

```
su
rw
systemctl enable --now kvmd-oled
ro
```

