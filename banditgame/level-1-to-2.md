# Bandit Level 1 → 2

## 🎯 Goal  
Find and read the file named `-` to obtain the Level 2 password.

## 🤔 Thought Process  
After logging in, I saw a file named `-`. Knowing `cat -` reads stdin, I prefixed it with `./` so the shell treated it as a filename, then read it to get the password.

## 🔧 Commands Used
```bash
ls
cat ./-
exit
