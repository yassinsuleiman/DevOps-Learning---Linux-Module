## 🎯 Goal  
Reverse a hexdump in `data.txt` back into readable text.

## 🤔 Thought Process  
I applied `xxd -r` to reconstruct the binary, then output it to see the password.

## 🔧 Commands Used
```bash
xxd -r data.txt > decoded.bin
cat decoded.bin
exit
