### WindowsPrivacyGuide
The ultimate guide for anonymizing Windows as much as possible.
This guide will cover everything you need to know in a simple matter for anonymizing, de-bloating, and optimizing the operating-system Windows 10 as much as possible.
Newer Windows OS' such as 10 & 11 have many unnecessary programs and files, as well as many options that spy on you by default, as well as collecting all of your information.
WindowsPrivacyGuide will respect your time, and will enlighten you in this compiled guide of how to take back your privacy when using the Windows OS.
Do keep in mind that this guide primarily targets Windows 10 due to it not being in the spotlight as much, as well as it being preferred for privacy and all around convenience.
This guide will be in order from what you should do first, to what you should do last. Photos will be included for those that would like precise instructions that are easy-to-follow.

### Chapters
1. Boot Installation & Configuration
2. Modifying Various Settings & Uninstalling Basic Apps
3. Useful Tools List
4. Useful Scripts List
5. Removing Microsoft Edge
6. Uninstalling Standard Apps With Tools (TODO)
7. Permanently Disabling Windows Updates (TODO)
8. Disabling Windows Firewall (TODO)
9. Securely Deleting Files (TODO)
10. Removing Metadata From Photos (TODO)
11. Installing NVIDIA drivers without bloatware (TODO)

> [!CAUTION]
> Please keep in mind I am NOT responsible for any issues that occurs with your computer. By applying any of these methods, you 100% agree to take full responsibility to any issues that occur on your device. It is recommended to create a restore-point in the event of a significant bug.

Chapter 1. Boot Installation & Configuration
------

Let's start from the complete beginning of the installation. This guide assumes you already aware of how to install the Windows 10 OS. I will not be explaining how to install Windows 10 OS, but rather, showing you what to disable on installation before you're prompted to the desktop. Firstly, it's important for you to NOT enable WiFi just yet! If you have an Ethernet plugged in, please disable it before continuing. Once your internet-connection is disabled, select the 'I don't have internet.' option, so you don't have to sign in. Following this path will give you what's called a local account, or an offline account. Proceed with installation, making sure Cortana is NOT enabled as well as disabling all checkboxes, and after, you should be able to proceed with installation and be prompted onto your desktop momentarily.

#### Photos
![photo1](https://i.imgur.com/aXnl9W0.png)
![photo2](https://i.imgur.com/YMQqBXl.png)
![photo3](https://i.imgur.com/1uy8jSi.png)

Chapter 2. Modifying Various Settings & Uninstalling Basic Apps
------

In the Windows 10 settings, there is various options we should modify / disable for our privacy. To open settings, press the Windows key, and select the gear icon in the bottom left. After that, I recommend going through each tab and disabling as much as possible that you deem a privacy threat / spyware. Starting in 'Updates & Security' and working our way up, we will click into the corresponding tab below and follow the sub-section below.

#### Updates & Security
- **Windows Update** > Advanced options > Disable everything in here and pause updates for as long as you can in the drop-down.
- **Troubleshoot** > Don't run any troubleshooters.
- **Find my device** > OFF.

#### Privacy
- **General** > Disable everything in here.
- **Speech** > Disable everything in here.
- **Inking** & typing personalizatio > Off.
- **Diagnostics** & feedback > Select Optional diagnostic data, and disable all the checkboxes, then select Never at the bottom.
- **Activity History** > Disable everything in here.
- **Location** > Set location for this device to off if it's enabled, and disable all checkboxes.
- **App diagnostics** > Disable everything in here.

#### Search
- **Permissions & History** > Set SafeSearch to off, and disable everything in here.

#### Gaming
- **Game Bar** > Disable game bar checkbox.
- **Game Mode** > Disable game mode checkbox.

#### Apps
- **Apps & features** > Uninstall all applications that you can from the large list that state they're from Microsoft.
> [!NOTE]
> Be sure to uninstall applications such as Paint & Calculator as well.

#### System
- **Optional features** > Uninstall applications such as Notepad or any common program for Windows.

Chapter 3. Useful Tools List
------

- https://exifcleaner.com/ (Clean meta-data from images)
- https://www.fileshredder.org/index.php (Permanently remove files securely)
- https://www.oo-software.com/en/shutup10 (Disable various spyware settings)
- https://www.majorgeeks.com/files/details/nsudo.html (Advaned system-management tool for full-privilege access to files)
- https://www.hibitsoft.ir/Uninstaller.html (Advanced program uninstaller & system cleaner)

Chapter 4. Useful Scripts List
------

- https://github.com/Sycnex/Windows10Debloater (Easy-to-use GUI script for removing bloatware)
- https://github.com/PrivacyIsFreedom/Windows (Various scripts for disabling Windows 10 spyware & features)

Chapter 5. Removing Microsoft Edge
------

Deleting the directoy & files that Microsoft Edge (msedge.exe) are in is quite easy, but you must keep in mind that they may come back after some updates. I personally haven't had Microsoft Edge come back after an update or reboot, but some people say that it may come back if a new update is installed on your device.

The steps to uninstalling Microsoft Edge is quite easy. Follow the steps below:
1. Open Task Manager (right click task-bar > Task Manager, or press CTRL + SHIFT + ESC)
2. Go to Details, and find the process msedge.exe, right click it, and select Open file location
3. At the top of File Explorer, you must select the folder right before the Edge one, so you're no longer inside the folder.
4. Now right click the msedge.exe processes' and select End task on all of them.
5. Finally, you can delete the folder that contains msedge.exe inside of it once the processes' are no longer running!
> [!NOTE]
> Alternatively, you may just go to the first tab, Processes, and find Microsoft Edge's process list and just end that, then delete the directory.

Chapter 6. Uninstalling Standard Apps With Tools
------

Test6

Chapter 7. Permanently Disabling Windows Updates
------

Test7

Chapter 8. Disabling Windows Firewall
------

Test8

Chapter 9. Securely Deleting Files
------

Test9

Chapter 10. Removing Metadata From Photos
------
Test10
