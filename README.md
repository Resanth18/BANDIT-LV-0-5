# BANDIT LV 1-5
**Over The Wire / Bandit level 1-5**
*Small & Simple walkthrough for beginners*


## Level 0 → Level 1
### 🎯 Objective:
- Connect to the Bandit server using SSH.
- Find the password for Level 1.

### 🔧 Commands Used:
- `ssh bandit0@bandit.labs.overthewire.org -p 2220` → Connects to the server.
- `ls` → Lists the files in the directory.
- `cat readme` → Displays the contents of the `readme` file.

### 🚀 Steps:
1. Open a terminal and connect using SSH:
   ```bash
   ssh bandit0@bandit.labs.overthewire.org -p 2220
2. Enter the password: `bandit0`
3. List the file using:
   ```bash
    ls
6. Now there will be a file listed in the name of *README*
7. Open that file by using:
8. ```bash
   cat readme
10. The password for next level (Level 1) is displayed there `ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If`

### 📸 Screenshot:
![Level 0 access](https://github.com/user-attachments/assets/67fc15d9-c4a9-4e21-b73d-537e218c6f66)
![Level 0 PASS](https://github.com/user-attachments/assets/ce28fbbd-88f0-49c5-8d53-261d3e822223)


## Level 1 → Level 2

### 🎯 Objective:
- Locate the hidden password file and read its content.

### 🔧 Commands Used:
- `ls` → Lists the files in the current directory.
- `cat ./-` → Reads a file named `-` (special character).

### 🚀 Steps:
1. SSH into Level 1:
   ```bash
   ssh bandit1@bandit.labs.overthewire.org -p 2220
2. Enter password found in *Level 0* : `ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If`
3. List the files:
   ```bash
   ls
4. You'll see a file named "-". Since - is a special character in Linux, use:
   ```bash
   cat ./-
5. This tells Linux to read the file named *-*
6. The password for Level 2 is displayed now: `263JGJPfgU6LtdEvgfWU1XP5yac29mFx`
