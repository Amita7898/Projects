# File Organiser

A simple and efficient desktop application to automatically organise files into folders based on their type or extension.  
Built with **Python** and packaged with **Tkinter** for a clean UI.

---

## Features
- Automatic Mode → Watches a directory continuously and sorts new files.  
- Manual Mode → Lets you categorise selected files on demand.  
- Progress Bar → Shows percentage while organising.  
- Undo Last Move → Reverts the last action.  
- Drag & Drop Support → Quickly drop files to sort.  
- Logging → Keeps track of all moves for easy reference.  

---

## How It Works
1. Choose a folder to monitor or select files manually.  
2. The app categorises files based on:
   - File extension (`.jpg`, `.pdf`, `.mp3`, etc.)  
   - Or partial folder/file name matching (in manual mode).  
3. Files are moved into organised subfolders automatically.  

---

## Getting Started

### Prerequisites
- Python 3.10+  
- Required libraries:  
  ```bash
  pip install watchdog tk
