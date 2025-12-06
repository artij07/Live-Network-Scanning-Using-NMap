# Live-Network-Scanning-Using-NMap
# Live Network Scanning Using Nmap

## 🎯 Objective
To perform a legal and ethical network scan on an authorized test website using Nmap and analyze open ports, services, and operating system.

## 🛠 Tools Used
- Nmap
- Kali Linux
- VirtualBox

## 🌐 Target
scanme.nmap.org (Official Nmap Test Server)

## ✅ Commands Used
nmap scanme.nmap.org  
nmap -sV scanme.nmap.org  
nmap -A scanme.nmap.org  

## 📊 Results
- Open Ports Found:
  - 22/tcp – SSH
  - 80/tcp – HTTP
  - 443/tcp – HTTPS
- Host Status: Alive
- Operating System: Linux (Ubuntu)

## ⚠️ Security Analysis
- Open SSH port can be targeted for brute-force attacks if not secured.
- HTTP traffic is not encrypted and vulnerable to sniffing.
- HTTPS provides encrypted and secure communication.

## 📚 Learning Outcome
- Learned practical network reconnaissance
- Understood port scanning and service detection
- Gained hands-on experience with Nmap on Kali Linux

## 👩‍💻 Author
Arti Sandip Jadhav  
Cybersecurity Student | CSE (IoT & CSBT)
