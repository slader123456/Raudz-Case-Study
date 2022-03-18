# Raudz-Case-Study


Adressing structure:

Kelowna: 192.168.1.0 /24

DHCP SCOPE: 192.168.1.100 /24 - 192.168.1.220 /24

DC01 (DHCP,DNS,AD,GPO,DFS,Stores drives and access / sharing privileges): 192.168.1.1 /24 

DC02 (DHCP Failover 50-50, DNS failover, GPO failover, DFS failover): 192.168.1.2 /24

PC01: DCHP 

RRAS (VPN tunnel to Calgary domain): 192.168.1.3 /24


Vernon:

DC01 (RODC From DC01 and DC02 from Kelowna Domain, DFS):

PC01 (DHCP):

RRAS (VPN Tunnel to Kelowna domain):


New domain names:

Kelowna:
kel.raudz.com

Calgary:
cal.raudz.com


