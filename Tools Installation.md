# Tool Installation

- To Update Kali Linux Tools You have to be on a your "NAT" network.
  
![image](https://github.com/user-attachments/assets/3ede1e87-df65-4670-ac0a-cfe55a146034)

 
- Now Start the Machine and open the Terminal and write the command `sudo apt update && sudo apt upgrade`

  
https://github.com/user-attachments/assets/85b40f13-d1fb-40e6-bd40-792d9ca08b1d

- Now all the tools in the Kali Linux is updated and upgraded.

---
  
# Verify tools

1. Nmap: Network exploration tool and security / port scanner. Nmap (“Network Mapper”) is an open source tool for network exploration and security auditing.
  
  > SYNOPSIS

       nmap  [Scan Type...]  [Options]   {target specification}
  
        # nmap -A -T4 192.168.XX.X
  
  - To get all the Scan types of Nmap, run the command `man nmap` or `nmap --help` in the terminal.

   ![image](https://github.com/user-attachments/assets/b7801e8b-a43a-41f7-a3d8-a8420a7a510d)

---  

2. Burp Suite: Burp Suite is a powerful and versatile web application security testing platform. It is used to identify vulnerabilities and assess the security posture of web applications.

- For proper functioning of Burpsuite you must install " java " in your Linux OS.
  
  > To install java run the command `sudo apt install default-jdk`. 
  
https://github.com/user-attachments/assets/15d06353-3b43-44e6-b13f-a68461aad4cc

  > After installation, you can verify it by checking the Java version with `java --version`.

  ![image](https://github.com/user-attachments/assets/219a2bbb-8103-470b-80fb-bb53829c7334)

 - To open Burpsuite type command `bash` and then type `burpsuite` in terminal.
   
   https://github.com/user-attachments/assets/f159f4d5-e506-4595-ab12-364882ceb3ce


   


   
- Metasploit Framework
- For defense: install Snort/Suricata/OSSEC as needed.
