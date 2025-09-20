# EX 4 ARP-Attack-and-Network-Sniffing
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
<img width="681" height="814" alt="image" src="https://github.com/user-attachments/assets/62faaf8d-1d3b-4208-938b-62f2cb568247" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="821" height="930" alt="image" src="https://github.com/user-attachments/assets/3f176cbc-81a2-40fe-bbc3-1a10905556ff" />








In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="623" height="737" alt="image" src="https://github.com/user-attachments/assets/a59d3af4-eb0a-4dee-8aba-1209797f0f2f" />


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="575" height="362" alt="image" src="https://github.com/user-attachments/assets/83b480bb-e9eb-475d-91ae-9d9e5c70f440" />




Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
