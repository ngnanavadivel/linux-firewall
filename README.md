# Linux built-in Firewall!

## netfilter

 The Linux Kernel comes with a packet filtering framework called *netfilter*. It allows to accept, drop or update packets of the incoming / outgoing traffic.
 
## iptables

*iptables* is one of the utilities that comes along with the Linux kernel which is a **powerful firewall** built on top of *netfilter* and it can be customized/configured using *rules*.

## fail2ban

*fail2ban* is another utitlity which is coded based on *iptables* which is used to block attackers from gaining access and helps in Linux Server Hardening.

# Let's try to understand how iptables work:

The iptables' packet filtering mechanism is built based on 3 important structures which are 
 - tables
 - chains
 - target
 
 ## Tables
 
 The tables are of 4 types:
 
 1. **filter** table
 
 
 
 2. **mangle** table
 
 
 
 3. **nat** table
 
 
 
 4. **raw** table
 
 
