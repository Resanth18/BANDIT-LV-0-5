# BANDIT-LV-1-5
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
3. List the file using: `ls`
4. Now there will be a file listed in the name of *README*
5. Open that file by using: `cat readme`
6. The password for next level (Level 1) is displayed there `ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If`
