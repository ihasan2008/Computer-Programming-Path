@ [Git]-[Bash]


# 🐧 Bash Commands Cheat Sheet (Command vs বাংলা ব্যাখ্যা)

---

## 📌 Basic Navigation
| Command | ব্যাখ্যা |
|--------|--------|
| pwd | বর্তমান directory (তুমি কোথায় আছো) দেখায় |
| ls | ফাইল ও ফোল্ডারের তালিকা দেখায় |
| ls -la | hidden file সহ বিস্তারিত list দেখায় |
| cd folder | নির্দিষ্ট folder এ ঢোকে |
| cd .. | আগের directory তে যায় |
| cd ~ | home directory তে যায় |
| clear | terminal পরিষ্কার করে |

---

## 📌 File & Directory Management
| Command | ব্যাখ্যা |
|--------|--------|
| touch file.txt | নতুন ফাইল তৈরি করে |
| mkdir folder | নতুন folder তৈরি করে |
| mkdir -p a/b/c | nested folder তৈরি করে |
| rm file.txt | ফাইল delete করে |
| rm -r folder | folder delete করে |
| rm -rf folder | force delete (সতর্কতা ⚠️) |
| cp file1 file2 | file copy করে |
| cp -r dir1 dir2 | folder copy করে |
| mv old new | rename বা move করে |

---

## 📌 File Viewing
| Command | ব্যাখ্যা |
|--------|--------|
| cat file.txt | পুরো file দেখায় |
| less file.txt | scroll করে পড়া যায় |
| more file.txt | page আকারে দেখায় |
| head file.txt | প্রথম ১০ লাইন |
| tail file.txt | শেষ ১০ লাইন |
| tail -f file.txt | live log |

---

## 📌 Search & Filter
| Command | ব্যাখ্যা |
|--------|--------|
| grep "text" file | text খুঁজে |
| grep -i text file | case ignore করে |
| grep -r text dir | folder এর ভিতরে search |
| find . -name file | file খুঁজে |
| find . -type f | শুধু file খুঁজে |
| locate file | দ্রুত search |

---

## 📌 System Monitoring
| Command | ব্যাখ্যা |
|--------|--------|
| top | live process |
| htop | advanced monitor |
| df -h | disk usage |
| du -sh folder | folder size |
| free -h | RAM usage |
| uptime | system uptime |
| uname -a | system info |

---

## 📌 User & Permission
| Command | ব্যাখ্যা |
|--------|--------|
| whoami | current user |
| id | user info |
| chmod 755 file | permission change |
| chmod +x file | executable বানায় |
| chown user file | owner change |
| passwd | password change |

---

## 📌 Networking
| Command | ব্যাখ্যা |
|--------|--------|
| ping google.com | network test |
| ifconfig | IP address |
| ip a | IP details |
| netstat -tuln | open port |
| ss -tuln | modern port check |
| curl url | data fetch |
| wget url | file download |

---

## 📌 Package Management
| Command | ব্যাখ্যা |
|--------|--------|
| apt update | package list update |
| apt upgrade | update install |
| apt install pkg | install |
| apt remove pkg | remove |
| apt search pkg | search |

---

## 📌 Process Management
| Command | ব্যাখ্যা |
|--------|--------|
| ps | process list |
| ps aux | full process list |
| kill PID | process বন্ধ |
| kill -9 PID | force বন্ধ |
| bg | background |
| fg | foreground |
| jobs | background jobs |

---

## 📌 Text Processing
| Command | ব্যাখ্যা |
|--------|--------|
| awk '{print $1}' | প্রথম column print |
| sed 's/a/b/g' | text replace |
| sort file | sort |
| uniq | duplicate remove |
| wc -l file | line count |
| cut -d',' -f1 file | column cut |

---

## 📌 Bash Scripting
| Command | ব্যাখ্যা |
|--------|--------|
| echo "text" | print |
| read var | input নেয় |
| if [ condition ] | condition check |
| for i in list | loop |
| while | loop |

---

## 📌 Automation
| Command | ব্যাখ্যা |
|--------|--------|
| crontab -e | schedule task |
| history | command history |
| alias ll='ls -la' | shortcut |

---

## 📌 Disk Management
| Command | ব্যাখ্যা |
|--------|--------|
| lsblk | disk list |
| mount | drive connect |
| umount | disconnect |
| fdisk -l | partition info |
| df -h | disk usage |

---

## 📌 Security & Remote Access
| Command | ব্যাখ্যা |
|--------|--------|
| sudo command | admin access |
| ssh user@ip | remote login |
| scp file user@ip:/path | file transfer |
| chmod 600 key | secure permission |

---

## 📌 Advanced Commands
| Command | ব্যাখ্যা |
|--------|--------|
| xargs | input নিয়ে command run |
| tee file | output save |
| watch command | repeat run |
| nohup command & | background run |
| time command | execution time |

---

# 🚀 Tips
- man command → বিস্তারিত help  
- command --help → দ্রুত help  
- Practice = Mastery 🔥  