# ICMP-Packet-Analysis
ICMP Protocol Analysis using Wireshark

Basic steps to analyze the ICMP protocol using Wireshark filters.
--> Common display filters used for search are:
1. icmp                                        # shows all ICMP traffic
2. icmp.type == 8                              # shows echo requests
3. icmp.type == 0                              # shows echo replies
4. icmp.code ==3                               # destination unreachable
5. ip.addr == 192.168.1.10                     # ICMP traffic from-to specific host
                                               # IP address taken as an example.
   
