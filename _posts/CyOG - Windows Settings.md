This will cover the:
1. **Windows Settings App Settings**


## Table Of Contents
1. [[#Windows Settings App Settings]]
  - [[#System Settings]]
    - [[#1. Display Settings.]]
    - [[#2. Sound Settings]]
    - [[#3. Notifications Settings]]
    - [[#4. Power and Battery]]
    - [[#5. Storage Settings]]
    - [[#6. Nearby Sharing (Or Shared Experiences)]]
    - [[#7. Multitasking]]
    - [[#8. Clipboard History]]
    - [[#9. Remote Desktop]]
  - [[#Bluetooth & Devices Settings]]
    - [[#1. Bluetooth]]
    - [[#2. Printers & Scanners]]
    - [[#3. Mouse]]
  - [[#Personalization Settings]]
    - [[#1. Background]]
    - [[#2. Colours or Colors]]
    - [[#3. Dynamic Lighting]]
    - [[#4. Start]]
    - [[#5. Taskbar]]
  - [[#Apps Settings]]
    - [[#1. Installed Apps]]
    - [[#2. Startup Apps]]
    - [[#3. Offline Maps]]
  - [[#Gaming Settings]]
    - [[#1. Game Mode]]
    - [[#2. Xbox Game Bar]]
    - [[#3. Captures]]
  - [[#Privacy and Security Settings]]
    - [[#1. Main Privacy]]
      - [[#1. Find My Device]]
      - [[#2. Device Encryption]]
      - [[#3. Windows Permissons]]
    - [[#2. App Permissons]]
  - [[#Windows Update]]
    - [[#1. Windows Update]]
    - [[#2. Delivery Optimizations]]
  - [[#Accessibility Settings]]
    - [[#1. Visual Effects]]
    - [[#2. Narrator]]
  - [[#Summary Of Windows Settings]]

# Windows Settings App Settings

- In this section, we will be covering some settings to tweak in the Windows Settings App. (Both Windows 10 and 11)
## System Settings

### 1. Display Settings.
**Location** - Settings - System - Display
**Tweak these: (Both Versions):**
1. **Scale and layout:** Set to 100%, higher scaling uses more resources.
2. **Display Resolution:** Set to the native resolution (The one that says recommended) but lower resolution can help with weak GPUs, especially in [iGPUs](https://www.google.com/search?q=what+is+a+igpu).
3. **Display Refresh Rate:** Set to the highest. To tweak this go to Settings - System - Display - Advanced Display settings and you will see it.
   NOTE: If you have dynamic refresh rate, disable it. Plus also know that higher refresh rate consumes [more power](https://www.google.com/search?q=does+higher+refresh+rate+consume+more+power).
4. **HDR**: Turn off.
5. **Night light:** Turn off if not using.

**For Windows 10:**
Go to Graphics settings:
- Add your game executables. See: [How to locate your games exe file.](https://www.auslogics.com/en/articles/find-a-programs-exe-file-in-windows-10/)
- Set your game to high performance.
- If you have "Hardware-accelerated GPU Schedulling" turn it on.
  NOTE: Test if hardware-accelerated GPU Schedulling gives you issues. In some systems it can.

**For Windows 11:**
Go to Graphics settings:
 - Do the same thing as windows 10 but in this case enable: "Optimizations for windowed games."
   What it does: It allows for better FPS and latency while using borderless fullscreen. Giving around the same latency as excusive fullscreen.

### 2. Sound Settings
**Path:** Settings - System - Sound

**Tweak these:**
 - **Spatial sound:** OFF
  How to disable spatial sound:
  Windows 10 & 11:
	-  Go to Settings - System - Sound
	  Go to device properties under output device
	- Go to spatial sound and set it to off.
	  OR - Go to sound control panel on the right
	- Double Click your speaker
	  Go to spatial sound
	- Set it to Off.
- **Mono audio:** OFF (unless needed)
  How to disable mono audio:
  1. Go to settings - system - sound
     Click on the right ease of access audio settings
  2. Click Mono audio - Off
	Through accessibility:
	Windows 10:
		1. Go to Settings - Ease of Access
		2. Go to audio under hearing
		3. Turn of mono audio
	Windows 11:
		- Go to Settings - Accessibility
		-  Click audio under hearing
		- Find Mono audio and turn it off.
		  
 - **Advanced Options:**
 - Setting sample rate to 44100 Hz or 48000 Hz
    How to do this:
		    1. Go to Control panel - Sound or through Settings - System - Sound
		    Go to playback devices
		    Double Click your speaker
		    Go to the 'Advanced' section
		    Set it to the sample rates above in default format
-  Disabling Audio Enhancements
	How to do this:
		1. Go to Control Panel → Sound
		2. Select playback device → Properties
		3. **Enhancements** tab - Check "Disable all enhancements"


### 3. Notifications Settings
**Path:** Settings - System - Notifications

**Tweak these:**
- Turn Off "Notifications"
- In Windows 10, Turn Off "Show Notifications on the lock screen"
- If you dont want to turn off notifications, disable notifications from apps manually on the bottom.
- Turn Off "Focus assist" notifications
- In Windows 11, Turn off do not disturb just in case.


### 4. Power and Battery
**Path:** Settings - System - Power and battery

**Tweak these:**
 - **Power mode:(Mainly windows 11)**
   - For Laptops, set it to balanced when on battery and best performance when plugged in.
   - For Desktops, set it to Best Performance.
   - NOTE: If the option is greyed out, its because the "Balanced" power plan isnt on. To enable go to Control Panel - Power Options and set it to Balanced.
 - **Screen and sleep or screen, sleep and hibernate timeouts:**
   - Set it to Never when plugged in and something when on battery (your preference)
   - If you have extra options: For plugged in set everything to never and for on battery: Set turn off my screen after for 10 minutes, sleep after 30 - 45 mins and hibernate after 1 - 3 hours. Saves battery on laptop.
 - **Battery saver settings:**
   - Turn off battery saver if desktop
   - If laptop, set battery saver to turn on at a certain percentage.

### 5. Storage Settings
**Path:** Settings - System - Storage

**Tweak these:**
- **Storage Sense:** On or Off (If you have a bunch of storage)
  - Run: Every week
  - Delete temp files: On
  - Delete files in recycle bin: Your preference
  - Delete files in Downloads folder: Your preference.

### 6. Nearby Sharing (Or Shared Experiences)
**Path:** Settings - System - Nearby Sharing
**(In windows 10)** - Settings - System - Shared Experiences.

**Tweak these:**
 - Turn Off "Nearby Sharing"
 - If you are in Windows 10, also turn off share across devices.


### 7. Multitasking
**Path:** Settings - System - Multitasking

**Windows 11 Specific:**
- **Snap windows:** Your choice, useful for multitasking.
  - Turn off these:
    When i snap a window, suggest what i can snap to it
    Show snap layouts when i hover over a windows maximize button
    When i drag a window, let me snap it without dragging all the way to the screen edge.
- Show tabs from apps when snapping or pressing Alt + Tab - Off
- Under desktops, set everything to only the desktop im using.
- Turn off title bar window shake. 

**Windows 10 Specific:**
  - **Snap windows:** Your choice
  - **Alt+Tab:** Shows only open windows
  - **Virtual Desktops:** Only on the desktop im using
  - **Timeline:** Turn OFF.

### 8. Clipboard History
**Path:** Settings → System → Clipboard

**Optimize:**
- Turn OFF "Clipboard history" (or keep if you use it)
- Turn OFF "Sync across devices"

### 9. Remote Desktop
**Path:** Settings → System → Remote Desktop

**Optimize:**
- Turn OFF if not using


## Bluetooth & Devices Settings

### 1. Bluetooth
**Path:** Settings - Bluetooth & devices - Bluetooth

**Tweak These:**
- Turn off bluetooth if not using.

### 2. Printers & Scanners
**Path:** Settings - Bluetooth & Devices - Printers & Scanners

**Tweak these:**
- Turn OFF "Let windows manage my default printer" (Doesnt really affect performance, just gives you more control)
- Remove unused printers (Reduces clutter)

### 3. Mouse
**Tweak these:**
- **Mouse Acceleration:** Go to Control Panel - Mouse
- Go to Pointer Options and turn off 'Enhance pointer precision'
- Affects pointer speed.


## Personalization Settings

### 1. Background
**Path:** Settings - Personalization - Background

**Tweak these:**
- Use either 'Solid color' or 'Picture'.  (NO SLIDESHOW)

### 2. Colours or Colors

**Path:** Settings - Personalization - Colors

**Tweak these:** 
- **Transparency Effects:** Off (Uses Some Resources)
- **Color mode:** Dark Mode (Uses less power)

### 3. Dynamic Lighting
**Path: (Only Windows 11)** Settings - Personalization - Dynamic Lighting

**Tweak these:**
- Turn off: Use dynamic lighting on my devices
- Turn off: Compatible apps in the foreground control lighting

### 4. Start
**Path:** Settings - Personalization - Start

**Windows 11 Specific:**
- Turn Off: Show most used apps, Show recommendations for tips, recent files in File Explorer and items in Jump lists and Show recommendations for tips, shortcuts, new apps and more.

**Windows 10 Specific:**
- Turn OFF "Show recently opened items in Jump Lists"
- Turn OFF "Show suggestions occasionally in Start"
- Turn OFF "Show app list in Start menu" (optional - for minimalism)
- Disable Live Tiles (right-click tiles → Turn live tile off)
- Unpin unnecessary tiles for cleaner, faster Start menu

### 5. Taskbar
**Path:** Settings - Personalization - Taskbar

**Windows 11 Specific:**
- **Taskbar items:**
  - Turn OFF "Widgets" (major performance impact!)
  - Turn OFF "Chat" (Microsoft Teams chat icon)
  - Turn OFF "Task view" button (if not using virtual desktops)
  - Turn OFF "Search" (or set to icon only)
- **Taskbar behaviors:**
  - Turn OFF "Show badges on taskbar buttons"
  - Turn OFF "Show flashing on taskbar buttons"
  - Turn OFF "Automatically hide the taskbar" (can cause stutters when it appears)
- **System tray:**
  - Customize which icons show in system tray
  - Disable unnecessary tray icons

**Windows 10 Specific:**
- Turn OFF "News and interests" (major resource hog!)
- Turn OFF "People" button
- Turn OFF "Meet Now" icon
- Turn OFF "Task View" button (if not using)
- Set taskbar search to "Hidden" or "Icon only"
- **Taskbar behaviors:**
  - Turn OFF "Show badges"
  - Turn OFF "Show taskbar button flashing"
  - Don't auto-hide (causes stutters)
- Right-click taskbar → Turn OFF:
  - News and interests
  - Show Task View button
  - Show People on taskbar


## Apps Settings
### 1. Installed Apps
**Path:** Settings - Apps - Installed apps

**Tweak these:**
 - Delete whatever you dont need
 - For each app:
   - Click three dots - Advanced options - Background apps permissions - Never
**For Windows 10:** Go to Settings - Privacy  -Background apps - Let apps run in the background - OFF.


### 2. Startup Apps
**Path:** Settings - Apps - Startup

**Tweak these:**
Disable everything you dont need except:
- Important drivers
- Antivirus (If using third party)

### 3. Offline Maps
**Path:** Settings → Apps → Offline maps

**Tweak these:**
- Delete all downloaded maps if not using

## Gaming Settings

### 1. Game Mode
**Path:** Settings - Gaming - Game Mode

**Tweak these:**
- Turn on Game Mode.
- NOTE: In some devices, it might make your games slower so test for a little bit.


### 2. Xbox Game Bar
**Path:** Settings - Gaming - Game bar

**Tweak these:**
- Turn OFF if you dont use it.

### 3. Captures
**Path:** Settings - Gaming - Captures

**Tweak these:**
- Disable everything you dont use there

## Privacy and Security Settings

### 1. Main Privacy
**Path:** Settings - Privacy & Security
#### 1. Find My Device
**Path:** Settings - Privacy & Security - Find My Device

- Turn it off unless you need it.

#### 2. Device Encryption
**Path:** Settings - Privacy & Security - Device Encryption

- I personally turn it off because of issues during troubleshooting but keep it on if you want your device to be secure

#### 3. Windows Permissons
**Path:** Settings - Privacy & Security

- Turn OFF Everything under Windows Permissions.


### 2. App Permissons

**Turn OFF These:**
- Location - OFF (Unless Needed)
- Camera - Only Apps you will use them on
- Microphone - Only for communication apps
- Notifications - Off
- Account info - Off
- Contacts - Off
- Calendar - Off
- Call History - Off
- Email - Off
- Tasks - Off
- Messaging - Off
- Radios - Off
- Other devices - Off
- Background apps - Off
- App diagnostics - Off
- Automatic file downloads - Off
- Music Library/Downloads/Documents/Pictures/Videos - Restrict access
- Text and image generation - Off unless you use it

## Windows Update

### 1. Windows Update
**Path:** Settings - Windows Update

**Tweak these:**
- Turn OFF 'Get the latest updates as soon as possible'
- Also Turn OFF These:
  - Recieve Updates for other microsoft products
  - Get me up to date
  - Download updates over metered connections
  - Notify me when a restart is required to finish updating
- Active hours - Put this to when you use the PC


### 2. Delivery Optimizations
**Path:** Settings - Windows Update - Advanced Options - Delivery Optimization

**Tweak these:**
- Turn Off 'Allow downloads from other PCs or devices'


## Accessibility Settings

### 1. Visual Effects
**Path:** Settings - Accessibility - Visual effects

**Tweak these:**
- Turn OFF Visual effects and Transparency Effects


### 2. Narrator
**Path:** Settings - Accessibility - Narrator

**Tweak these:**
- Turn it OFF (Unless you need it)



## Summary Of Windows Settings

- These are the ones which have the most impact.

Mainly for Windows 11:
System > Nearby sharing - Disable It.
In windows 10, its at System > Shared Experiences. Disable Nearby Sharing.

System > Multitasking - Disable if you dont use it.

Network & internet > Mobile hotspot - Disable if you dont use.

Personalization > Background - Dont use slideshow. 

Personalization > Lock screen - don't get fun facts. No one wants fun facts.

Personalization > Taskbar - switch off everything you don't use.

Personalization > Device usage - turn off everything.
(Not in Windows 10)
Personalization > Dynamic Lighting - turn that stuff off.
(Not in Windows 10)
Apps > Installed apps - go down every app, select the 3-dot ... menu > Advanced options (where applicable) > set apps to never run in the background if you don't want them to, and/or uninstall what you don't want.
(In windows 10 Just go to privacy and disable background apps.)

Apps > Advanced app settings > Share across devices - turn off if you don't do that.
(Its in System - Shared Experiences In Windows 10)
Apps > Startup - turn off what you don't want starting with Windows. Leave the hardware apps on.

Time & Language > Typing - turn off what you don't use.

Gaming - turn off what you don't use.

Accessibility > Visual effects - always show scrollbars but turn off transparency and animation effects.

Accessibility > Hearing > Captions - turn off if you don't need or want them.

Privacy & security > Windows permissions and App permissions - go through all **32** categories and turn off everything you don't want or need.
(Look above)
Windows Update > Advanced options > Additional options > Delivery Optimization - turn it off.
Credit to: @dtallee on reddit.

