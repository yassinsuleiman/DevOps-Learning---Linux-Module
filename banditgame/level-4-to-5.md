# Bandit Level 4 → 5

## 🎯 Goal  
Find the 1033-byte human-readable file in the current directory.

## 🤔 Thought Process  
I used `find` with `-size 1033c` to locate the file by exact byte size, then confirmed it was ASCII and read it with `cat`.

## 🔧 Commands Used
```bash
find . -type f -size 1033c
file ./<found-file>
cat ./<found-file>
exit
