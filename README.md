# Hotspot-Tools by KM4ACK
Some modifications/customizations by WB0SIO

# Description

A collection of tools to manage the hotspot on the raspberry pi.
The original km4ack version of the hotspot can be installed [from here](https://youtu.be/qMT-0mz1lkI)
or by using the [Build-a-Pi](https://github.com/km4ack/pi-build) script.

My version with the user supplied hotspot IP address:

Autohotspot - https://github.com/lcgreenwald/autohotspot.git

Build-a-pi - https://github.com/lcgreenwald/pi-build-2.git

# Install

     git clone https://github.com/lcgreenwald/autohotspot-tools.git $HOME/hotspot-tools 

     cd ~/hotspot-tools

     bash setup        # Use this for a pi running a desktop version of the OS.
     
     bash setup-lite   # Use this for a pi running the lite version of the OS.

# Tools in Script

1 - Change SSID name and/or password for the hotspot 

2 - Run hotspot script to check for known SSID’s in range

3 - Disable the hotspot. This will make it like the hotspot feature doesn’t exist on the pi. This is something that quite a few people have asked for.

4 - Enable hotspot that has been disabled using #3

5 - Change the IP of hotspot & pi DHCP server (Experimental). wb0sio - Modified to update the entire IP address instead of just the first half.

6 - Manage SSID's. Add/Remove SSID's from the system. Helpful when in hotspot mode and no previously known SSID’s are in range.

7 - List Known SSID’s already in the pi.

8 - List DHCP leases currently assigned by the raspberry pi hotspot and optionally, delete them.

9 - Update the hotspot tools app

