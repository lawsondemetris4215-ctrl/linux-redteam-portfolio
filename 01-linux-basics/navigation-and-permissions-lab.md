# Navigation & Permissions Lab

## Objective
Understand how to navigate the Linux filesystem and modify file permissions.

---

## 1. Navigating the File System

### Commands Used

pwd
ls
cd
ls -la

### What I Learned

- `pwd` shows my current directory.
- `ls` lists files.
- `ls -la` shows hidden files and permissions.
- `cd` changes directories.

---

## 2. Creating Files & Directories

### Commands Used

mkdir testfolder
cd testfolder
touch testfile.txt
ls -la

### What I Learned

- `mkdir` creates directories.
- `touch` creates empty files.
- Linux updates permissions automatically when files are created.

---

## 3. Understanding Permissions

### Commands Used

chmod 755 testfile.txt
ls -la

### Explanation

Permission format example:
-rwxr-xr-x

Breakdown:
- Owner: read, write, execute
- Group: read, execute
- Others: read, execute

755 means:
7 = read, write, execute
5 = read, execute
5 = read, execute

---

## 4. Changing Ownership

### Command Used

sudo chown user:user testfile.txt

### What I Learned

- `chown` changes file ownership.
- Ownership affects access control.
- Proper permissions are critical for system security.

---

## Security Reflection

Misconfigured permissions can:
- Allow unauthorized access
- Enable privilege escalation
- Expose sensitive data

Understanding permissions is foundational for both system administration and offensive security.
