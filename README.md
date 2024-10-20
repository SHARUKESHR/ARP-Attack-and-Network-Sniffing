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
![eth 04 1](https://github.com/user-attachments/assets/0b3bc881-2df3-4c6d-a504-136d39401a11)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![eth 04 2](https://github.com/user-attachments/assets/0596a5a1-7d56-467f-916c-af43fbf0f64e)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:



![eth 04 3](https://github.com/user-attachments/assets/2f46fead-e1ef-406c-984e-f41465c2f0fd)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![eth 04 4](https://github.com/user-attachments/assets/c798fbd2-7c6c-4dfc-ab39-a69d13c9db27)



Invoke the wireshark and examine the various menus  and controls of the tool:
![eth 04 5](https://github.com/user-attachments/assets/372b2374-01cc-406d-b6bb-4f551a88afa2)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
