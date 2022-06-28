# Canbus-Guide
Welcome to my little guide to setting up Canbus on your Voron!  This is based around the 3D Mellow FLY-SHTXX series and 3D Mellow UtoC Series.
I bought mine from:
https://mellow.aliexpress.com/store/1531088?spm=a2g0o.productlist.0.0.4b4b5fae0JTZrN

Putting the FLY-SHTXX into DFU Boot mode:
Install a jumper (included) to short the 3.3v and Boot pins on the Toolhead Board
<Insert Image 1>
<Insert Image 2>
Connect your Toolhead Board to your Raspberry Pi Via a USB A to USB C cable.  Please note that not all cables are wired the same, some are only wired for power, some power and data.  Get a good quality one, and thank yourself for it later.  I like to use a 1-2m cable so I can do this with the Toolhead Board already mounted on the Toolhead.  Others prefer to do it on the desktop, its your call.
Follow MazOrs Canboot Guide https://github.com/maz0r/klipper_canbus/blob/main/controller/canboot.md

