# Cybersecurity-Home-lab-Setup
A 3-VM Isolated cybersecurity home lab built with VirtualBox
This project documents the setup of a 3-VM isolated home lab 
environment using VirtualBox. The lab consists of Kali Linux, 
Ubuntu Server, and Metasploitable 2, all connected on a 
Host-Only network for safe and controlled cybersecurity practice.

# Lab Environment
1. Kali Linux — 192.168.56.103 
2. Ubuntu Server — 192.168.56.102 
3. Metasploitable 2 — 192.168.56.101 
4. Network: Host-Only (vboxnet0) — 192.168.56.0/24

# Steps Taken
1. Installed VirtualBox
2. Created Kali Linux VM
3. Created Ubuntu Server VM
4. Added Metasploitable 2 using .vmdk file
5. Set all 3 VMs to Host-Only network (vboxnet0)
6. Confirmed IPs using ip a and ifconfig
7. Pinged all VMs from Kali to confirm communication
8. Drew network topology diagram on draw.io
9. Took snapshots of all 3 VMs

# When to take snapshots
A VM snapshot should be taken:
1. Before running any exploits or scans
2. Before installing new tools
3. After a clean working setup is confirmed

This is important because it allows instant restoration if something breaks without 
needing to rebuild the VM from scratch.




