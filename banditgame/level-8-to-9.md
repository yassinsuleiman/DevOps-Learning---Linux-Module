# Bandit Level 8 → 9

## 🎯 Goal  
Find the only line in `data.txt` that appears exactly once.

## 🤔 Thought Process  
I sorted the file and then used `uniq -u` to isolate the unique line, which contained the password.

## 🔧 Commands Used
```bash
sort data.txt | uniq -u
exit
