# DELL-latitude-7390-hackintosh-monterey

Hi y'all this is my dell latitude 7390 hackintosh monterey build
Based on opencore v0.8.4
pretty much everything works


![Screen Shot 2022-09-08 at 6 15 11 AM](https://user-images.githubusercontent.com/59527864/189131450-9d4b1685-e603-4cbd-970a-06e159bc1c34.png)

# *NOTE*

my laptop is not the  2 in 1 touchscreen version 
although this should work on those models as well 
but the touchscreen might not work because i havent mapped it


# Specs

CPU- Intel(R) Core (TM) 15-8350U CPU @ 1.70GHz
GPU- Intel HD Graphics 620
RAM- 16.00 GB
WIFI-(intel 8265NGW)
Intel Generation- Kaby Lake

# MacOs verison

Model identifier- MacBookPro15,4
version- macOS Monterey Version 12.5.1 (Build 21G83)

# What works-

-touchpad with buttons
-sleep and wake
-iGPU acceleration
-HDMI 
-Ethernet
-power management
-all usb 3.0 ports and 2.0 ports
-keyboard
-wifi (intel 8265NGW)
-bluetooth
-usb c port
-webcam
-mic
-speakers
-headphone jack
-sd card slot

#not working

-Airdrop

# Not tested

-WWAN port
-Thunderbolt port
-iservices (imessege)

# IMPORTANT

CFGlock needs to be unlocked 
CFGlock offset is 0x52D
you have to unlock it manually from modGRUBshell see dortania guide for more details

you have to generate your own smbios details and place them in your config.plist
