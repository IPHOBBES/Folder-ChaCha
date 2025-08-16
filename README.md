# >_ Folder ChaCha

![Folder ChaCha Icon](./folderchacha-icon.png)

A lightweight macOS AppleScript app that continuously monitors a folder and moves or copies all its contents to another location. Fast, simple, and visually clean — with square-style setup dialogs and optional notifications.

---

## Why Folder ChaCha?

Some folders just won’t stay tidy — Downloads, AirDrop, work-in-progress projects.  
Manually cleaning them is boring. Automating them is better.  

>_ Folder ChaCha lets you pick a source, pick a destination, choose **MOVE** or **COPY**, and then dances files away every few seconds. Optional notifications keep you informed, or you can let it run silently in the background.

---

## Features

- Move or copy all top-level items from a source folder to a destination folder  
- Supports nested folders and `.folder` packages  
- Continuous monitoring with a configurable interval (default 5 seconds)  
- Optional notifications for moved/copied files  
- Clean, square dialogs for:  
  - Action selection (MOVE / COPY)  
  - Source folder selection  
  - Destination folder selection  
  - Notification preference  
- Safe for user-space folders only (no system folder access by default)  

---

## Installation

1. Download the latest release zip and unzip `FolderChaCha.app`.  
2. Open the app (may require approval in **System Preferences → Security & Privacy**).  
3. For full functionality, grant **Full Disk Access** under Privacy settings (optional).  

---

## Usage

- Click **START** in the welcome dialog  
- Choose **MOVE** or **COPY**  
- Select your **Source Folder**  
- Select your **Destination Folder**  
- Choose **SHOW ALERTS** or **NO ALERTS**  
- The app will now monitor your source folder every 5 seconds and move/copy new items automatically  

---

## License

MIT License

---
