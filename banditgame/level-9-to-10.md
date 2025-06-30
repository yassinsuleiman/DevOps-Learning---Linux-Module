# Bandit Level 9 → 10

## 🎯 Goal  
Decode a Base64-encoded password stored in `data.txt`.

## 🤔 Thought Process  
I applied `base64 -d` to the file to decode it, then read the output directly.

## 🔧 Commands Used
```bash
base64 -d data.txt
exit
