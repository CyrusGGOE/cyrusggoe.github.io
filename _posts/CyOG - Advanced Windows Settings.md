# Advanced Windows Settings

Here are some settings that are a bit advanced.


## 1. Disabling Core Isolation

- This is actually a tweak that can guarantee a 5% boost in FPS.

**How to Disable**
1. Go to Windows Security by searching it
2. Then go to Device Security
3. Click on Core Isolation details and Disable Memory integrity.


## 2. Advanced Tweaks

- These are some tweaks that require CMD and are mostly safe.
**Instructions for all the tweaks**
- Run the commands in CMD
- Test them and see if they work.
### 1. NTFS Tweaks

These are a few tweaks that deal with NTFS. They can slightly boost storage speed and are mostly safe.

```cmd
fsutil behavior set memoryusage 2 
fsutil behavior set mftzone 4
fsutil behavior set disablelastaccess 1
fsutil behavior set disabledeletenotify 0
fsutil behavior set encryptpagingfile 0 
```


### 2. Memory Tweaks

A few memory tweaks to free up some CPU Usage.
NOTE: Not recommended on systems with low RAM (8GB or less)

#### 1. Disabling Memory Compression

- Can free up some CPU Usage from decompressing RAM.

```powershell
#  For Powershell
Disable-MMAgent -MemoryCompression
# If using CMD
PowerShell -Command "Disable-MMAgent -MemoryCompression" 
```


#### 2. Page Combining

- Combines pages using the same library. Disabling can reduce RAM Overhead.

```powershell
# For Powershell
Disable-MMAgent -PageCombining
# For CMD
PowerShell -Command "Disable-MMAgent -PageCombining"
```


#### 3. Disabling Paging Executive

- Once again, reduces CPU Overhead

```cmd
REG ADD "HKLM\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management" /v DisablePagingExecutive /t REG_DWORD /d 1 /f
```

### 3. Win32PrioritySeperation

- This is a tweak that controls the balance between foreground and background boost.
- It is very influential in gaming performance.

**How to change:**
Open RegEdit and go to: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\PriorityControl

Find Win32PrioritySeperation and use the table below to change values:

| Hexadecimal Value | Decimal value | Description                              | Priority       | Interval          | Consistency       |
| ----------------- | ------------- | ---------------------------------------- | -------------- | ----------------- | ----------------- |
| 26                | 38            | Default for Windows                      | 3:1 (High)     | Shorter, Variable | Good (Responsive) |
| 2a                | 42            | Most recommended for competitive gaming. | 3:1 (Hifh)     | Shorter, Fixed    | Best consistency. |
| 28                | 40            | Recommended for Input latency focus.     | 1:1 (No Boost) | Shorter, Fixed    | High (Equal)      |

You can also try other values as well.

### 4. Disabling Automatic maintenance

- This is a tweak to disable certain CPU Spikes when windows does automatic maintenance.

```cmd
reg add "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule\Maintenance" /v "MaintenanceDisabled" /t REG_DWORD /d "1" /f
```

**Note:** Now that it is disabled, maintaining the PC will now be done by the user.

