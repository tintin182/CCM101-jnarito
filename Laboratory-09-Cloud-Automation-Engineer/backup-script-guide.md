# ⚙️ Backup Script Guide

## 1. Backup Script

The `backup.sh` script creates a compressed backup of the `app-data` folder and saves it in the `backups` folder.

```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

# Create the backup directory if it does not exist
mkdir -p $BACKUP_DIR

# Compress the source directory into a tarball (.tar.gz)
tar -czf $BACKUP_DIR/backup_$TIMESTAMP.tar.gz $SOURCE_DIR

echo "Backup completed successfully at $TIMESTAMP!"
```

## 2. File Permissions

The command `chmod +x backup.sh` gives the script permission to run as a program. After setting this permission, I can execute the script using `./backup.sh`.

## 3. Cron Job Schedule

The following cron expression schedules the backup script to run every day at 2:00 AM.

```cron
0 2 * * * /root/backup.sh
```

### Cron Field Breakdown

| Field | Value | Meaning |
|---|---|---|
| Minute | `0` | At minute zero |
| Hour | `2` | At 2:00 AM |
| Day of Month | `*` | Every day of the month |
| Month | `*` | Every month |
| Day of Week | `*` | Every day of the week |

## 4. Summary

The backup script automates the process of compressing application data into a timestamped archive. The executable permission allows the script to run, while the cron job schedules it to run automatically every night at 2:00 AM.
