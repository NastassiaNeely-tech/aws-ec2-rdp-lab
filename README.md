# AWS EC2 Lab: Connecting to a Windows Instance via RDP

## 📌 Overview
This lab demonstrates how to securely connect to a Windows EC2 instance in AWS using Remote Desktop Protocol (RDP) and a key pair for password decryption.

This project highlights foundational cloud and security skills relevant to cybersecurity and cloud engineering roles.

---

## 🎥 Video Walkthrough
[Click here to watch the Loom walkthrough] (https://www.loom.com/share/6a160d4bed04412dbbb21f189166cb2a)

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
![EC2 Status](images/ec2-status.png)

### 2. Connecting via RDP Client
![RDP Client](images/rdp-client.png)

### 3. Uploading Private Key & Decrypting Password
![Decrypt Password](images/decrypt-password.png)

### 4. Remote Desktop Login
![RDP Login](images/rdp-login.png)

### 5. Successful Connection to EC2 Instance
![Connected Desktop](images/connected-desktop.png)

---

## 🔄 Step-by-Step Process

1. Navigate to the AWS Management Console  
2. Open the EC2 service  
3. Click on **Instances**  
4. Verify instance is running and status checks have passed  
5. Select the EC2 instance (named "windows")  
6. Click **Connect**  
7. Choose the **RDP client** tab  
8. Download the Remote Desktop file  
9. Open the `.rdp` file and click **Connect**  
10. In AWS, click **Get Password**  
11. Upload your `.pem` private key file  
12. Click **Decrypt Password**  
13. Copy the decrypted password  
14. Paste it into the RDP login prompt  
15. Click **Yes** to accept the certificate  
16. Successfully connect to the EC2 instance  

---

## 🔐 Security Considerations
- Never share your `.pem` private key file  
- Store key pairs securely (use encrypted storage if possible)  
- Restrict RDP access (port 3389) using security groups  
- Rotate credentials when no longer needed  

---

## 🚀 Outcome
Successfully established a secure remote connection to a Windows EC2 instance using AWS tools and key-based authentication.

---

## 📁 Project Structure
