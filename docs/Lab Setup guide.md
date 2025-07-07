# Lab Setup Guide

## 1. Oracle VirtualBox Installation
- Download and install Oracle VirtualBox: https://www.virtualbox.org/wiki/Downloads

![oracle](https://github.com/user-attachments/assets/ac5cdd35-dc1d-48f8-a7ef-fba5a83a8124)

## 2. Kali Linux VM Setup
- Download Kali Linux ISO: https://www.kali.org/get-kali/
- Create a new VM in VirtualBox (2GB+ RAM, 20GB+ disk).
- Install Kali Linux following the installer prompts.

## 3. Vulnerable Target Setup
- Download a vulnerable VM image (e.g., Metasploitable, DVWA, or Juice Shop).
- Import or install as a separate VM.
- Set both VMs to “Host Only” or “Internal Network” for safety.

## 4. Networking
- Ensure both VMs are on the same virtual network.
- Test connectivity (e.g., ping from Kali VM to target VM).

## 5. Tool Installation
- Update Kali: `sudo apt update && sudo apt upgrade`
- Verify tools: Nmap, Nikto, Burp Suite, Metasploit Framework, etc.
- For defense: install Snort/Suricata/OSSEC as needed.

## 6. Snapshots
- Take VM snapshots at key stages for easy rollback.
