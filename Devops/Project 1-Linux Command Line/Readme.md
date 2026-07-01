# Project 1: Linux & Command Line Basics 🐧

## Objective

The objective of this project is to learn and practice fundamental Linux commands commonly used in DevOps environments. The project focuses on file management, directory navigation, log handling, and basic system operations using the command line.

---

## Mission Tasks Completed

### 1. Create Application Directories

```bash
mkdir -p app/logs
```

Created the `app` directory along with the `logs` subdirectory.

### 2. Create Configuration File

```bash
touch app/config.conf
```

Created an empty configuration file for the application.

### 3. Initialize Server Log

```bash
echo "Started" > app/logs/server.log
```

Added an initial startup message to the server log.

### 4. Verify Working Environment

```bash
pwd
ls -R app
```

Checked the current directory and displayed the complete application structure.

### 5. Backup Server Log

```bash
mv app/logs/server.log app/logs/server.bak
```

Renamed the log file to create a backup.

### 6. Audit File Information

```bash
ls -l app/config.conf
```

Viewed file permissions, ownership, size, and timestamps.

---

## Directory Structure

```text
Project-1-Linux-Command-Line/
├── README.md
├── commands.md
├── app/
│   ├── config.conf
│   └── logs/
│       └── server.bak
└── screenshots/
```

---

## Commands Learned

- `pwd` — Print working directory
- `ls` — List files and directories
- `mkdir` — Create directories
- `touch` — Create files
- `echo` — Write text output
- `cat` — Display file contents
- `mv` — Move or rename files
- `rm` — Remove files and directories
- `tail -f` — Monitor logs in real time

---

## Key Learnings

Through this project, I learned:

- Linux command-line fundamentals
- File and directory management
- Log file creation and monitoring
- Configuration file handling
- Safe usage of commands such as `rm` and `mv`
- The importance of verifying context using `pwd` before performing operations

---

## DevOps Mindset

> **Precision:** Know your `pwd` before you act.  
> **Visibility:** Use `tail -f` to monitor system activity.  
> **Safety:** Verify context before executing `rm`.  
> **Mindset:** GUI is for browsing. CLI is for building.

---

## Outcome

This project provided hands-on experience with Linux commands that form the foundation of modern DevOps workflows and system administration practices.