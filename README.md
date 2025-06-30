# 🐧 DevOps Learning – Linux Module

Welcome to my Linux command-line journey.  
This repository captures the practical work I completed while studying Linux fundamentals and tackling the first 15 levels of the OverTheWire **Bandit** wargame.

**Focus:** learn by doing.  
I kept notes short, wrote small helper scripts, and bookmarked lessons learned instead of copying every slide.
*(Folders appear as I push content; some start empty and fill up as I revisit topics.)*

---

## 🧠 Skills & Topics Covered

| Category              | Highlights                                                          |
|-----------------------|---------------------------------------------------------------------|
| **CLI Basics**        | `pwd`, `ls`, `cd`, tab-completion                                   |
| **File Ops**          | `touch`, `cat`, `echo`, `mv`, `cp`, `rm`, hidden files              |
| **Directories**       | `mkdir`, `rmdir`, `rm -r`, handling spaces & special chars          |
| **Search & Inspect**  | `grep`, `find`, `du`, `file`, `strings`, `xxd`                      |
| **Permissions**       | `chmod` (numeric & symbolic), `chown`, `chgrp`                      |
| **Users & Groups**    | `useradd`, `usermod`, `passwd`, `/etc/passwd`, `groups`             |
| **Streams & Pipes**   | `>`, `>>`, `2>`, `|`, `/dev/null`                                   |
| **Environment**       | `$PATH`, `export`, aliases, `.zshrc` tweaks                         |
| **Encoding/Compression** | `base64`, `tr` (ROT13), `tar`, `gzip`, `bzip2`                  |
| **Remote Work**       | SSH keys, AWS EC2 practice box                                      |

---

## 🎮 Bandit Wargame Progress (0 → 15)

| Level | Core Concept        | Key Command / Tool                         |
|-------|---------------------|--------------------------------------------|
| 0     | SSH login           | `ssh`                                       |
| 1     | Read a file         | `cat`                                       |
| 2     | Hidden file         | `ls -a`                                     |
| 3     | Space in filename   | `cat "file name"`                           |
| 4     | Nested hidden path  | `cd ./inhere`                               |
| 5     | Find by ownership   | `find -user bandit6`                        |
| 6     | Find by size        | `find -size 1033c`                          |
| 7     | Find exec perms     | `find -executable`                          |
| 8     | String filtering    | `grep "millionth"`                          |
| 9     | Unique string       | `sort | uniq -u`                            |
| 10    | Base64 decode       | `base64 -d`                                 |
| 11    | ROT13               | `tr 'A-Za-z' 'N-ZA-Mn-za-m'`                |
| 12    | Hexdump reverse     | `xxd -r`                                    |
| 13    | Gzip archive        | `tar -xzf`                                  |
| 14    | SSH private key     | `ssh -i`                                    |
| 15    | Port knocking       | `nc`, port scan                             |

*Levels 16 + are on deck; each level’s write-up lives under `bandit/`.*

---

## ✨ Key Takeaways

1. **Terminal confidence skyrocketed.** I went from copy-pasting commands to *thinking* in the shell.  
2. **Problem solving > memorisation.** Bandit forced creativity with a limited toolkit.  
3. **Custom shell matters.** A clean ZSH + Powerlevel10k prompt + sensible aliases saves real time.  

---

## 🚀 Next Up

- Finish Bandit 16 – 20  
- Write Bash automation scripts for repetitive tasks  
- Container basics (Docker) → CI/CD → Cloud tooling  
