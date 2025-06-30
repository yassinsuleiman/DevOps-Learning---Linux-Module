# Bandit Level 10 → 11

## 🎯 Goal  
Decode a ROT13-encrypted string in `data.txt`.

## 🤔 Thought Process  
I used `tr` with the ROT13 mapping to translate letters and reveal the password.

## 🔧 Commands Used
```bash
tr 'A-Za-z' 'N-ZA-Mn-za-m' < data.txt
exit
