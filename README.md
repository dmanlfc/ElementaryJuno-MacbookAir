# ElementaryJuno-MacbookAir
A set of driver scripts I use to make my Macbook Air 7,2 (2017) run Elementary OS 5.0 (Juno)

## Hardware drivers - macbookairhardware.sh

This script call 3 scripts to assist with:

1. Installing the FaceTime HD web cam (install-camera-elementary5.sh)
2. Install the Broadcom WiFi driver (install-macbookair-wifi-elementary5.sh)
3. Ensure the fan drivers are installed (install-macbookfan-elementary5.sh)

## Software install - installelementary5.sh

This provides a set of installable options which doesn't necessarily depend on the Ubuntu default DEB packages as there are a lot of apps out of date.
The script will grab the latest (at time of writing) packages from various sources.
Although there is more containerisation technologies emerging I tend to still opt for native DEB packages first.

Note: All scripts must be executable & run as sudo
i.e. chmod +x ./<name of sh file>
sudo ./<name of sh file>

Hopefully this is usefull to some people

Dan
