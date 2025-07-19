# Vulnerable Target Setup

This guide will help you set up the vulnerable VM **Metasploitable 2** in VirtualBox for your cybersecurity lab.

---

## Table of Contents

1. [Download Metasploitable 2](#1-download-metasploitable-2)
2. [Extract the Downloaded File](#2-extract-the-downloaded-file)
3. [Create a New VM in VirtualBox](#3-create-a-new-vm-in-virtualbox)
4. [Attach the Virtual Hard Disk](#4-attach-the-virtual-hard-disk)
5. [Start the VM](#5-start-the-vm)
6. [Login Details](#6-login-details)
7. [You're Ready!](#7-youre-ready)

---

## 1. Download Metasploitable 2

- Download the vulnerable VM image "Metasploitable 2" from the official source:

https://github.com/user-attachments/assets/5b392e14-f408-42a0-80e5-107cdcf93fd8

- Downloaded file will be in ZIP form.

![image](https://github.com/user-attachments/assets/dcad187a-f1ae-4bf0-9224-e04fd9ac8b38)

---

## 2. Extract the Downloaded File

- Extract the ZIP file to a convenient location on your computer.

![image](https://github.com/user-attachments/assets/5a221464-fbb6-424d-96a8-7acd6439463b)

---

## 3. Create a New VM in VirtualBox

- Open **VirtualBox** and click on **New**.

![image](https://github.com/user-attachments/assets/fd2bb005-59c5-4a26-a882-889eb884ad74)

- Enter a **name** for your VM (e.g., Metasploitable2).
- Set:
  - **Type:** `Linux`
  - **Version:** `Other Linux (64-bit)` (or 32-bit, depending on your system)

![image](https://github.com/user-attachments/assets/a494b0ee-5cc4-4240-b953-093d7032dffd)


- Keep the default hardware settings and click **Next**.

![image](https://github.com/user-attachments/assets/a6909348-d03a-4e47-a700-6c6bd2790e74)

---

## 4. Attach the Virtual Hard Disk

- Choose **Use an existing virtual hard disk file** and click the **folder** icon.

![image](https://github.com/user-attachments/assets/f9fa7bb0-c891-44d9-8272-0d3a7cf1a580)


- Navigate to the folder where you extracted the ZIP file and select the disk image file.

  
![image](https://github.com/user-attachments/assets/a7a6205d-ca3a-476c-9e98-9e71309102b5)


- Select the Metasploitable disk under "Not Attached". In your case, there should be only one option (if you haven't previously installed it) click **Choose**.
  
![image](https://github.com/user-attachments/assets/44412ed8-0511-4560-9d73-230531062168)


- Click **Next**.

![image](https://github.com/user-attachments/assets/28f00d17-216e-41d8-8fe3-8df2f3e3687c)

- Review all configurations and click **Finish**.

![image](https://github.com/user-attachments/assets/6311753c-d680-4844-9c74-7a025271a6a7)

---


## 5. Start the VM

- Select the Metasploitable 2 VM in VirtualBox and click **Start**.

![image](https://github.com/user-attachments/assets/475800e0-78f4-4947-a8e2-40248eb8506d)

- The system will configure itself for a few minutes.

---

## 6. Login Details

- Once the VM boots up, log in using:

  - **Username:** `msfadmin`
  - **Password:** `msfadmin`
 
![image](https://github.com/user-attachments/assets/51c454c9-9982-4760-b83f-bf313eaa5fe4)

---
  
## 7. You're Ready!

Your vulnerable target machine is now set up and ready for use in your cybersecurity lab.

---

> **Tip:**  
> For security, ensure this VM is only accessible within your isolated lab network and never exposed directly to the internet.
