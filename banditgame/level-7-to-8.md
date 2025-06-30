# Bandit Level 7 → 8

## 🎯 Goal  
Filter `data.txt` for the line containing “millionth.”

## 🤔 Thought Process  
I piped the file through `grep` to extract only the line with the target word, revealing the password.

## 🔧 Commands Used
```bash
grep "millionth" data.txt
exit
