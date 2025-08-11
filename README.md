The yaml file is the lab backup file for the CML. You can directly upload this yaml file to CML to replicate my lab.


<img width="2260" height="1070" alt="image" src="https://github.com/user-attachments/assets/fa4710ce-9cc0-417e-bb75-1a9da6bf911f" />



This is the traceroute from the Host connected to PE1 device, It is pinging the host connected in the Data center vrf TENANT1

inserthostname-here#traceroute vrf Cust1 192.168.10.15
Type escape sequence to abort.
Tracing the route to 192.168.10.15
VRF info: (vrf in name/id, vrf out name/id)
  1 192.167.1.1 4 msec 3 msec 3 msec
  2 22.1.1.5 [MPLS: Labels 16001/23 Exp 0] 6 msec 5 msec 5 msec
  3 22.1.1.1 [MPLS: Label 23 Exp 0] 5 msec 5 msec 5 msec
  4 21.1.1.5 [MPLS: Label 492288 Exp 0] 5 msec 5 msec 4 msec
  5 192.168.10.254 11 msec 11 msec 11 msec
  6 192.168.10.15 14 msec *  13 msec

inserthostname-here#ping vrf Cust1 192.168.10.15
Type escape sequence to abort.
Sending 5, 100-byte ICMP Echos to 192.168.10.15, timeout is 2 seconds:
!!!!!
