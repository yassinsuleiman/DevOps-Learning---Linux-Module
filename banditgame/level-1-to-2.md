# Bandit Level 1 → 2

## 🎯 Goal  
Find and read the file named `-` to obtain the Level 2 password.

## 🤔 Thought Process  
1. `ls` shows a file named `-`.  
2. `cat -` reads stdin, so use `cat ./-`.  
3. Retrieve and copy the password.  

## 🔧 Commands Used
```bash
ls
cat ./-
exit
