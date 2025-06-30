# Bandit Level 0 → 1

## 🎯 Goal  
SSH into the server as **bandit0** and read the `readme` file to get the password for Level 1.

## 🤔 Thought Process  
1. Note host, port (2220), username, password.  
2. Connect via `ssh`.  
3. `ls` to see `readme`.  
4. `cat readme` to reveal the password.  

## 🔧 Commands Used
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
exit
