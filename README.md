# OpenCoreBigSur_Microsoft_Surface_Go_3

# Spects:
CPU	Intel® Pentium® Gold 6500Y Dual-core

iGPU	Intel® UHD Graphics 615

RAM	8GB LPDDR3

Storage 128GB SSD

Audio	ALC(298)

Wifi + Bluetooth	Intel® Wifi6 AX2??, Bluetooth 5.0

Card Reader	Realtek PCI-E Card Reader, 152D:1237

Front&Rear Cam	Intel(R) AVStream Camera 2500, ISP Interface, 8086:591c, 8 MPix/5 MPix

Type Cover & Trackpad	Microsoft Type Cover, 045E:096F

Display	10.50 inch 3:2, 1920 x 1280 pixel 220 PPI, 10-Point Capative

Battery	26.81Wh 7.66v 3500mAh

# What do we need?

- USB with a capacity greater than 16gb
- HDD / SSD greater than 35.5gb
- OpenCore Utilities: https://github.com/acidanthera/OpenCorePkg
- Patience and time :)

# Steps:

- Format your USB to FAT32 and copy the files from this repo (EFI folder)

- Go to OpenCore-x.x.x.x-RELEASE \ Utilities \ macrecovery open cmd and paste the following command: 
./macrecovery.py -b Mac-E43C1C25D4880AD6 -m 00000000000000000 -os latest download

- Create a folder in the root of our USB memory called com.apple.recovery.boot and we will copy the following downloaded files
  * BaseSystem.dmg
  * BaseSystem.chunklist

- Finally we will boot from our USB drive, and we will go to the disk utility and format our hdd / ssd to APFS

- When the installation is finished do not panic if it takes a long time to finish or there are reboots, it takes its own time

# BUGS:
- Touchscreen (in this case you had to choose what had to work, whether the touch screen or the trackpad)
- Volume button
- Sensors
- Control of baterry
- Gesture on trackpad
- Camera

# WORKING
- WiFi
- Bluetoth
- AirDrop
- Power botton
- Keyboard
- Type c
- Touchpad
- Slot of micro SD
- Speakers

# I want to thank the guys at OpenCore and the different groups that have helped me carry out the work for the beautiful work :)

Telegram:
- https://t.me/hackintosh_spain
- https://t.me/c/1071950348/180432

Guide used:
- https://dortania.github.io/OpenCore-Install-Guide/

GitHub based repo:
- https://github.com/kingo132/surface-go2-hackintosh

Youtube channel where it is explained step by step
- https://www.youtube.com/watch?v=-GLyfS0eI5g
