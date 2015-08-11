# PiGPS netinstall

Raspbian provides a [netinstall image](https://github.com/debian-pi/raspbian-ua-netinst) which can be customized.
This repository contains our customizations. In the future we may provide full netinstall images.

# Customizations

* At the time this repository was created, the default image installed Raspbian Wheezy. This configuration will install Raspbian Jessie.

As this image is developed further, it should also install all required packages for PiGPS.

# Instructions

* Extract the original netinstall image on your SD card by following the Raspbian instructions.
* Then copy ```installer-config.txt``` and ```post-install.txt``` from this repository to the SD card's ```/boot/``` directory.
* Make sure the Raspberry Pi is connected to your network (requires DHCP or further customization).
* Boot. Installation may take a while, feel free to watch via HDMI.
