# Software intalls for CIS-1090 and CIS-2031

Instructions and settings for installing VS Code, Git client, and Node.js with resistributable C++ compiler

## Background

These instructions were developed on a clean install Windows 10 VM. All installation steps were completed as an admin user, all verification steps were performed as a non-admin user.

## Installation

The following files were downloaded and copied to the desktop:

* https://github.com/git-for-windows/git/releases/download/v2.37.1.windows.1/Git-2.37.1-64-bit.exe
* https://code.visualstudio.com/sha/download?build=stable&os=win32-x64
* https://nodejs.org/dist/v16.16.0/node-v16.16.0-x64.msi

### Git

**TLDR: Install Git client with all defaults**

1. Double click on the Git installer
1. If prompted, allow Git for Windows to make changes to this device in the UAC popup by clicking yes.
1. Click next.
1. Use all the defaults, just keep clicking next until you get to the Install button.
1. Click Install.
1. Uncheck "View Release Notes" and click Finish:

### VS Code

**TLDR: Install VS Code with all defaults**

1. Double click on the VS Code Installer.
1. If prompted, allow VS Code to make changes to this device in the UAC popup by clicking yes.
1. Accept the agreement and click next.
1. Use the default location, `C:\Program Files\Microsoft VS Code`. Click next.
1. Use all the defaults, just keep clicking next until you get to the Install button.
1. Click Install.
1. Uncheck "Launch Visual Studio Code" and click Finish:

### Node.js

**TLDR: Install Node.js BUT CHECK THE BOX TO INSTALL EXTRA TOOLS**

1. Doubleclick on the node installer to start the Node.js Setup Wizard.
1. Click next.
1. Accept the terms of the License Agreement, click next.
1. Use the default location, `C:\Program Files\nodejs\`. Click next.
1. Leave the features as default, click next:
1. **Check the checbox "Automatically install the necessary tools..."**, click next: ![image](https://user-images.githubusercontent.com/1305026/182406243-8a38f50a-a374-46b9-8070-838b9694b38f.png)
1. Click Install to begin the installation.
1. If prompted, allow Node.js to make changes to this device in the UAC popup by clicking yes.
1. Once this phase of the installation is successfull click finish:
1. A command prompt will appear to install additional tools. Press any key to continue, several times:
1. If prompted, allow Windows PowerShell to make changes to this device in the UAC popup by clicking yes.
1. Wait while additional tools install. This took 6 minutes on my VM, YMMV:
1. Type ENTER to exit.



## Verification

Two local accounts, "CPP Student" and "Javascript Student" were created with the "Standard User" account type.

### CIS-1090

1. Login as Javascript Student
2. Start VS Code
3. Choose the "Clone Git Repository" option: <br><img width="300" alt="image" src="https://user-images.githubusercontent.com/1305026/182420096-e326aeab-59de-46bf-815e-b213e2577345.png">
5. Enter `https://github.com/CU-CIS-1090-PSC/verification.git` in the box at the top, press enter.
6. Choose the `CIS-1090` folder on your USB drive, and click Select Repository Location"
7. Open the cloned repository: <br><img width="300" alt="image" src="https://user-images.githubusercontent.com/1305026/182420539-481e6427-4f16-4f20-ab21-032917b80ca6.png">
8. Show "NPM Scripts" in the editor window: <br><img width="300" alt="image" src="https://user-images.githubusercontent.com/1305026/182421010-85fa247e-a6d3-45f8-87a9-858b78135f3e.png">
9. Open the items under "NPM Scripts" and click the "Run Arrow":<br><img width="300" alt="image" src="https://user-images.githubusercontent.com/1305026/182421402-93aa9812-6d8c-4eb5-b37d-d3a41b110ac1.png">
10. Expect the following terminal output:<br><img width="300" alt="image" src="https://user-images.githubusercontent.com/1305026/182421653-b0c55a08-b389-4758-a35c-fea430b46434.png">



### CIS-2031
