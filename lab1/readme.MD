## Laboratory Work 1 Information security attacks (MITM):

# Tools used
1. Arpspoof (https://github.com/alandau/arpspoof)
2. Nmap
3. Wireshark 2

# Steps
1. Using NMap we can analyze the devices in the local network and get their Ip address and MAC.
2. After finding a victim we use arpspoof to arp poison him and redirect his trafic through our machine.
3. Using Wireshark we can now analyze sent packets. To make it easier we filter the packets by the mac address and type of http.

# Demo

See /res/lab1_demo