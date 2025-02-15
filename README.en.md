Comment:

AfinaWindows uses public and official tools provided by Windows to optimize and repair the system. We believe that information and knowledge should be freely accessible to everyone. If you want to learn more about the commands and technologies used by this program, consult the official Microsoft documentation:

- [PowerShell](https://learn.microsoft.com/en-us/powershell/) - Advanced automation and system administration tool.
- [WMIC](https://learn.microsoft.com/en-us/windows/win32/wmisdk/wmi-start-page) - Command line interface for accessing system information.
- [DISM](https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/dism-supported-platforms) - Utility for managing and repairing operating system images.
- [SFC](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/sfc) - Tool to scan and repair protected system files.
- [CHKDSK](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/chkdsk) - Verification and repair of hard drives.
- [Defrag](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/defrag) - Disk optimizer and defragmenter.
- [Task Scheduler](https://learn.microsoft.com/en-us/windows/win32/taskschd/task-scheduler-start-page) - Automatic task scheduling in Windows.

# AfinaWindows

Developed by Iván Eduardo Chávez Ayub

**AfinaWindows** is a desktop application designed to optimize, repair and improve Windows performance through advanced maintenance, security and network commands. Its intuitive interface, built with PyQt6, makes it easy to access these tools.

![AfinaWindows icon](AfinaWindows.png)

# Download

[Click here to download the application](dist/AfinaWindows.exe)

## Main Features

- **System Maintenance:** Run DISM, SFC and CHKDSK commands to check and repair corrupted files.
- **Security:** Activate and reset Firewall settings and network options.
- **Advanced Optimization:** Improve system performance through memory and disk adjustments.
- **Network Commands:** Fix connection problems by resetting IP and Winsock.
- **Simplified graphical interface:** Organize commands into categories for ease of use.

## How to Use

1. **Run the application:**
   - Open **AfinaWindows.exe** with administrator privileges.
2. **Select a category:**
   - Maintenance, Security, Network, System Information, Advanced Optimization.
3. **Click on a command:**
   - It will run in a new CMD window.

## Screenshots

![App Capture](Capture.png)

## System Requirements

- **Operating System:** Windows 10 or higher.

## Development

- [PyQt6](https://pypi.org/project/PyQt6/): For the graphical interface.
- [subprocess](https://docs.python.org/3/library/subprocess.html): For executing commands in CMD.

## Contributions

If you want to contribute:

1. Fork the repository.
2. Make your improvements.
3. Send a pull request.

---

Send your comments or suggestions to [sellocasadenubes@gmail.com](mailto:sellocasadenubes@gmail.com).
