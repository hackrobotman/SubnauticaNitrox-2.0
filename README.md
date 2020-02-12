# SubnauticaNitrox-2.0
PIRATE-FRIENDLY NITROX MOD FOR SUBNAUTICA MULTIPLAYER

♪ Yar-har-fiddle-dee-dee ♪\
♪ Being a pirate is alright to be ♪\
♪ I do what I want because a pirate is free ♪\
♪ I am a pirate! ♪

**Download this repo as a .zip and extract it. I like to place the contents in a folder called NitroxMod in the Subnautica install directory, but the mod could be anywhere.**

**You WILL need 32-bit dnSpy for this to work.
As far as I have tested, multiplayer only works with Build Apr-2018 60026**

Once you've extracted everything properly:
1. Open steam, in the top left, click on "Games" and then click "Add a non-Steam game to my library"
2. Direct steam to where you keep your Subnautica.exe
3. Go to your Steam library and right-click on your link to Subnautica
4. Navigate to Manage > Add Desktop Shortcut
5. Right-click on your new shortcut and go to properties
6. You should see something like "steam://rungameid/<LOTS-OF-NUMBERS>" (the number string should be unique for everyone as far as I know)
7. Copy that entire string, including steam://rungameid/
8. Open up dnSpy, go to File > Open > NitroxLauncher.exe
9. Expand NitroxLauncher > NitroxLauncher.exe > LauncherLogic
10. Look for the method StartSubnautica
11. Look for the line processStartInfo.FileName = "steam://rungameid/14899496267188011008"  
12. Right-click on the line and click "edit method."
12. Replace what's in quotes with what you copied in step 7.\
  **As far as I know, this line of code is merely inserted into the run menu (Win+R) when the method is called (by clicking play singleplayer or multiplayer in the launcher. Therefore, you could simply place the direct path to subnautica.exe in the quotes instead. I do not know if this will work but it might be easier than doing the first 7 steps.**

You should also update path.txt with your path to the Subnautica install directory, but this can also be done from the launcher options menu, as far as I know.

Now you should be good to go! Have fun playing with your friends, even if they have pirated copies, and remember, support the developers!

Sunrunner is a bitch
