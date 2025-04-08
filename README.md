# 📦 Blockchain Assignment - IPFS (InterPlanetary File System)

## 🧑‍🎓 Submitted By
**Name:** Lucky Longre  
**Course:** B.Voc in Software Development  
**Subject:** Introduction to Blockchain  
**Assignment:** Uploading Files to IPFS using WSL Ubuntu

---

## 📌 Objective
To install IPFS (InterPlanetary File System) in a local Ubuntu environment (via WSL), upload files to the decentralized IPFS network, generate a unique CID (Content Identifier), and share it for verification.

---

## 🚀 Steps Performed

### ✅ Step 1: Download & Extract IPFS (Kubo)
```bash
wget https://dist.ipfs.tech/kubo/v0.32.1/kubo_v0.32.1_linux-amd64.tar.gz
tar -xvzf kubo_v0.32.1_linux-amd64.tar.gz
cd kubo
sudo bash install.sh
```

### ✅ Step 2: Initialize & Start IPFS
```bash
ipfs init
ipfs daemon
```

### ✅ Step 3: Add File to IPFS
I created a simple `hello.txt` file and uploaded it to IPFS using:
```bash
ipfs add hello.txt
```

### 📅 CID Generated:
```
QmRmU6fULi6BgXjw4j8TU7tZyNdn6w2EMbqQE2cWNH5RZN
```

### 🌐 File Access Link:
[https://ipfs.io/ipfs/QmRmU6fULi6BgXjw4j8TU7tZyNdn6w2EMbqQE2cWNH5RZN](https://ipfs.io/ipfs/QmRmU6fULi6BgXjw4j8TU7tZyNdn6w2EMbqQE2cWNH5RZN)

---

## 🖼️ Screenshots

### 1. IPFS Installation on Ubuntu (WSL)
![IPFS Installation](images/ipfs-installation.png)

### 2. IPFS Daemon Running
![Daemon Running](images/ipfs-daemon.png)

### 3. Adding File to IPFS and Getting CID
![CID Generated](images/ipfs-cid.png)

---

## 🧠 What I Learned

- How to install and use IPFS locally
- The concept of decentralized file storage
- How files are stored and retrieved via CID
- Pushing files to GitHub using Git and Personal Access Token

---

## 📁 GitHub Repository

🔗 [https://github.com/Sem1-LuckyLongre/blockchain-assignments](https://github.com/Sem1-LuckyLongre/blockchain-assignments)

---

## ✅ Conclusion

This assignment helped me understand the power of decentralized storage through IPFS. I successfully uploaded a file, got the CID, and shared it via GitHub for academic review.
