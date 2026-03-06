# File Organizer

Script that sorts files by type. Made it because my Downloads folder was a mess.

## What it does

Moves files into folders based on extension:
- Images (jpg, png, gif, etc.)
- Documents (pdf, docx, txt)
- Videos, Audio, Spreadsheets, Archives, Code
- Others (everything else)

## Usage
```bash
python3 file_organizer.py
```

Enter a directory path or press Enter for current folder. It asks for confirmation before moving anything.

## How it works

Uses `pathlib` and `shutil`. Reads files, checks extensions, creates category folders, moves files. Handles duplicates by adding `_1`, `_2`, etc.

Nothing fancy. Just saves time cleaning up folders.

## Requirements

Python 3.6+ (standard library only)
