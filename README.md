# Software intalls for CIS-1090 and CIS-2031

Instructions and settings for installing VSCode, Git client, and Node.js with resistributable C++ compiler

## Background

These instructions were developed on a clean install Windows 10 VM. All installation steps were completed as an admin user, all verification steps were performed as a non-admin user.

## Installation

The following files were downloaded and copied to the desktop:

* https://github.com/git-for-windows/git/releases/download/v2.37.1.windows.1/Git-2.37.1-64-bit.exe
* https://code.visualstudio.com/sha/download?build=stable&os=win32-x64
* https://nodejs.org/dist/v16.16.0/node-v16.16.0-x64.msi

![image](https://user-images.githubusercontent.com/1305026/182405189-cd971b35-4cfb-4448-bf42-b31b574ff740.png)


### Node.js

1. Doubleclick on the node installer to start the Node.js Setup Wizard.
1. Click next.
1. Accept the terms of the License Agreement, click next.
1. Use the default location, `C:\Program Files\nodejs\`. Click next.
1. Leave the features as default, click next:
  * ![image](https://user-images.githubusercontent.com/1305026/182405789-e744efbd-9d2f-4634-8583-eaa79cb8910e.png)
1. **Check the checbox "Automatically install the necessary tools...."**, click next:
  * ![image](https://user-images.githubusercontent.com/1305026/182406243-8a38f50a-a374-46b9-8070-838b9694b38f.png)
1. Click Install to begin the installation.
1. If prompted, allow Node.js to make changes to this device in the UAC popup by clicking yes.
1. Once this phase of the installation is successfull click finish:
  * ![image](https://user-images.githubusercontent.com/1305026/182406718-a142c2cc-7430-47a0-a1ae-5783a0097bd6.png)
1. A command prompt will appear to install additional tools. Press any key to continue, several times:
  * ![image](https://user-images.githubusercontent.com/1305026/182406948-74ef9157-7a61-4d0c-8c30-f67f34c0a558.png)
1. If prompted, allow Windows PowerShell to make changes to this device in the UAC popup by clicking yes.
1. Wait while additional tools install. This took 6 minutes on my VM, YMMV:
 * ![image](https://user-images.githubusercontent.com/1305026/182408924-97091705-7eed-409a-a350-7e4fd72be9b5.png)
1. Type ENTER to exit.


### Git

### VSCode

## Verification
