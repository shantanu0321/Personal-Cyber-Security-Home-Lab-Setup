##  Vulnerable Target Setup

- Download a vulnerable VM image Metasploitable 2.

https://github.com/user-attachments/assets/5b392e14-f408-42a0-80e5-107cdcf93fd8

After the download is complete extract the file.

  ![mt](https://github.com/user-attachments/assets/b1203df4-5015-4a60-8d92-3f78860c3db9)



![ext](https://github.com/user-attachments/assets/215a46e7-610c-4645-accb-6d1af8c9d05f)


After extraction open the Virtual Machine and click on "Add".

![ins](https://github.com/user-attachments/assets/251844aa-95bf-465f-b20e-b35046249b12)


Write the name of machine and change the **Type** to Linux and **Subtype** to other Linux and **Version** to Other Linux(64-bits) as shown in the photo and click on next.

![11](https://github.com/user-attachments/assets/784b6c3f-abd0-432e-bcef-54d7ea61cc50)


Let the hardware setting to default and click on next.

![12](https://github.com/user-attachments/assets/892e6316-5ac6-4c35-b6ff-ec908d83cefa)


  
- Import or install as a separate VM.
- Set both VMs to “Host Only” or “Internal Network” for safety.

## 4. Networking
- Ensure both VMs are on the same virtual network.
- Test connectivity (e.g., ping from Kali VM to target VM).

## 5. Tool Installation
- Update Kali: `sudo apt update && sudo apt upgrade`
- Verify tools: Nmap, Nikto, Burp Suite, Metasploit Framework, etc.
- For defense: install Snort/Suricata/OSSEC as needed.
