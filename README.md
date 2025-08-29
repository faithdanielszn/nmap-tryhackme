# nmap-tryhackme
walkthrough of the room on tryhackme
# TryHackMe — OhSINT Challenge Walkthrough

## My Understanding of OSINT
**Open-Source Intelligence (OSINT)** is the process of collecting publicly available data from sources like social media, websites, and documents to assess security risks.  
In cybersecurity, OSINT is crucial for uncovering vulnerabilities, tracking threats, and performing reconnaissance without engaging in illegal activities.

---

## Why I Chose OSINT
As an entry-level professional, OSINT was a natural fit because it’s:
- Practical and beginner-friendly  
- Built on **real-world applications**  
- Allows skill-building using **freely available resources**  

This makes it perfect for someone starting out in cybersecurity.

---

## Why the TryHackMe OhSINT Lab?
The **OhSINT room** on [TryHackMe](https://tryhackme.com/room/ohsint) is an excellent starting point because:
- It’s designed for **beginners**, with gradual difficulty increase.  
- Provides **hands-on experience** with real-world scenarios (e.g., extracting metadata from an image).  
- Helps build practical OSINT skills using accessible tools.  

---

## Taking on the Challenge
🔗 [Link to the TryHackMe OhSINT Room](https://tryhackme.com/room/ohsint)

### Understanding the Challenge
The first step was downloading the task file by clicking the **“Download Task Files”** button in Task 1.  
This gave me the image file required for investigation.

---

## OSINT Investigation: Revealing Hidden Insights
At first glance, the image appeared **ordinary**—no visible clues or hidden text.  
But OSINT teaches us to dig deeper! My first step: **extract metadata**.

---

### Understanding Metadata
Metadata = hidden data inside files. It can reveal:
- **Creation dates**
- **Software or device details**
- **GPS coordinates**
- **Author/copyright info**

This information is **gold** in OSINT investigations.

---

### Tools for Metadata Extraction
- **ExifTool** → Command-line utility for extracting metadata  
  ```bash
  exiftool image.jpg

