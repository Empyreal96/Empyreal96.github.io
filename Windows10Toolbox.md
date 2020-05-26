# **Windows 10 Toolbox**	-	Home

#### Backstory:

I started this as a little Windows Update 'Switch' so that I could enable and disable it as and when I needed it, but then I got using W10 ARM64 on my Lumia 950XL, I would apply various tweaks to improve its responsiveness but only to have to re-flash a few days later due to my experimenting.. So I started to make a tool to let me change the settings I would change after a new install.

Now it has progressed to quite a large Toolbox! but I plan to add so much more!

Note: the code will not be pretty, its not very organized and has not comments on what commands do, but I will get round to refining the code, I live by "If it works it don't need fixing" 

#### What does this script use?

This is written is batch script entirely with Notepad++. Native Windows commands used to apply tweaks are:

- REG (To make changes to Windows Registry Values)
- SC (This is used to change Service States)
- Powershell (Used for the GetAppx Commands to remove Built in Apps)
- DISM (Used to repair Windows file stores and System files)
- SFC (Used to check integrity of System files)
- SCHTASKS (Used to remove scheduled tasks)
- WUSA (Used to Uninstall  Installed KB packages/updates)

###### Screen:

![](https://github.com/Empyreal96/win-10-services-toolbox/raw/master/Update%20Switch%20Screens/screen2.gif)



## Features:

###### Windows Update:

- Start and Stop Update Services
- Enable or Disable Automatic Driver Downloads
- Enable or Disable Automatic Maintenance

###### Windows Search & Cortana:

- Start or Stop Windows Search and Cortana Services
- Enable or Disable Immersive Search and Searching Online

###### Windows Spotlight:

- Enable or Disable parts or all of Windows Spotlight
- Backup Spotlight Wallpapers

###### Telemetry and User Diagnostics:

- Enable or Disable Telemetry Data Collection and Connected User Experience Service
- Remove Telemetry Scheduled Tasks

###### Windows Apps and Features:

- Remove or Re-install Default Built In MetroUI Apps
- Add or Remove Windows Optional Features
- DISM Scan and Repair as well as SFC Checks and fix

###### Explorer:

- Manage Transparency
- Context Menu Options
- Disable OneDrive

###### Advanced:

- Page File Settings
- Enable or Disable Built-in Administrator Account
- Reset Default Shell Folders and DPI

##### AND MUCH MORE!





