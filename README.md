# LauncherKiller
Are you using a Video Game Library Manager like Playnite or LaunchBox? Are you tired of closing the launchers (Steam, Origin, Epic Games, ...) manually, which just don't have an option to close itself after you've finished playing? Then this little tool is just right for you.
<br>
This tool terminates processes and is still in the test phase. I am not responsible for any damage to your system. 

# Setup
1. VERY IMPORTANT! if you don't want to remove the remaining icons yourself, open all launchers manually and make them always              visible in the SystemTray.<br>

Before:<br>
![alt text](https://raw.githubusercontent.com/acealone/LauncherKiller/master/images/Tray_Launcher_Before.png)
<br>
After:<br>
![alt text](https://raw.githubusercontent.com/acealone/LauncherKiller/master/images/Tray_Launcher_After.png)
<br>
2. Move the files to a folder of your choice.<br>
3. Open "LauncherKiller.exe", press "+" and add your launcher.<br>

# Usage
There are two ways to use this tool.<br>
<h2>Normal mode:</h2>
Keep LauncherKiller open while launching your games. It will detect when a fullscreen application is started. After you finished playing, LauncherKiller will terminate all open launcher which are in the list. You can use the checkbox to minimize LauncherKiller to tray.<br>
<h2>Lite mode:</h2>
You can use the script section in e.g. Playnite or LaunchBox to close all launchers in the list after done playing.<br>
Batch:<br>
Start C:\LauncherKiller\LauncherKiller.exe --lite
