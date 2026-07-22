# Chapter 21: Real DevOps Scenario, Hands-On Practice & Interview Questions

## Real DevOps Scenario
A Java application writes logs to: `/var/log/myapp/app.log`


### Common Tasks
- Monitor logs: `tail -f /var/log/myapp/app.log`

- Find error messages: `grep "ERROR" /var/log/myapp/app.log`

- Backup logs before troubleshooting: `cp /var/log/myapp/app.log ~/app.log.backup`

- Check disk usage: `du -sh /var/log/myapp`

👉 These are everyday tasks for DevOps engineers.

## Hands-On Practice

- Create a practice directory:

```bash
mkdir ~/linux-practice
cd ~/linux-practice
```
- Create nested folders:

```bash
mkdir -p projects/aws/logs
```
- Create files:

```bash
touch file1.txt file2.txt notes.md
```
- Copy and rename:

```bash
cp file1.txt backup.txt
mv backup.txt archive.txt
```
- View file details:

```bash
file archive.txt
ls -i
```
- Delete test files:

```bash
rm archive.txt
rm -r projects
```
- Explore:

1. `ls` :

- Meaning: List

- Purpose: Displays the files and  directories in the current directory.

Example: `ls`

Output: `file1.txt  notes.md  projects/`

2. `ls -la` :

- Meaning: List (long format + all files)

- Purpose: Shows detailed information about files, including hidden ones (those starting with `.`).

Example: `ls -la`

Output:
```bash
drwxr-xr-x  2 shreeya users 4096 Jul 22  Documents
-rw-r--r--  1 shreeya users  123 Jul 22  notes.md
-rw-r--r--  1 shreeya users  456 Jul 22  .bashrc
```

3. `ls -lh`:

- Meaning: List (long format + human-readable sizes)

- Purpose: Same as ls -l, but file sizes are shown in KB/MB/GB instead of raw bytes.

Example:`ls -lh`

Output:  
```bash
-rw-r--r--  1 shreeya users 1.2K Jul 22  notes.md
-rw-r--r--  1 shreeya users  15M Jul 22  backup.tar.gz
```

## Interview Questions
What is the Linux file system?

Why is everything treated as a file in Linux?

What is the difference between / and /root?

What is stored in /etc and /var?

Explain the difference between an absolute path and a relative path.

What does mkdir -p do?

What is the difference between cp and mv?

Why is tail -f commonly used by DevOps engineers?

What are hidden files, and how do you view them?

What is an inode? Does it store the filename?