# iptables-management

The Debian Package iptables-management
----------------------------

Provides is a utililty tool for managing iptables rules and is loaded at boot time.
It is equivilant to **iptables-persistent** by providing the exact same functionality
in addition to, allowing packages to install rules within the provided directories.
The rules are generated every time iptables-management is reloaded and is saved to 
*/etc/iptables/ipv4/rules* and */etc/iptables/ipv6/rules* from where it is then loaded to 
*iptabels* and *ip6tables* respectivly.

 -- Aron Podrigal <aron@mongotel.com>  Mon, 27 Apr 2015 06:50:40 -0400
