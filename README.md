# TUF-ROG-Power-Plan-missing

If your power plan or **Power mode synchronization** option in Armoury Crate is missing on your TUF or ROG laptop, this repository provides solutions to bring them back.

---

## Overview

### How it normally looks
![Power plans: silent and performance mode highlighted](Pictures/LRH123_0-1733765877158.png)

### Expected options in Armoury Crate
![Armoury Crate with highlighted Power mode synchronization](Pictures/20250216172112349_EN02.png)

---

## How to Fix It

There are two main methods depending on your system state.

![Guide flowchart showing fix paths](Pictures/Guide.png)

---

## Steps

### Step 1: Uninstall Armoury Crate

1. Download the [Armoury Crate Uninstall Tool](https://www.asus.com/supportonly/armoury%20crate/helpdesk_download/).
2. Click **Show all** and scroll down until you locate the tool.

![Download section page 1](Pictures/ScreenPic1.png)

![Download section page 2](Pictures/ScreenPic2.png)

3. Unzip the downloaded archive to your Desktop.
4. Run `Armoury Crate Uninstall Tool.exe` as **Administrator**.

![Uninstall tool execution](Pictures/ScreenPic3.png)

5. Wait for the uninstallation process to finish, then **restart your PC**.

---

### Step 2: System Restore

1. Press `Win + R`, type `rstrui.exe`, and click **OK**.

![Run dialog box](Pictures/ScreenPic4.png)

2. Click **Next**.

![System restore window](Pictures/ScreenPic5.png)

3. Review the available restore points and select one created **before** the issue occurred.
   
> [!NOTE]
> If you don't have any restore points available, or if they are all too recent, **skip to Step 2.1**.

![Restore points list](Pictures/ScreenPic6.png)

4. Click **Finish** to start the restore process.

![Final restore confirmation](Pictures/ScreenPic7.png)

### Step 2.1: Windows In-place Upgrade <br>(If step 2 -> 3 didn't help, IF YOU DOING STEP 2 RIGHT NOW - SKIP TO STEP 3)

Save your wallpaper because they will dissapear
1. Run powershell (Press Win and type "Windows Powershell and run it)
   
2. Copy and paste command below

```bash
explorer.exe /select,(Get-ItemProperty "HKCU:\Control Panel\Desktop").Wallpaper
```

3. Save it somewhere for later
   
4. Download Win11 iso file with your language
**Link: https://www.microsoft.com/en-us/software-download/windows11**

5. Scroll to "Download Windows 11 Disk Image (ISO) for x64 devices" <br> Select it and confirm

![Download](Pictures/ScreenPic8.png)

7. Select the language you want your **system** be in and confirm

![Download](Pictures/ScreenPic9.png)

9. You will see download button. Click it

![Download](Pictures/ScreenPic10.png)

10. After you downloaded it, right click file and click **"connect"**

![WinFile](Pictures/ScreenPic11.png)

11. You will see new drive in explorer. Double click it.
![WinFile](Pictures/ScreenPic12.png)

> [!NOTE]
> If you want to cancel it - right click new drive and click *Eject* **SKIP THIS STEP IF YOU DONT WANT TO CANCEL IT**

![WinFile](Pictures/ScreenPic13.png)

12. You will see windows window XD <br> Click next. It will check for updates.

![WinFile](Pictures/ScreenPic14.png)

