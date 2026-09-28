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
