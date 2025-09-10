# Windows Useful Commands & Tips

A quick reference for handy Windows commands, shortcuts, and troubleshooting steps.  
(No fluff, just helpful stuff.)

---

## 🔹 Basic System Info
- `winver`  
  Shows your Windows version and build number.

- `systeminfo`  
  Displays detailed system information (uptime, OS version, hotfixes, memory, etc.).

- `hostname`  
  Shows your computer name.

- `driverquery`  
  Lists installed drivers.

---

## 🔹 File System & Navigation
- `dir`  
  List files in the current directory.

- `cd <path>`  
  Change directory.

- `tree`  
  Displays a folder structure in a tree format.

- `copy file1 file2`  
  Copy a file to another location.

- `xcopy source destination /E /H`  
  Copy folders including subdirectories.

- `robocopy source destination /MIR`  
  Powerful copy/mirror tool. Great for backups.

---

## 🔹 Disk & File Check
- `chkdsk C: /f /r`  
  Checks disk for errors and fixes them.

- `sfc /scannow`  
  Scans and repairs corrupted system files.

- `DISM /Online /Cleanup-Image /RestoreHealth`  
  Repairs Windows image and update issues.

---

## 🔹 Networking
- `ipconfig`  
  Displays current IP configuration.

- `ipconfig /all`  
  Shows detailed network adapter info.

- `ping example.com`  
  Test connectivity to a host.

- `tracert example.com`  
  Show the path packets take to a destination.

- `netstat -ano`  
  Shows active connections with process IDs.

---

## 🔹 Process & Task Management
- `tasklist`  
  Displays all running processes.

- `taskkill /PID <pid> /F`  
  Force-kill a process by PID.

- `taskkill /IM app.exe /F`  
  Kill a process by name.

---

## 🔹 User & Access
- `whoami`  
  Displays current logged-in user.

- `net user`  
  Lists user accounts.

- `net user <username> <password> /add`  
  Create a new user.

- `net localgroup administrators <username> /add`  
  Add a user to the Administrators group.

---

## 🔹 System Maintenance
- `cleanmgr`  
  Opens Disk Cleanup GUI.

- `msconfig`  
  Opens system configuration (boot, startup, services).

- `eventvwr`  
  Opens Event Viewer for logs.

- `services.msc`  
  Manage Windows services.

---

## 🔹 Fun & Hidden Gems
- `calc`  
  Opens the calculator.

- `mspaint`  
  Classic Paint app – nostalgia included.

- `notepad`  
  Quick text editor.

- `control`  
  Old-school Control Panel.

- `powershell`  
  Launches PowerShell (more powerful than cmd).

---

## 🚑 Quick Fix Checklist (When Windows misbehaves)
1. Run `sfc /scannow`
2. Run `DISM /RestoreHealth`
3. Check disk with `chkdsk`
4. Restart computer
5. Check Event Viewer
6. If still broken: consider restore point or backup

---

## ⚡ Keyboard Shortcuts You’ll Love
- `Win + E` → Open File Explorer  
- `Win + R` → Open Run dialog  
- `Win + X` → Quick admin menu  
- `Win + Shift + S` → Take a screenshot snip  
- `Ctrl + Shift + Esc` → Task Manager  
- `Alt + Tab` → Switch between open windows  

---

Happy commanding! 🚀
