# MITMF

This project is a middle man attack project that is still under development. The python file named arp-poison Ulitsa contains a block of code that changes the MAC address of the gateway path with your MAC address in line with the target and gateway path you provide to scan your network. Packet-listener is a packet listening tool with the same function as whireshark. The code block in it is written to listen to HTTP.


(NOTE: You must use sslstrip to work with HTTPS.)


Example of use arp-poison […]:

python3 arp-poison.py -t 10.0.2.4 -g 10.0.2.1


Example of use packet-listener :

python3 packet-listener.py
