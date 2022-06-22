# Ethical_Hacking
Ethical Hacking notes
Scanning Networks:
Network scanning refers to a set of Procedures used for identifying hosts, ports and Services in a network. It is one of the components of intelligence gathering.

Objectives of Network Scanning:
1.	To discover live hosts, Ip address and open ports of live hosts
2.	To discover operating systems and system architecture
3.	To discover services running on hosts
4.	To discover vulnerabilities in live hosts

TCP Session Establishment – Three – way handshake
TCP Session Termination – Four – way handshake

Scanning Tools:
1.	Nmap to extract information such as line hosts on the network, open ports, services (application name and version), types of pocket filter, firewalls, operating systems and version.
2.	Hpings/Hping3: command line network scanning and packet crafting.

ARP Ping Scan: Attackers send ARP request probes to target hosts, and an ARP response indicates that the host is active.
Nmap-sn-PR (IP Address)

UDP Ping Scan: Attackers send UDP packets to target hosts and a UDP response indicates that the host is active.
Nmap-sn-PU (IP Address)

TCP Connect/full Open Scan Zenmp nmap-st-v (IP Address)
Scan result when a port is open:




Scan result when a port is closed:





Inverse TCP flag scan and Xmas Scan: Attackers send TCP probe packets with a TCP flag(FIN, URG, PSH) set or with no flags.

Port open:



Port closed:





It does not work in windows systems
