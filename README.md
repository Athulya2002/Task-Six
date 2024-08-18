# Task-Six
ICMP PACKET CAPTURE USING WIRESHARK 

This repository contains a packet capture file (ping.pcapng) generated using Wireshark on Kali linux. The task involved capturing ICMP packets during a ping operation to google.com , filtering the capture to only include four ICMP request and four ICMP Echo reply packets , and saving the results.

STEPS FOLLOWED

1.Open Wireshark and Start Capturing Packets

Wireshark Interface : Wireshark was opened in Kali Linux.
Network Interface : The eth0 interface was selected for packet capture.
Packet Capture : The capture was started to monitor network traffic on eth0.

2.Ping Google.com from the terminal

ping command : The following command was executed in the terminal.
              ping -c 4 google.com

3.Observe Captured ICMP Packets in Wireshark

Stopping the capture : After the ping command completed , the packet capture was stopped.
Filtering for ICMP : The capture wad filtered to display only ICMP packets using the ICMP filter.
File saving : The filtered capture was saved as ping.pcapng.
