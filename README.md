# Scripts Repository

This repository contains various utility scripts.

## cPanel to CWP Migration Script

`cpanel_importer.py` - A Python script to assist in migrating backups from cPanel to CWP (Control Web Panel).

### Usage

```bash
python3 cpanel_importer.py -path /path/to/backup
```

### Features

- Validates backup directory path
- Provides detailed logging
- Error handling and reporting
- Extensible structure for backup processing

### Requirements

- Python 3.x
