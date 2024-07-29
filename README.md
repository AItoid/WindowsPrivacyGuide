### win10-privacy-guide
The ultimate guide to anonymizing Windows as much as possible.
This guide will cover everything you need to know in a simple matter for anonymizing, de-bloating, and optimizing the operating-system Windows 10 as much as possible.
Newer Windows OS' such as 10 & 11 have many unnecessary programs and files, as well as many options that spy on you by default, as well as collecting all of your information.
WindowsPrivacyGuide will respect your time, and will enlighten you in this compiled guide of how to take back your privacy when using the Windows OS.
Do keep in mind that this guide primarily targets Windows 10 due to it not being in the spotlight as much, as well as it being preferred for privacy-modifications and all around convenience.
This guide will be in order from what you should do first, to what you should do last. Photos will be included for those that would like precise instructions that are easy-to-follow.

### Chapters
1. Boot Installation & Configuration
2. Modifying Various Settings & Uninstalling Basic Apps
3. Useful Tools List
4. Useful Scripts List
5. Removing Microsoft Edge
6. Uninstalling Standard Apps With Tools
7. Permanently Disabling Windows Updates
8. Disabling Windows Firewall
9. Securely Deleting Files
10. Removing Metadata From Photos
11. Installing NVIDIA drivers without bloatware

> [!WARNING]
> Please keep in mind I am NOT responsible for any issues that occurs with your computer. By applying any of these methods, you agree to take full responsibility in the instance of any issues occurring on your device. It is recommended to create a system-restore-point in the event of a notable issue.

> [!CAUTION]
> Some options in Windows may refuse to work after applying some scripts, and will just close the settings window due to instability, or fail to load entirely. The rest of Windows will work as intended though. For those who play games, this will generally NOT cause any issues with games you may play.

> [!TIP]
> While you can disable a lot of Windows bloatware, spyware, and actions manually, it's more efficient to just use the scripts that are presented below, as well as the uninstaller to enhance the privacy of your Windows 10 build quicker.

Chapter 1. Boot Installation & Configuration
------

Let's start from the complete beginning of the installation. This guide assumes you are already aware of how to install the Windows 10 OS. I will not be explaining how to install the OS, but rather showing you what to disable on installation before you're prompted to the desktop. Firstly, it's important for you to NOT enable WiFi just yet! If you have an Ethernet plugged in, please disable it before continuing. Once your internet-connection is disabled, select the 'I don't have internet.' option, so you don't have to sign in. Following this path will give you what's called a local account, or an offline account. Proceed with installation, making sure Cortana is NOT enabled as well as disabling all checkboxes, and after, you should be able to proceed with installation and be prompted onto your desktop momentarily.

