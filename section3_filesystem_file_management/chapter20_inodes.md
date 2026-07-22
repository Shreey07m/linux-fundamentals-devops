# Chapter 20: Inodes

## What is an Inode?
Data structure storing metadata:
- File size
- Owner
- Permissions
- Timestamps
- Disk block locations

⚠️ Does not store filename.

## Commands
- `ls -i` → Show inode number
Example:
```bash
123456 report.txt
```