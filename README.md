# Getting Familiar with Linux & Scripting

This repository is part of the **Bugfreak Academy Cybersecurity Training**. It's a personal learning resource to get comfortable with Linux commands and beginner scripting tasks.

---

## How Much Has Been Understood So Far?

- ✅ Linux basics: file navigation, system info, user control  
- ✅ Useful networking commands  
- ✅ Understanding permissions and ownership  
- ✅ Learned to group commands by purpose  
- 🔜 Next: scripting real-world tasks (automation, logs, cleanup, etc.)

---

# 📦 Core Linux Commands (Grouped by Category)

<details>
<summary>📁 File and Directory Navigation</summary>

```bash
pwd                : Show current working directory
ls                 : List files in the current directory
cd foldername      : Change directory
mkdir foldername   : Create a new folder
rmdir foldername   : Remove an empty folder
touch filename.txt : Create an empty file
cp file1 file2     : Copy a file
mv old new         : Rename or move a file
rm file.txt        : Delete a file
clear              : Clear the terminal screen
```
</details>

<details>
<summary>📄 Viewing and Searching Files</summary>

```bash
cat file.txt         : Show file contents
less file.txt        : View large files
head -n 10 file.txt  : Show first 10 lines
tail -n 10 file.txt  : Show last 10 lines
grep "word" file     : Search for a word
find . -name "*.txt" : Find .txt files in folder
wc -l file.txt       : Count lines in file
file filename        : Check file type
stat filename        : View metadata
diff file1 file2     : Compare files
```
</details>

<details>
<summary>⚙️ System Basics</summary>

```bash
whoami     : Show your username
id         : Show UID, GID and groups
date       : Show current date/time
cal        : Show calendar
uptime     : Show how long system is on
df -h      : Show disk usage
free -h    : Show memory usage
top        : Live process viewer
uname -r   : Show kernel version
hostname   : Show machine name
```
</details>

<details>
<summary>🌐 Networking</summary>

```bash
ip a                  : Show IP addresses
ping google.com       : Test internet connection
curl http://...       : Fetch a webpage
wget http://...       : Download a file
netstat -tuln         : Show open ports
nslookup domain.com   : DNS info
dig domain.com        : Detailed DNS info
traceroute domain.com : Route to server
host domain.com       : Resolve host
whois domain.com      : Domain registration info
```
</details>

<details>
<summary>🔐 Permissions & Users</summary>

```bash
chmod 755 file        : Change file permissions
chown user:group file : Change owner
sudo command          : Run as root
adduser username      : Add new user
passwd username       : Set password
groups username       : Show user groups
su -                  : Switch to root
who                   : Who is logged in
last                  : Login history
history               : Command history
```
</details>

<details>
<summary>🔧 Useful Extras</summary>

```bash
man ls              : Manual page for command
alias ll='ls -l'    : Create alias
uptime -p           : Pretty uptime
ps aux              : List processes
kill PID            : Kill process
xargs               : Chain command inputs
tee file.txt        : Save and display output
sleep 5             : Pause script
yes                 : Print repeated string
hostnamectl         : Manage hostname
reboot              : Restart system
shutdown now        : Power off
df -Th              : Disk usage + type
lsb_release -a      : Distro info
env                 : Show environment vars
export VAR=value    : Set environment var
echo $VAR           : Print environment var
basename /path/file : Show filename
dirname /path/file  : Show directory path
tac file.txt        : Reverse `cat`
```
</details>
