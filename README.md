# mods tutorial
**1. Installation of Java 8** (*If you're already sure you have Java 8 installed, you may skip this step*)

Head to https://www.java.com/en/download/ and click the red button which reads "Agree and Start Free Download."
Once the exe downloads run it and follow the prompts until it is installed.

**2. Installation of Forge**

Head to https://files.minecraftforge.net/net/minecraftforge/forge/index_1.16.5.html and download the latest installer.
Once it has downloaded, find the file and double-click it. If nothing happens, you need to return to step one (if it still doesn't work ping me and I'll help you). 
If a prompt opens asking which program to run it with, choose Java.
After double clicking it, it should open up a GUI with three choices. Select "Install Client" then click "OK."
Wait until a pop up window opens stating that the installation is complete.

**2. Downloading Modpack**

Head to https://desktop.github.com and click the button which reads "Download for Windows (64bit)."
Follow the on-screen instructions until you land on the home page of the program (you can skip logging in and creating an account).
In files, head to %Appdata%/.minecraft/ and **delete** the folder named mods.
Go back to Github Desktop and click clone repository (Ctrl+Shift+O).
Choose the third pane titled URL. In the repository URL field, enter "OmarAlsh/mods" without the quotation marks.
In the local path field, click the "Choose" button and navigate to %appdata%/.minecraft then make sure the file name is mods then click Select.
Click the clone button and wait for the mods to download.

**3. Configure Minecraft**

*This is optional but hihgly recommended.*
Open the Minecraft Launcer and open the installations pane. Hover over "forge" and click the three-dots button, then click edit.
Open the more options drop-down then change the number in the -Xmx2G argument to a higher number (this is the number of gigabytes of RAM that will be allocated to Minecraft when forge is being used).
As an example, my JVM ARGUMENTS field reads: 

-Xmx6G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M

Notice that the first flag has been changed to six gigabytes. If you fear that you've broken your Minecraft, simply click the reset button beside this field.

**4. Adding the server**

Launch the forge installation and wait for it to open. It may take a while on the first launch.
Head to multiplayer and add the server address listed in the #server-announcements channel.
If the server won't open for you, you probably need to update your modpack (I explain hwo to do this in the next section).


**How to update  your mods list**

Adding new mods is easy using Github Desktop.
Simply open the program and click the "Fetch origin" button while in the mods repository.
Then, click "Pull origin" and wait for the mods to download.
Relaunch forge from the Minecraft Launcher and it should work.

IF YOU HAVE ANY ISSUES PING ME ON DISCORD.
