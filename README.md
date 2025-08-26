# Daggerfall-modernization-guide
A complete guide to modernizing The Elder Scrolls II: Daggerfall using Daggerfall Unity, visual mods, and ReShade enhancements.

## Dream
Paste the "Mods," "SpellIcons," and "Presets" folders into the following directory:

"..Daggerfall\DaggerfallUnity_Data\StreamingAssets"

Organize them as follows:
"..Daggerfall\DaggerfallUnity_Data\StreamingAssets\Mods"
"..Daggerfall\DaggerfallUnity_Data\StreamingAssets\SpellIcons"
"..Daggerfall\DaggerfallUnity_Data\StreamingAssets\Presets"

In the game, confirm that all 12 or more(in case updated) Dream packages are marked as "Enabled."

After copying the presets to the designated folder:

Open the mods section in the game menu.
Select the desired mod for setup(Some mods include the option to configure presets within their settings menus.).
Click on "settings."
In the top right corner, locate the "presets" tab.
Click on the tab and load the DREAM preset.
Utilize these presets to achieve the optimal final results!

Download Link: https://www.nexusmods.com/daggerfallunity/mods/5

## Setting up ReShade
Access the DREAM folder and launch ReShade_Setup_4.8.2.exe or the latest version.
Select the gray button labeled "Click here to select a game and manage...."
Click "Browse."
Navigate to your "DaggerfallUnity.exe" in the game folder (e.g., "C:\Program Files (x86)\Steam\steamapps\common\Daggerfall Unity").
Choose "DaggerfallUnity.exe" and click "Open."
Opt for "DirectX 10/11/12."
Ensure all checkboxes are marked.
Click OK.
Always choose "Select all" and click OK.

## Importing the DREAM RESHADE preset
Copy "DREAM 2022.ini" to the folder where your "DaggerfallUnity.exe" is located, such as "C:\Program Files (x86)\Steam\steamapps\common\Daggerfall Unity."

To Apply the DREAM Reshade Preset in the Game:

Reshade initiates automatically upon starting the game, briefly displaying information at the top of the screen.

Access the Reshade menu by pressing the "Home" key and click "Skip tutorial."

Locate "ReShadePreset" at the top and click on it.

Choose "DREAM 2022."

Click on "Select."

Recommended: Set the ON/OFF key to the "End" key (located under the "Home" key). Configure this in "Settings" - "General" - "Effect Toggle Key."
Completion: DONE!

Note: The DREAM version may change from year to year, and if the mod is updated, ensure to
replace the existing file with the updated version.

## Enhanced Sky mod
Download Enhanced Sky mod, extract it, and copy the files into:

C:\Program Files (x86)\Steam\steamapps\common\The Elder Scrolls II Daggerfall\arena2 launcher\DaggerfallUnity_Data\StreamingAssets\Mods or wherever the game is installed.

Download Link: https://forums.dfworkshop.net/viewtopic.php?t=1542

## Distant Terrain
Download Distant Terrain mod, extract it, and copy the files into:

C:\Program Files (x86)\Steam\steamapps\common\The Elder Scrolls II Daggerfall\arena2 launcher\DaggerfallUnity_Data\StreamingAssets\Mods or wherever the game is installed.

Download Link: https://www.nexusmods.com/daggerfallunity/mods/128

## Handpainted model replacements
Download the Handpainted model mod, extract it, and copy the files into:

C:\Program Files (x86)\Steam\steamapps\common\The Elder Scrolls II Daggerfall\arena2 launcher\DaggerfallUnity_Data\StreamingAssets\Mods or wherever the game is installed.

Download Link: https://www.nexusmods.com/daggerfallunity/mods/9

## Real Grass
Download Real Grass mod, extract it, and copy the files into:

C:\Program Files (x86)\Steam\steamapps\common\The Elder Scrolls II Daggerfall\arena2 launcher\DaggerfallUnity_Data\StreamingAssets\Mods or wherever the game is installed.

Download Link: https://www.nexusmods.com/daggerfallunity/mods/20

## Improved Interior Lighting
Download Improved Interior Lighting mod, extract it, and copy the files into:

C:\Program Files (x86)\Steam\steamapps\common\The Elder Scrolls II Daggerfall\arena2 launcher\DaggerfallUnity_Data\StreamingAssets\Mods or wherever the game is installed.

Download Link: https://www.nexusmods.com/daggerfallunity/mods/144

## To launch the game through Steam
1) To launch Daggerfall Unity from Steam, start by installing Daggerfall Unity using the guide provided earlier. Once the installation is complete, follow the steps below to enable Steam integration for Daggerfall Unity only after installing mods:

Navigate to the following directory: Steam\steamapps\common\The Elder Scrolls Daggerfall.

Locate the existing "DOSBox-0.74" folder and rename it to "DOSBox-0.74-backup." Then, create a new, empty folder named "DOSBox-0.74" in the same directory.

Copy all the contents from the Daggerfall Unity installation folder, which you downloaded from the specified zip file (e.g., dfu_windows_64bit-v0.16.2-rc), and paste them into the newly created "DOSBox-0.74" folder.

Within the "DOSBox-0.74" folder, rename "DaggerfallUnity.exe" to "DOSbox.exe" and "DaggerfallUnity_Data" to "DOSBox_data."

By following these steps accurately, you can now launch Daggerfall Unity directly from Steam.

2) After the successful launch of Daggerfall from steam navigate to the mods section to customize settings based on player preferences. Press the Home Button, and ensure to check the boxes for AdaptiveSharpen[AdaptiveSharpen.fx], Clarity, and SMAA. Additionally, tick the Performance Checkbox is located at the bottom.
