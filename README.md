# Ancora-Education-Ucertify-Lab70
# Part III: Command Line Tools

Command line tools are powerful utilities that allow users to interact with a computer's operating system through text-based commands. In this lab session, you will explore various command line tools and learn how to use them effectively. This lab session will cover several command line tools, namely, dig, tcpdump, and nmap commands.

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=13]

## Lab Objective 
This lab session will demonstrate the steps involved in using dig, tcpdump, and nmap commands to troubleshoot network issues. Upon completion of this lab, you will be able to: Understand the purpose of the dig, tcpdump, and nmap commands. Capture and analyze network traffic using the dig command. Capture and analyze network packets using the tcpdump command. Scan networks for open ports and services using the nmap command. Lab/Machine Environment You are provided with the Linux virtual machine.
## PART A: Analyzing Command Line Tools
Launch the Terminal, execute dig, tcpdump, and nmap commands, and then analyze their results. For nmap, use the IP address as 192.168.56.102. The Terminal refers to a text-based interface that allows users to interact with the operating system using command-line commands. It is also known as a shell or command-line interface (CLI). The Terminal provides a direct means of executing commands and running various programs without the need for a graphical user interface (GUI).
### STEP 1 
From the top bar, click the Terminal icon.
### STEP 2 
Execute the following command to install and resolve a given FQDN to its IP address (Note: Execute one command at a time.):
```bash
sudo apt-get install dnsutils
```
```bash
dig www.google.com
```
### Caution 
If asked Do you want to continue?, type Y and press Enter. 
### STEP 3
Execute the following command to capture packets from a specific interface:
```bash
tcpdump -i eth0 > captured_packets.txt
```
### STEP 4 
Wait for 2 minutes and then press Ctrl+C to stop the command:
### Caution 
Make sure to wait for 2 minutes before proceeding. 
### STEP 5
Execute the following command to view the captured packets from a specific interface:
```bash
cat captured_packets.txt
```
### STEP 6 
Execute the following command to scan for live hosts, operating systems, packet filters, and open ports:
```bash
nmap 192.168.56.102
```
## Lab Summary
This lab session provides you with a straightforward and practical understanding of how to use dig, tcpdump, and nmap commands to troubleshoot network issues. Here's a summary of what you have learned: 
* The purpose of the dig, tcpdump, and nmap commands.
* How to capture and analyze network traffic using the dig command.
* How to capture and analyze network packets using the tcpdump command.
* How to scan networks for open ports and services using the nmap command.

Now, you are equipped with the knowledge and skills to use dig, tcpdump, and nmap commands to troubleshoot network issues effectively.
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
