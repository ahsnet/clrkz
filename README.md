# VPSAutoScrptz
Tunneling Service:  
OCS Panel: 85   
OpenSSH : 22, 444   
Dropbear : 143, 3128    
SSL : 443     
Squid3 : 8000, 8080 (limit to IP SSH)     
OpenVPN : TCP 1194 (client config : http://myip:81/client.ovpn)    
badvpn : badvpn-udpgw port 7300    
nginx : 81

# Installation
OCS Panel Only: wget https://raw.githubusercontent.com/ahsnet/clrkz/master/ocspanel.sh && chmod +x ocspanel.sh && ./ocspanel.sh 

OCS & VPS: wget https://raw.githubusercontent.com/Clrkz/VPSAutoScrptz/master/VPSnOCScrptZ.sh && chmod +x VPSnOCScrptZ.sh && ./VPSnOCScrptZ.sh

VPS Only (For Servers) : wget https://raw.githubusercontent.com/ahsnet/clrkz/master/debi9.sh && chmod +x debi9.sh && ./debi9.sh

Disable Change Password in Panel: wget https://raw.githubusercontent.com/Clrkz/VPSAutoScrptz/master/DsblChngPW.sh && chmod +x DsblChngPW.sh && ./DsblChngPW.sh

Updates:
Kill Multilogin, Delete All Expired Users
cd && wget -O ClrkzOCSUpdate "https://github.com/Clrkz/VPSAutoScrptz/raw/master/update-ocs.sh" && chmod +x ClrkzOCSUpdate && sed -i -e 's/\r$//' ClrkzOCSUpdate && ./ClrkzOCSUpdate && rm ClrkzOCSUpdate

# Credits
Modder: Clrkz https://fb.com/143Clarkz

Original script by :
* Fornesia
* Rzengineer
* Fawzya