#### Photos
![photo1](https://i.imgur.com/aXnl9W0.png)
![photo2](https://i.imgur.com/YMQqBXl.png)
![photo3](https://i.imgur.com/1uy8jSi.png)

Chapter 2. Modifying Various Settings & Uninstalling Basic Apps
------

In the Windows 10 settings, there is various options we should modify / disable for our privacy. To open settings, press the Windows key, and select the gear icon in the bottom left. After that, I recommend going through each tab and disabling as much as possible that you deem a privacy threat / spyware. Starting in 'Updates & Security' and working our way up, we will click into the corresponding tab below and follow the sub-section on the side.

#### Updates & Security
- **Windows Update** > Advanced options > Disable everything in here and pause updates for as long as you can in the dropdown.
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

#### System
- **Optional features** > Uninstall applications such as Notepad or any common program for Windows.

Chapter 3. Useful Tools List
------

- https://exifcleaner.com/ (Clean meta-data from images)
- https://www.fileshredder.org/index.php (Permanently remove files securely)
- https://www.oo-software.com/en/shutup10 (Disable various spyware settings)
- https://www.majorgeeks.com/files/details/nsudo.html (Advaned system-management tool for full-privilege access to files)
- https://www.hibitsoft.ir/Uninstaller.html (Advanced program uninstaller & system cleaner)
- https://mpc-hc.org/ (Open-source video-player)
- https://www.irfanview.com/ (Spyware-free photo-viewer)
- https://www.techpowerup.com/download/techpowerup-nvcleanstall/ (Utility to install NVIDIA display-driver without additional spyware)
- https://heldercorreia.bitbucket.io/speedcrunch/ (Open-source calculator)
- https://notepad-plus-plus.org/ (Open-source notepad software)
- https://www.mozilla.org/en-US/firefox/ (Open-source browser for privacy)
- https://www.torproject.org/download/ (Open-source browser for anonymity & privacy)
- https://mullvad.net/en (Open-source VPN that doesn't collect logs)
- https://windscribe.com/ (Open-source VPN that doesn't collect logs)

Chapter 4. Useful Scripts List
------

- https://github.com/Sycnex/Windows10Debloater (Easy-to-use GUI script for removing bloatware)
- https://github.com/PrivacyIsFreedom/Windows (Various scripts for disabling Windows 10 spyware & features)
- https://privacy.sexy/ (Various scripts for making Windows 10 more private)

Chapter 5. Removing Microsoft Edge
------

Deleting the directory & files that Microsoft Edge (msedge.exe) are in is quite easy, but you must keep in mind that they may come back after some updates. I personally haven't had Microsoft Edge come back after an update or reboot, but some people say that it may come back if a new update is installed on your device.

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

In this section, we are primarily focused on using the HiBit Uninstaller application, which is listed in chapter 3. This tool is useful for uninstalling a variety of program-types, as well as cleaning up the system. Here is a photo of what the application looks like. It's the portable version as you can see, so it's not in our program-list.

#### Photos
![photo4](https://i.imgur.com/joHHOwk.png)
![photo5](https://i.imgur.com/dVPbZmP.png)

The options we are interested in are Tools > Windows Store Apps Manager / Program Components Manager. You may also like to use some of the other tools in this dropdown such as Registry Cleaner, Junk Files Cleaner, Empty Folder Cleaner, Shortcuts Fixer, and even a File Shredder built into it. I don't recommend this file-shredder though, but rather one that's added to the list of actions when you right-click a file. Be sure to remove any left-over native Microsoft applications such as Paint, Notepad, Calculator, Solitaire, Xbox, Phone, etc, etc. Uninstalling some of these applications may seem like a waste of time, but at the end of the day, we're here to modify Windows 10 to the extreme, not just disable a few functions.

Chapter 7. Permanently Disabling Windows Updates
------

Please make sure you have the application NSudo installed, which is listed in chapter 3's tool-list, and follow the steps below to disable Windows 10 updates.
1. Select TrustedInstaller in the dropdown
2. Select Enable All Privileges checkbox
3. Insert text taskschd.msc
4. Select Run
5. Expand Task Scheduler Library > Microsoft > Windows
6. Select UpdateOrchestrator near the bottom
7. Disable all triggers in the listbox by right clicking them, and selecting Disable
8. Select WindowsUpdate below UpdateOrchestrator and expand
9. Right click Scheduled Start Properties, and select Disable
10. Restart the OS to ensure modifications take place

#### Photos
![photo10](https://i.imgur.com/RHMklZL.png)
![photo11](https://i.imgur.com/6OlvGBE.png)
![photo12](https://i.imgur.com/Ld9LjpV.png)

Chapter 8. Disabling Windows Firewall
------

Disabling the Windows Firewall is easy! Follow the steps below to disable it very quickly.
1. Open Control Panel
2. Type 'Firewall' into the search-box in the top-right corner
3. Select Windows Defender Firewall
4. Select Turn Windows Defender Firewall on or off
5. Select Turn off for both radio-buttons.

#### Photos
![photo6](https://i.imgur.com/sh0VBad.png)

Chapter 9. Securely Deleting Files
------

In chapter 3, I present you with a link to a file-shredder installer. The file-shredder is very convenient, and easy-to-use. After installing it with the link presented in chapter 3, please follow the steps below to shred any file or directory easily.
1. Right click the file
2. Select File Shredder
3. Select Secure delete files
4. Press OK

#### Photos
![photo7](https://i.imgur.com/WIUZa3a.png)

Now the files will never be able to be recovered!

Chapter 10. Removing Metadata From Photos
------

In chapter 3 you will find a link to a program called ExifCleaner. This tool is an easy-to-use program for removing meta-data from images. Meta-data is information associated with an image that may be used to identify you.
Follow the steps below to remove meta-data from an image with ExifCleaner.
1. Drop a file onto ExifCleaner / select a file in File and press Open

#### Photos
![photo8](https://i.imgur.com/2lqpo23.png)

Chapter 11. Installing NVIDIA drivers without bloatware
------

In chapter 3, you can find the link to the program called NVCleanstall. This is a program that allows you to install your NVIDIA display-driver without the additional telemetry / spyware. Be sure to uninstall your graphics-card driver prior to using this software to ensure no issues occur. The program is very straight-forward to use, and all you have to do is follow a few steps, and you will have your display-driver without the additional spyware. Please follow the steps below to install your driver!
1. Select Install best driver for my hardware radio-button
2. Select Next
3. Select checkboxes PhysX, and HD Audio via HDMI.
4. Select Next
5. Now just keep accepting until the NVIDIA installer says success!

> [!NOTE]
> If you are on a laptop, be sure to also select the checkbox Optimus, and Microsoft Visual C 2017 Runtimes if that's not already installed.

#### Photos
![photo9](https://i.imgur.com/mVWbVxU.png)
