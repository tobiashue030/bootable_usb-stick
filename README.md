# bootable_usb-stick
The plan is to delete the OS of a used laptop and install a new one via a bootable USB-stick. After that I want to set up a NAS, DHCP-, DNS- and web-server.
I will make notes from every step taken. Considering creating a network map.

Ventoy Stick created with Ubuntu and Windows 11.

Data safed from old notebook - password wasnt known, so I had to use a temporary OS via ventoy usb stick to get access.

Wiped the notebook via installing a new OS (Ubuntu).

Figuring out if the specs are good enough for project via installing inix on ubuntu device:
sudo apt update
sudo apt install inxi

trying to install ssh to exchange screenshots faster between main pc and ubuntu pc that I need to put into ai (claude) to help me understand and learn:
Setting up ssh: sudo apt install openssh-server
