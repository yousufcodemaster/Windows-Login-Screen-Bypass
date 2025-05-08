# Windows-Login-Screen-Bypass
Windows-Login-Screen-Bypass without any password reset or getting logged out of any app, especially WhatsApp.


# Windows Login Screen Bypass and App Execution (Single Process)
This repository demonstrates an advanced technique to bypass the Windows login screen and run apps directly without logging in. It also explores methods for hiding multiple processes and displaying them as a single process in Task Manager.

## Overview
This method works by:
1. **Bypassing the Windows login screen** using **Command Prompt (CMD)** without needing to log in.
2. Running **user applications** after bypassing the login.
3. Techniques for hiding multiple processes and showing only a **single process** in Task Manager.

The goal is to make Microsoft work harder and improve the security of the Windows operating system.

---

## Process Bypass Overview:
1. **Boot from USB**:
   - Insert any **bootable USB** with a file manager.
   - Browse to the `C:\Windows\System32` folder.
2. **Replace `sethc.exe` with `cmd.exe`**:
   - This allows you to open **Command Prompt (CMD)** directly from the login screen by pressing the **Shift key 5 times**.
   
3. **Access User Applications**:
   - Once CMD is opened, you can run applications like **WhatsApp**, **Chrome**, etc., without logging in.
   
---

## Key Features:
- **Access User Apps** without logging in.
- **Hide multiple processes** and display only one process in **Task Manager** (still untested, requires further experimentation).
- **Single Process** execution for apps that support it, such as Chrome using the `--single-process` flag.
- Potential for using **process injection** to mask multiple processes into a single process.

---

## How to Use:
1. **Create Bootable USB**:
   - Use any bootable OS like **Windows installation media** or **Linux** with file manager.
2. **Replace `sethc.exe` with `cmd.exe`** in `System32`.
3. **Restart the computer** and press **Shift key 5 times** to open the Command Prompt.
4. **Run your desired applications** directly from CMD.

## Additional Notes:
- Applications that are **already single-process** (like WhatsApp or Chrome with flags) will work without any extra configuration.
- **Process hiding techniques** can be used to merge multiple processes into a single process, but this still requires further testing and improvements.

---

## Contribution:
If you have any ideas for **improvements** or **better techniques**, please feel free to **contact me**. I am open to any suggestions and collaboration.

If you decide to **repost** this technique or use it in your work, please make sure to **credit me** as the original author.

---

## Disclaimer:
This technique is shared for **educational purposes only**. **Use at your own risk**, and be aware that bypassing security measures can potentially harm the system. Always use responsibly and legally.

---

## License:
This project is licensed under the **MIT License**.
