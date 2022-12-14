# Visual-Studio-2022-Setup
Setup wizard for Microsoft Visual Studio 2022.
# How to install
Copy the following commands:
```
git clone https://github.com/JoseErnestoOnGithub/Visual-Studio-2022-Setup.git
cd C:\Users\Ângelo
mkdir Downloaded-VisualStudio
cd C:\Users\Ângelo\Visual-Studio-2022-Setup
move VisualStudioSetup.exe C:\Users\Ângelo\Downloaded-VisualStudio
start VisualStudioSetup.exe
Select necessary components.
Start installing.
```
Visual Studio 2022 will be successfully installed on your device!
# System Requirements

    ARM64 processor or 1.8 GHz or faster x64 processor (quad-core or better recommended). ARM32 processors are not supported.
    Minimum of 4 GB of RAM. Many factors impact resources used; we recommend 16 GB RAM for typical professional solutions.
    Windows 365: Minimum 2 vCPU and 8 GB RAM. 4 vCPU and 16 GB of RAM recommended.
    Hard disk space: Minimum of 850 MB up to 210 GB of available space, depending on features installed; typical installations require 20-50 GB of free space. We recommend installing Windows and Visual Studio on a solid-state drive (SSD) to increase performance.
    Video card that supports a minimum display resolution of WXGA (1366 by 768); Visual Studio will work best at a resolution of 1920 by 1080 or higher.
        Minimum resolution assumes zoom, DPI settings, and text scaling are set at 100%. If not set to 100%, minimum resolution should be scaled accordingly. For example, if you set the Windows display ‘Scale and layout’ setting on your Surface Book, which has a 3000x2000 physical display, to 200%, then Visual Studio would see a logical screen resolution of 1500x1000, meeting the minimum 1366x768 requirement.
        

Source: https://learn.microsoft.com/en-us/visualstudio/releases/2022/system-requirements

# Known issues
Computers that do not meet the minimum system requirements (For example, 32-bit computers, Windows in Arm64 technology, etc.) will prevent Visual Studio 2022 from installing.
There are a lot a bugs that Microsoft needs to fix. For a possible solution, follow these steps:
Step 1: Send a problem report to Microsoft. Open the link, https://aka.ms/WIPFeedbackHub, and ask a new question. Wait for other people to respond, and they will send a message to you that Microsoft can fix.
Step 2: If you're having trouble signing in into your Microsoft account, try using this javascript function, which will solve the problem. Open the console and copy the code: DiagnoseErrors(), then paste it into the console. Now, the troubleshooter will open. The troubleshooter will check for network problems. Once the problems are being checked, if issues are found, the troubleshooter will fix this automatically.

**Happy coding!**
