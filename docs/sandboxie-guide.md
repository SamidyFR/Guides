# *Run untrusted software in unprivileged containers with Sandboxie-Plus*

Caveats:
 1. This provides better performance than a typical virtual machine. But there's some performance loss, so **it's not ideal for resource-intensive games**.

 2. This is **only for using programs while isolating them from the internet**. If you're an advanced user, feel free to tweak Sandboxie-Plus to be usable while letting the sandbox connect to the internet by [blocking read-access to sensitive directories](https://sandboxie-plus.com/sandboxie/closedfilepath/). Or use a [virtual machine](https://fmhy.net/system-tools#virtual-machines) instead.

 3. Sandboxie-Plus is **only available for Windows**. So, if you're a MacOS or Linux user, it won't work unless you set up a Windows VM beforehand and install it on there.

 4. Sandboxie-Plus has **premium features** and unless you [support them](https://www.patreon.com/DavidXanatos), you won't get permanent access to them (only for 5 minutes). You can try to compile the code yourself from [their GitHub repo](https://github.com/sandboxie-plus/Sandboxie). But if you can't, you're out of luck.

![Sandboxie-Plus Logo](https://avatars.githubusercontent.com/u/63755826?s=200&v=4)

---

### *Getting Started*

#### *Download Sandboxie-Plus*

Download and install the latest version of the software from [here](https://sandboxie-plus.com/downloads).
**(Pick the version similar to this one:** ***Sandboxie-Plus-[Architecture]-[Version Number].exe*****)**

  ![one](https://files.catbox.moe/2nwkor.png)

#### *Install Sandboxie-Plus*

Install it like any other program. The steps have been listed anyways in case you have issues.

  1. Select your language and click on `OK`.

    ![two](https://files.catbox.moe/m5cbwt.png)

  2. Click on `I accept the agreement` and then `Next`.

    ![three](https://files.catbox.moe/40zy2x.png)

  3. Select `Install Sandboxie-Plus on this computer` if you want it to be a standard application, otherwise select the `Extract all files to a directory for portable use` option for portable use.

    ![four](https://files.catbox.moe/q15lrr.png)

  4. You can browse for a new installation folder. Otherwise, click `Next`.

    ![five](https://files.catbox.moe/rfnjfh.png)

  5. Give the app a name if you want to. Otherwise, click on `Next`.

    ![six](https://files.catbox.moe/z2qsid.png)

  6. You can check the `Create a desktop shortcut` checkbox to create a desktop shortcut. The `Download latest Templates.ini and translations` option's not necessary unless you can't understand English. **Do not check the `Install (or Update) ImDisk 3.0 driver (for RamDisk and Encrypted Sandboxes)` checkbox unless you have a premium certificate as both of those are paid features.** Then, click on `Next`.

    ![seven](https://files.catbox.moe/fmdkut.png)

  7. Check the options if you want to. Otherwise, click on `Install`.

    ![eight](https://files.catbox.moe/ss4avj.png)

  8. Wait for a bit until it finishes installing.

    ![nine](https://files.catbox.moe/urrp0k.png)

  9. You can check the `Start Sandboxie-Plus UI` checkbox. Regardless of if you do or do not, click on `Finish`.

    ![ten](https://files.catbox.moe/gqzetx.png)

#### *Setting up Sandboxie-Plus*

After opening the app, you'll notice that a new `Introduction` window has opened. You can use it to configure the app to your liking. Follow the steps below.

  1. Select whether you're using it for personal or commercial use. **Be sure to double check the selection as it persists on the later installations as well.**

    ![eleven](https://files.catbox.moe/cw5avs.png)

  2. If you have the premium certificate, fill in your personal details and rest of the serial number. Regardless of if you do or do not, click on `Next`.

    ![twelve](https://files.catbox.moe/jquxzv.png)

  3. If you're an advanced user, select the first option and if you're not, select the second one. Use the third option if you want a more retro feeling while using the app. After that, select `Bright Mode` if you like light mode and `Dark Mode` if you like dark mode.

    ![thirteen](https://files.catbox.moe/xt95jf.png)

  4. Check the first option if you want the app to automatically start with Windows, the second one if you want to create a sandbox from the Windows context menu, the third one if you want a desktop icon of a browser using Sandboxie and the fourth one if you want only apps with admin access to your computer to be able to change the configuration of Sandboxie-Plus. Then click on `Next`.

    ![fourteen](https://files.catbox.moe/tec1sj.png)

  5. Pick the first option if you want stable updates and the second one if you want experimental updates. Then click on `Next`.

    ![fifteen](https://files.catbox.moe/fjj27d.png)

  6. Click on `Finish`.

    ![sixteen](https://files.catbox.moe/e8hn6g.png)

---

### *Create a sandbox*

  1. Click on `Sandbox (located at the top-left side of the screen)` → `Create New Box`.

    ![seventeen](https://files.catbox.moe/6uy8sf.png)

  2. Give the box a name and select the box type (if you don't have access to the premium features, select `Standard Sandbox`). **Be sure to check the `Configure advanced options` checkbox.**

    ![eighteen](https://files.catbox.moe/9f5kky.png)

  3. In the next page, the default selections are good enough. If you're an advanced user, feel free to change the settings to your liking. If not, click on `Next`.

    ![nineteen](https://files.catbox.moe/b01kuw.png)

  4. In the next page, change the `Network Acess` selection to `Block network/internet by denying access to Network devices`, check `Make applications think they are running elevated` and `Drop rights from Administrators and Power User groups`. Then, click on `Next`.

    ![twenty](https://files.catbox.moe/28rzr7.png)

> **Warning: Blocking internet connections is important** in this particular setup, because the app you run is allowed to read *(not modify)* many of the files accessible to your current user, and could potentially upload them to the internet. If you really need internet for a program, consider configuring the sandbox with less privileges, for example by [blocking read-access to sensitive directories](https://sandboxie-plus.com/sandboxie/closedfilepath).

> **Note:** 'Make applications think they are running elevated' allows you to install any program without giving administrator (full system control) permissions.

> **Warning:** 'Drop rights from Administrators and Power User groups' is especially important if your current Windows user is an *Administrator* account. For extra isolation, you could create a separate Windows user account, a *Standard User* without admin permissions, but it's not required.

  5. Click on `Next`.

    ![twenty-one](https://files.catbox.moe/w0gpff.png)

  6. Click on `Finish`

    ![twenty-two](https://files.catbox.moe/nju0ko.png)

##### *Confirm settings are correct*
The `Status` column shows if you correctly blocked admin permissions and internet connections:

  ![twenty-three](https://files.catbox.moe/m10753.png)

---

### *Install your app inside the sandbox*
The app will **not** ask you for admin permissions, because it has fake admin permissions. It will be installed in a parallel file system inside the sandbox.

#### *Create a sandbox from the Windows context menu*
Right click on the file you want a sandbox for. Then click on `Run Sandboxed`.

Windows 10:

  ![twenty-four](https://files.catbox.moe/23ys2b.png)

Windows 11:

  ![twenty-five](https://files.catbox.moe/akpdij.png)

> If you're using something to only have the old context menu on Windows 11, it won't work.

#### *Explore the Windows File Explorer from inside the sandbox*

  1. Right click on the sandbox that you want to run. Then, go to `Run` → `Standard Applications` → `Windows Explorer`

    ![twenty-six](https://files.catbox.moe/ywpog3.png)

  2. Check the `Don't show this message again.` checkbox and click on `OK`.

    ![twenty-seven](https://files.catbox.moe/k0tdbg.png)

---

### *Run your sandboxed app or game*

#### *Run it from the start menu*

Right click on the sandbox that you want to run. Then, hover over `Run` → `Standard Applications`. After that, click on `Run from Start Menu`

  ![twenty-eight](https://files.catbox.moe/d2m5f9.png)

#### *Create a desktop shortcut*

  1. While the sandboxed app is open, right-click on the main process and select `Create Shortcut`.

    ![twenty-nine](https://files.catbox.moe/oan7tk.png)

  2. Save it like a normal shortcut.

    ![thirty](https://files.catbox.moe/vmqpnd.png)

#### *Take files out of the sandbox*

  1. Right click over the sandbox that you want the files out of. Then, click on `Recover Files`.

    ![thirty-one](https://files.catbox.moe/k9udot.png)

  2. Select the file that you want to take out. If there are multiple files that you want to take out, select the folder. After that, click on `Recover`.

    ![thirty-two](https://files.catbox.moe/8t9271.png)

---

### *Other interesting settings*

#### *Block read-access to cookies directories using [closedfilepath](https://sandboxie-plus.com/sandboxie/closedfilepath)*
It's important when letting the sandbox connect to the internet. It's meant for advanced users only. So, if you consider yourself one, follow the steps.

  1. Right click on the sandbox. Then click on `Sandbox Options`.

    ![thirty-three](https://files.catbox.moe/kudlwl.png)

  2. Click on `Edit ini Section`. Then click on `Edit ini`. After that, add these lines for the following browsers:

**For Chromium based browsers:** `ClosedFilePath=%LocalAppData%\*\*\User Data\Default\*`

  ![thirty-four](https://files.catbox.moe/bmbvmc.png)

**For Firefox based browsers:** `ClosedFilePath=%USERPROFILE%\AppData\Roaming\*\Profiles\*`

  ![thirty-five](https://files.catbox.moe/uul9pu.png)

  3. Click on `Ok`.

You can use 'Windows File Manager' inside the sandbox to verify that you can't access those directories that contain cookies or other sensitive files.

#### *Total access for selected directories using [openfilepath](https://sandboxie-plus.com/sandboxie/openfilepath)*
You can let the the sandboxed app directly edit files in some specific directories.

  1. Right click on the sandbox. Then click on `Sandbox Options`.

    ![thirty-six](https://files.catbox.moe/kudlwl.png)

  2. Click on `Edit ini Section`. Then click on `Edit ini`. After that, add a line similar to `OpenFilePath=[Directory Path]` which will look something like `OpenFilePath=C:\Downloads\`.

    ![thirty-seven](https://files.catbox.moe/q1nnfi.png)

  3. Click on `OK`.

---

### *Credits*
**The previous owner** - Unknown (not a username)
**New / Current owner** - Clara

[![Fuck AI](https://files.catbox.moe/os5g6k.png)](https://notbyai.fyi)

*(With <3)*

**If you have any feedback you want to give me, please fill in a form [here](https://formulaer.com/f/aa502b70-f46d-4e81-98a2-bd6b2de24540).**

**************
[Go back to the top](#run-untrusted-software-in-unprivileged-containers-with-sandboxie-plus)
