## Computer Network data traffic Analysis
> Network attacks prevent a business from operating. for example, ZOOM during corona event. 


>Malicious software (Malware) includes:
• Virus
• Worms
• Trojan horses

>Goals:
• Destroy data
• Corrupt data
• Shutdown a network or system

>Ransomware:
Encrypts files, demands ransom for the key.
Doesn't need to be reported as a breach, because no data was stolen.
For example, Zoom.

>Firewalls: 
Identify traffic on uncommon ports.
• Can block this type of attack, if your firewall
filters outgoing traffic.
• Windows Firewall in XP SP2, Vista, and Win 7 does not filter outgoing traffic by default
• Trojan programs can use known ports to get through firewalls.
• HTTP (TCP 80) or DNS (UDP 53).

>Botnets:
A Botnet is a network of Internet devices (i.e. computers, mobile
etc) that have been manipulated to carry out malicious activities.
• The owners of such devices are often unaware of this.
• These Bots serve the wishes of some master known as Command.
& Control.

Bot examples:
• Neris | IRC
• Rbot | IRC
• Menti | IRC
• Sogou | HTTP
• Murlo | IRC
• Virut | HTTP
• NSIS | P2P
• Zeus | P2P
• SMTP Spam | P2P
• UDP Storm | P2P
• Tbot | IRC |
• Zero Access | P2P
• Weasel | P2P
• Smoke Bot | P2P
• Zeus Control (C&C) | P2P

## How to obtain data
Computer Network data can be obtained by using capture
tools such as WireShark, Snort, tcpdump … etc
• Also there are freely available datasets (for research purposes)
• Some useful examples are here (labelling info is
provided): https://www.unb.ca/cic/datasets/botnet.html
• The data is normally in binary format (PCAP for Packet
Capture)
• In order to transform this data into a format understandable
by machine learning tool, several steps should be performed

## How to convert PCAP to CSV or Data preparation
• Convert PCAP Data into a suitable format for Machine Learning (CSV)
• Use open source Java tool (works best on Ubuntu Linux):
• https://github.com/ahlashkari/ISCXFlowMeter
• Requires JNetPcap Package
https://sourceforge.net/projects/jnetpcap/
• This tool generates several numeric attributes (features) such as Source
Port, Destination Port, Protocol, Flow Duration, Flow Bytes per second
and Flow Packets per second.

## Classify the balanced/unbalanced data using Machine Learning/Deep Learning algorithm using CSV file.



