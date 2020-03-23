# Hotspot-Tools by KM4ACK

# Description

A collection of tools to manage the hotspot on the raspberry pi.
The hotspot can be installed [from here](https://youtu.be/qMT-0mz1lkI)
or by using the [Build-a-Pi](https://github.com/km4ack/pi-build) script.

# Install

     git clone https://github.com/km4ack/hotspot-tools.git $HOME/hotspot-tools 

     cd ~/hotspot-tools

     git checkout dev

     bash setup

# Tools in Script

1 - Change SSID name and/or password for the hotspot 

2 - Run hotspot script to check for known SSID’s in range

3 - Disable the hotspot. This will make it like the hotspot feature doesn’t exist on the pi. This is something that quite a few people have asked for.

4 - Enable hotspot that has been disabled using #3

5 - Change the IP of hotspot & pi DHCP server (Experimental)

6 - Manage SSID's. Add/Remove SSID's from the system. Helpful when in hotspot mode and no previously known SSID’s are in range.

7 - List Known SSID’s already in the pi.

8 - Update the hotspot tools app

