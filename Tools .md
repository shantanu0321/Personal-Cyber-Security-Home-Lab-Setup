# Tools Installed

- To Update Kali Linux Tools You have to be on a your "NAT" network.
  
![image](https://github.com/user-attachments/assets/3ede1e87-df65-4670-ac0a-cfe55a146034)

 
- Now Start the Machine and open the Terminal and write the command `sudo apt update && sudo apt upgrade` and enter the password for root user `kali`.

  
https://github.com/user-attachments/assets/85b40f13-d1fb-40e6-bd40-792d9ca08b1d

- Now all the tools in the Kali Linux is updated and upgraded.

---
  
# Verify tools

1. Nmap: Network exploration tool and security / port scanner. Nmap (“Network Mapper”) is an open source tool for network exploration and security auditing.
  
  
  - To get all the Scan types of Nmap, run the command `man nmap` or `nmap --help` in the terminal.

   ![image](https://github.com/user-attachments/assets/b7801e8b-a43a-41f7-a3d8-a8420a7a510d)

---  

2. Burp Suite: Burp Suite is a powerful and versatile web application security testing platform. It is used to identify vulnerabilities and assess the security posture of web applications.

- For proper functioning of Burpsuite you must install " java " in your Linux OS.
  
  > To install java run the command `sudo apt install default-jdk`. 
  
https://github.com/user-attachments/assets/15d06353-3b43-44e6-b13f-a68461aad4cc

  > After installation, you can verify it by checking the Java version with `java --version`.

  ![image](https://github.com/user-attachments/assets/219a2bbb-8103-470b-80fb-bb53829c7334)

 - To start Burpsuite type command `bash` and then type `burpsuite` in terminal.
   
   https://github.com/user-attachments/assets/f159f4d5-e506-4595-ab12-364882ceb3ce

---

3. Wireshark: It is a free and open-source packet analyzer. It's a powerful tool used to capture and analyze network traffic in real-time, allowing users to examine the data passing through a network.
   
    > To start wireshark type command `wireshark` in the terminal

https://github.com/user-attachments/assets/6733ffc2-428c-42ea-a405-a1aff14af616


---
  
4. Metasploit Framework: The Metasploit Framework is a powerful, open-source platform used for developing and executing exploit code, primarily for penetration testing and security assessments. It provides a comprehensive environment for discovering vulnerabilities, testing attack strategies, and validating security measures.

- To start Metasploit Framework type command `msfconsole` in the Terminal.


https://github.com/user-attachments/assets/7be9f7b1-53b3-4de5-8fda-0729ae45210e

---

5. OSWAP Juice-shop: OWASP Juice Shop is a deliberately vulnerable web application designed for security training and learning. It's created by the Open Worldwide Application Security Project (OWASP) to help developers, security professionals, and students understand and practice identifying and mitigating common web application vulnerabilities.

 - This is the setup for OSWAP juice-shop.

   
 1.    Install node.js
 2.    Run `git clone https://github.com/juice-shop/juice-shop.git`.(or clone your own fork of the repository)
 3.    Go into the cloned folder with `cd juice-shop`
 4.    Run `npm install` (only has to be done before first start or when you change the source code)
 5.    Run `npm audit fix --force` (In case if npm install shows any error)
 6.    Run `npm i --package-lock-only` ( This command will make a package file for `npm audit fix --force`)
 7.    Run `npm audit fix --force` again to fix everything.
 8.    Run `npm start`
 9.    Browse to " http://localhost:3000 " in your Browser.
 10.   Now you can use it for pentesting using Burpsuite tool.

  > Watch the video for better understanding.



https://github.com/user-attachments/assets/44a909b0-25d2-4366-ab20-0566ec896a8a



---
     

