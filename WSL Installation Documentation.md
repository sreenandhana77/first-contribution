# WSL Installation Documentation

### Prerequisites:
 * You must be running Windows 10 version 2004 and higher (Build 19041 and higher) or Windows 11 to use the commands below. 

---

### The Standard Installation:

**Step-1:**
1. Open PowerShell as Administrator by clicking on "Run as Administrator".
2. Run the install command:
```
wsl --install
```
3. After the installation is done, **Restart** your computer.


**Step-2:**
After  restarting:
1. Make sure to set WSL 2 as the default version:
```
wsl --set-default-version 2
```
2. Run this command below:
```
wsl.exe --install -d Ubuntu
```
After the installation is done, you will need to create a user account and password for your newly installed Linux distribution.
> Author's note: For those who enjoy creating problems for themselves: If you type random gibberish when it asks for password creation, the installer will kindly insist that you prove you meant it by typing it again. Just press **Enter** if you want a fresh start.

