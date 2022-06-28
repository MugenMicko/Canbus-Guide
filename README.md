# Canbus-Guide  (This is not finished yet, please do not used until complete!!)
Welcome to my little guide to setting up Canbus on your Voron!  This is based around the 3D Mellow FLY-SHTXX series and 3D Mellow UtoC Series.  
I bought mine from:  
https://mellow.aliexpress.com/store/1531088?spm=a2g0o.productlist.0.0.4b4b5fae0JTZrN  
  
Putting the FLY-SHTXX into DFU Boot mode:  
Install a jumper (included) to short the 3.3v and Boot pins on the Toolhead Board  
<Insert Image 1>  
<Insert Image 2>  
Connect your Toolhead Board to your Raspberry Pi Via a USB A to USB C cable.  Please note that not all cables are wired the same, some are only wired for power, some power and data.  Get a good quality one, and thank yourself for it later.  I like to use a 1-2m cable so I can do this with the Toolhead Board already mounted on the Toolhead.  Others prefer to do it on the desktop, its your call.  
  
Follow MazOrs Canboot Guide https://github.com/maz0r/klipper_canbus/blob/main/controller/canboot.md  
  
Next, Setup your Pi, Follow MazOrs Canable and Clones Pi Setup:  
https://github.com/maz0r/klipper_canbus/blob/main/controller/canable.md  

Next, Hook up your CANBus cables, if you cant buy a premade one, twist a pair of Red and Black 2AWG PTFE of FEP coated wires using a drill, repeat with another pair of different coloured wires, terminate them with the correct pins for your connectors, sheath them, put the pins in your connectors and plug it in :)  
  
Yay! We can now compile and flash our Klipper Firmware to the FLY-SHT36 via CANbus!!!  
Follow the instructions for Compiling Klipper firmware from:  
https://mellow.klipper.cn/#/advanced/canboot?id=%e7%83%a7%e5%bd%95canboot%e5%bc%95%e5%af%bc%e5%9b%ba%e4%bb%b6  
More to come..  
