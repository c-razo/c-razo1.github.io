---
layout: post
title: "Password Cracking and Encryption Project"
date: 2024-11-04
categories: cybersecurity projects
---
## Project Overview

In this project, I explored password cracking and encryption techniques using tools like John the Ripper and Hashcat. This involved creating and cracking a sample hashed password, understanding system resource limitations, and learning about effective password security.

### Step 1: Environment Setup

I set up my Kali Linux Debian VM on VMware Fusion, allocating 2 processor cores and 20 GB of storage. Below is a screenshot of the setup environment.

![Enviroment Setup](Enviroment-Setup.png)

### Step 2: Installing John the Ripper and Hashcat

After setting up the environment, I installed John the Ripper and Hashcat. Here’s the command and installation confirmation:

![Installation of Tools](Install-John-and-Hashcat.png)

### Step 3: Creating a Sample Password Hash

I generated a hashed password and stored it in a file named `hash.txt`. This hash was created with SHA-512, providing a strong encryption method.

![Password Hash Creation](Create-Sample-Password-Hash.png)

### Step 4: Cracking the Password with John the Ripper

I used John the Ripper to crack the password hash. Here is the successful result showing the cracked password:

![John the Ripper Cracking Result](John-3.png)

### Project Outcome and Learnings

This project demonstrated the importance of strong passwords and the effectiveness of various password-cracking tools. I also encountered resource limitations in my VM, which helped me understand the importance of hardware in security testing.

![Hashcat Limitations on Kali Linux VM via VMWare Fusion for MacOS](Hashcat2.png)
