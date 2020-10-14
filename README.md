# Change-Linux-MAC
changes MAC in Linux for network security in command line -i or -interface and --m or --mac and - h for help
 run 

python macchanger.py -i eth0 -m 14:12:12:12:12:22

Current MAC = 12:12:12:12:12:22
[+] Change mac adress eth0 to 14:12:12:12:12:22
[+] MAC address was successfully changed to 14:12:12:12:12:22

Usage: macchanger.py [options]

Options:
  -h, --help            show this help message and exit
  -i INTERFACE, --interface=INTERFACE
                        Interface to change its MAC address
  -m NEW_MAC, --mac=NEW_MAC
                        New MAC address
