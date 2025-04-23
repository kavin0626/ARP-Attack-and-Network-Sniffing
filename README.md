# EX:4-ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode
- `Step 2:` Investigate on the various categories of tools as follows.
-  `Step 3:` Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![O1](https://github.com/user-attachments/assets/d6ecc01f-2a9c-415f-b459-e65c07639b9a)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![O2](https://github.com/user-attachments/assets/f582ee5f-89e0-4736-9640-7e40db64e526)


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![O3](https://github.com/user-attachments/assets/3e3cc724-d1a7-4e74-9c8e-cdc8418c77da)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![O4](https://github.com/user-attachments/assets/39432531-60aa-4d43-8e30-eae0e4349de5)


Invoke the wireshark and examine the various menus  and controls of the tool:
![O5](https://github.com/user-attachments/assets/79da2025-11b2-4b43-946f-e6772cf22f0f)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
