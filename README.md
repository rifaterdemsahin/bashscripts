# Sample Bash Scripts

## Script 1: Hello World

This script prints "Hello, World!" to the terminal.

```bash
#!/bin/bash
echo "Hello, World!"
```

## Script 2: Backup Files

This script creates a backup of a specified directory.

```bash
#!/bin/bash

# Directory to backup
SOURCE_DIR="/path/to/source"

# Backup destination
DEST_DIR="/path/to/backup"

# Create backup
tar -czvf "$DEST_DIR/backup_$(date +%Y%m%d).tar.gz" "$SOURCE_DIR"
```

## Script 3: Disk Usage Report

This script generates a disk usage report for the home directory.

```bash
#!/bin/bash

# Disk usage report for home directory
du -sh /home/*
```

## Script 4: User Information

This script displays information about the current user.

```bash
#!/bin/bash

# Display current user information
echo "User: $(whoami)"
echo "Home Directory: $HOME"
echo "Shell: $SHELL"
```

## Script 5: System Update

This script updates the system packages (for Debian-based systems).

```bash
#!/bin/bash

# Update package list and upgrade all packages
sudo apt update && sudo apt upgrade -y
```
