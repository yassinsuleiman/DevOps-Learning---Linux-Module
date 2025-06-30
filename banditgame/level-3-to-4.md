# Bandit Level 3 → 4

## 🎯 Goal  
Navigate into a hidden directory `inhere` and read its hidden file.

## 🤔 Thought Process  
I ran `ls -a` to reveal `inhere`, entered it, listed with `ls -a` again to see `.hidden`, and used `cat` to display the password inside.

## 🔧 Commands Used
```bash
ls -a
cd inhere
ls -a
cat .hidden
exit
