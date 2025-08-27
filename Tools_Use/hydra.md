# 🐉 Hydra (THC-Hydra)

## Description

Hydra is a fast and flexible password-cracking tool used for brute-force and dictionary attacks against more than 50 protocols 
and services (e.g., SSH, FTP, HTTP, RDP, SMTP, Telnet). It is widely used in penetration testing to evaluate the strength of 
authentication mechanisms.

---

## ✅ Key Features:

- Supports many protocols (SSH, FTP, HTTP, MySQL, RDP, SMB, etc.)

- Performs brute-force and dictionary attacks

- Parallelized to run multiple login attempts quickly

- Works with username and password lists

- Useful for red teaming, password audits, and security assessments

---

## 🛠 Example Usage

### Brute-force FTP login
**`hydra -l admin -P passwords.txt ftp://192.168.1.10`**

### Brute-force SSH login
**`hydra -l root -P rockyou.txt ssh://192.168.1.10`**

### Brute-force HTTP login form
**`hydra -l admin -P passlist.txt 192.168.1.30 http-post-form "/login.php:user=^USER^&pass=^PASS^:F=incorrect"`**

---

- **`-l admin`** → sets the login/username to admin (single user)
  
- **`-P passwords.txt`** → tells Hydra to use a password wordlist from passwords.txt

- **`ftp://192.168.1.10`** → target protocol is FTP, and the target IP is 192.168.1.10.

- **`ssh://192.168.1.20`** → target is SSH service at IP 192.168.1.20

---

- http-post-form → tells Hydra that we are attacking an HTTP POST login form.

- **`"/login.php:user=^USER^&pass=^PASS^:F=incorrect"`** → form details.

- **`/login.php`** → path of the login page.

- **`user=^USER^&pass=^PASS^`** → parameters where Hydra will substitute ^USER^ and ^PASS^ with username and password values from your lists.

- **`F=incorrect`** → failure message (Hydra looks for this string in the response; if it finds it, login failed, otherwise success).

---

## Tool use

