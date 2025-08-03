# ☁️ Cloud VM Deployment Lab – AWS EC2 & Azure Virtual Machines

This lab demonstrates the creation, configuration, and secure remote access of virtual machines (VMs) in **Amazon Web Services (AWS EC2)** and **Microsoft Azure** using SSH key-based authentication. The lab simulates real-world infrastructure deployment scenarios across cloud platforms.

---

## 🧰 Technologies Used

- **Amazon Web Services (AWS EC2)**
- **Microsoft Azure**
- **Ubuntu (Cloud VM OS)**
- **SSH (Secure Shell)**
- **VirtualBox** (for local VM testing)
- **Command Line Tools** – `ssh`, `chmod`, `nslookup`, `whoami`, `ps`

---

## 🔄 Workflow Summary

### ✅ Part 1 – AWS EC2 Instance Deployment

1. Launched an Ubuntu EC2 instance in **ca-central-1** region
2. Created and downloaded a secure SSH key pair
3. Retrieved public DNS and IP of the EC2 instance
4. Verified DNS resolution using `nslookup`
5. Connected via:
   - **AWS console web terminal**
   - **Local virtual machine via SSH** using key authentication
6. Adjusted file permissions using `chmod 400`
7. Verified remote login using `whoami` and `ps`
8. Took screenshots for VM status, terminal session, and successful login
9. Terminated the EC2 instance when complete

---

### ✅ Part 2 – Azure Linux VM Deployment

1. Created a Linux VM via **Azure Free Services**
2. Chose Ubuntu Server image and configured defaults
3. Set SSH authentication using Azure-generated key pair
4. Downloaded the `.pem` key and saved securely
5. Verified deployment and retrieved VM’s public IP
6. Connected via SSH from local VM using key
7. Validated session with terminal commands and screenshots
8. Deleted the Azure VM and associated resources after testing

---

## 📁 Project Structure

