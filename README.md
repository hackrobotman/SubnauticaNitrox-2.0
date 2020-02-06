# Nitrox-2.0
PIRATE-FRIENDLY NITROX MOD FOR SUBNAUTICA MULTIPLAYER

YOU SHOULD STILL SUPPORT THE DEVELOPERS, UNKOWN WORLDS, AND BUY THIS GAME AS I HAVE. THIS GAME IS GREAT, I JUST DISLIKE OPEN-SOURCE DEVELOPERS WHO TRY TO CONTROL WHO CAN USE THEIR PROJECTS. DEVELOPERS WHO TRY TO IMPOSE THEIR OWN MORAL COMPASS ON AN OPEN-SOURCE PROJECT ARE FUCKING IDIOTS WHO ARE UNAWARE OF HOW SIMPLE IT IS TO MODIFY AN OPEN-SOURCE PROJECT. FUCK YOU SUNRUNNER.

Download this repo as a .zip and extract the AssetBundles-lib.zip folder within so that the contents of that folder are in the same directory as every other file in this repo.
You WILL need dnSpy for this to work.
As far as I have tested, multiplayer only works with Build Apr-2018 60026

Once you've extracted everything properly:
1. Open steam, in the top left, click on "Games" and then clicl "Add a non-Steam game to my library"
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
12. Replace what's in quotes with what you copied in step 7.
  
Now you should be good to go! Have fun playing with your friends, even if they have pirated copies, and remember, Sunrunner is a bitch.
