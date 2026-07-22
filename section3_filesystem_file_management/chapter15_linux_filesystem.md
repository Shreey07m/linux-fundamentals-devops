# Chapter 15: Linux File System

## What is a File System?
A file system organizes and manages files/directories on storage devices.  
Analogy: A library with sections (directories) and books (files).

## Everything is a File
- Text file → File
- Directory → File
- Keyboard, Mouse, Disk → Device files

Example:
```bash
ls /dev
```
Output: `sda`, `tty`, `null`, `random`

## Linux Directory Structure

Single-root hierarchy starting at  `/`.

### Key directories:

- `/` → Root

- `/home` → User directories

- `/root` → Root user’s home

- `/etc` → Config files

- `/var` → Logs, cache

- `/tmp` → Temporary files

- `/usr` → Installed software

- `/bin` → Essential commands

- `/sbin` → System admin commands

- `/dev` → Device files

- `/proc` → Kernel/process info

- `/boot` → Bootloader + kernel

- `/opt` → Optional software

- `/media` → Auto-mounted drives

- `/mnt` → Manual mount point