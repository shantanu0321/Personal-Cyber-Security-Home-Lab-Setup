#  Set both VMs to “Host Only” or “Internal Network” for Safety.

This guide will help you configure the network settings for your Kali Linux and Metasploitable 2 virtual machines in VirtualBox to ensure a safe, isolated lab environment.

---

## 1. Configure the Kali Linux Machine

1. Open **VirtualBox** and select your **Kali Linux** machine.
2. Click on **Settings** > **Network**.

![image](https://github.com/user-attachments/assets/e7a14afd-7b22-43e6-89e7-8335967820b3)


3. Change the network adapter from **NAT** to **Host Only Adapter**.

![image](https://github.com/user-attachments/assets/65b02aae-d5f3-43fd-88c4-6ceabf3565da)

---

## 2. Configure the Metasploitable 2 Machine

1. In **VirtualBox**, select your **Metasploitable 2** machine.
2. Click on **Settings** > **Network**.

![image](https://github.com/user-attachments/assets/d7969288-ded1-4935-9657-e851c05f51ea)


3. Change the network adapter from **NAT** to **Host Only Adapter**.

![image](https://github.com/user-attachments/assets/1d5ae852-ffec-4ecf-b721-272650a9b1cb)

 ---

## 3.Test connectivity

1. Start both the **Kali Linux** and **Metasploitable 2** VMs.
2. Log in to both machines.
3. Find the IP address assigned to each machine. Open Terminal and run this:
    ```
    ifconfig 
    ```
4. On your **Kali Linux** VM, open a terminal and try to ping the Metasploitable 2 VM’s IP address:
   ```
   ping <Metasploitable-2-IP-address>
   ```
   If you receive replies, the network is properly configured and both machines are on the same isolated network.
    
https://github.com/user-attachments/assets/0cf32af4-fd92-4125-9f03-e5cada14f886

---

## Next Steps

With networking configured, you can proceed to use your lab for safe, hands-on cybersecurity practice. Refer to other sections of this repository for tool installation and exercises.
