# Bandit Level 5 → 6

## 🎯 Goal  
Locate the file owned by `bandit6` in `/var/lib/dpkg/info`.

## 🤔 Thought Process  
I narrowed `find` to that directory and filtered results by user and group, then read the only matching file to get the password.

## 🔧 Commands Used
```bash
find /var/lib/dpkg/info -user bandit6 -group bandit5 2>/dev/null
cat /var/lib/dpkg/info/<found-file>
exit
