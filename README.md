# Raudz-Case-Study


Adressing structure:

Kelowna:

DC01 (DHCP,DNS,AD,GPO,DFS,Stores drives and access / sharing privileges):

DC02 (DHCP Failover 50-50, DNS failover, GPO failover, DFS failover): 

PC01 (DCHP): 

RRAS (VPN tunnel to Calgary domain): 


Vernon:

DC01 (RODC From DC01 and DC02 from Kelowna Domain, DFS):

PC01 (DHCP):

RRAS (VPN Tunnel to Kelowna domain):


New domain names:

Kelowna:
kel.raudz.com

Calgary:
cal.raudz.com


