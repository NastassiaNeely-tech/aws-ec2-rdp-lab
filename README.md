# AWS EC2 Lab: Connecting to a Windows Instance via RDP

## 📌 Overview
This lab demonstrates how to securely connect to a Windows EC2 instance in AWS using Remote Desktop Protocol (RDP) and a key pair for password decryption.

This project highlights foundational cloud and security skills relevant to cybersecurity and cloud engineering roles.

---

## 🎥 Video Walkthrough
[!Click here to watch the Loom walkthrough] https://www.loom.com/share/6a160d4bed04412dbbb21f189166cb2a

---

## 🛠️ Technologies Used
- AWS EC2
- Windows Server (EC2 instance)
- Remote Desktop Protocol (RDP)
- Key Pair Authentication (.pem)

---

## 🧠 Key Skills Demonstrated
- Cloud resource management (AWS EC2)
- Secure remote access configuration
- Public/private key pair usage
- Password decryption and authentication
- Navigating AWS Management Console

---

## 📸 Key Steps (Visual Highlights)

### 1. EC2 Instance Status Check
<img width="1898" height="891" alt="EC2-status" src="https://github.com/user-attachments/assets/27e82c81-8138-4cc1-8e39-177c6e5e6eb7" />

### 2. Connecting via RDP Client
<img width="1902" height="845" alt="RDP-login" src="https://github.com/user-attachments/assets/66e3b18d-c170-45ff-a5a9-dba82600ec5f" />

### 3. Uploading Private Key & Decrypting Password
<img width="1897" height="847" alt="Decrypt-private-key" src="https://github.com/user-attachments/assets/c3695fbf-86d1-4a8d-b213-5fbad45e1a60" />

### 4. Remote Desktop Login
<img width="1902" height="845" alt="RDP-login" src="https://github.com/user-attachments/assets/0a9b7fe1-e1ff-4d23-a4d7-b814b0b8e346" />

### 5. Successful Connection to EC2 Instance
<img width="1912" height="991" alt="Connected-desktop" src="https://github.com/user-attachments/assets/254d6607-cd5a-48fd-b2db-3039fdac691a" />

---

## Full Step-by-Step Process

### 1. Navigate to AWS Console
- Go to the AWS Management Console home page.

### 2. Access EC2 Service
- Click on **EC2** under the services section.

### 3. View Instances
- In the EC2 dashboard, click on **Instances**.

### 4. Verify Instance Status
- Ensure that:
  - Instance state is **running**
  - **Status checks** have passed

### 5. Select the Instance
- Locate your instance (in this lab, named **"windows"**)
- Click the checkbox next to the instance name

### 6. Connect to the Instance
- Click the **Connect** button at the top of the page

### 7. Choose RDP Client
- Select the **RDP client** tab

### 8. Download Remote Desktop File
- Click **Download Remote Desktop File**

### 9. Open the RDP File
- Open the downloaded `.rdp` file
- Click **Connect**

### 10. Retrieve Administrator Password
- In the AWS console:
  - Click **Get Password**
  - Click **Upload Private Key File**

### 11. Upload Key Pair
- Locate your downloaded `.pem` key pair file
- Click **Open**

### 12. Decrypt Password
- Click **Decrypt Password**
- The decrypted password will appear under the **Password** field

### 13. Copy Password
- Click the **copy icon** (double squares) to copy the password

### 14. Log Into the Instance
- Return to the Remote Desktop window
- Paste the decrypted password
- Click **OK / Connect**

### 15. Accept Security Prompt
- Click **Yes** when prompted

### 16. Instance Initialization
- The virtual machine will begin initializing
- You are now connected to your EC2 Windows instance

---

## 🔐 Security Considerations
- Never share your `.pem` private key file  
- Store key pairs securely (use encrypted storage if possible)  
- Restrict RDP access (port 3389) using security groups  
- Rotate credentials when no longer needed  

---

## 🚀 Outcome
Successfully established a secure remote connection to a Windows EC2 instance using AWS tools and key-based authentication.
