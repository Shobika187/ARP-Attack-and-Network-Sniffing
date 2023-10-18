# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![image](https://github.com/Shobika187/ARP-Attack-and-Network-Sniffing/assets/94508142/c7accb17-f498-410d-bdf0-236312ab6059)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Shobika187/ARP-Attack-and-Network-Sniffing/assets/94508142/8f5b3bbe-9743-4040-b3e4-d7ac3d0f9192)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/Shobika187/ARP-Attack-and-Network-Sniffing/assets/94508142/6ca4eb6e-82d9-4ff7-81fe-fc89c8cf66f3)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/Shobika187/ARP-Attack-and-Network-Sniffing/assets/94508142/05c1d5cb-326b-464c-8348-244ebcf264c6)


Invoke the wireshark and examine the various menus  and controls of the tool:


## OUTPUT:
![image](https://github.com/Shobika187/ARP-Attack-and-Network-Sniffing/assets/94508142/8f7d46d1-a58c-481c-acef-fb24435948ad)
## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Ettercap can be used as sniffing tool as illustrated below:

## OUTPUT:
![image](https://github.com/Shobika187/ARP-Attack-and-Network-Sniffing/assets/94508142/7e5ce09f-1751-41a1-b063-9a143793788d)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
