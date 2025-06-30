# Bandit Level 6 → 7

## 🎯 Goal  
Identify and execute the only file marked as executable.

## 🤔 Thought Process  
I used `find` with `-executable` to list executables, then ran the discovered file directly to display the password.

## 🔧 Commands Used
```bash
find . -type f -executable
./<found-file>
exit
