# SSE-Frostfall-SKSE64-SkyUI-FIX
Temporary fix for Skyrim SSE (64bit) running Campire, Frostfall, SKSE64, and SkyUI. Fixes for 16:9 and 21:9 ultrawide.
This is based off the authors temporary fix outlined here: http://www.dracotorre.com/blog/frostfall-se-skse64/ it fixes
warmth and coverages values being forced 0 for everything and also not showing up in any of the menus. 

# What you should already have installed:

- Campfire 1.11 SE: https://www.nexusmods.com/skyrimspecialedition/mods/667
- Frostfall 3.4.1 SE: https://www.nexusmods.com/skyrimspecialedition/mods/671
- SKSE64 Alpha 2.0.6 SE: http://skse.silverlock.org/
- SkyUI 5.2 SE: https://www.nexusmods.com/skyrimspecialedition/mods/12604

# Fixing that install to work together:

First install PapyrusUtil 3.4 SE: https://www.nexusmods.com/skyrimspecialedition/mods/13048/

Then install one of these FIX mod zip files using NMM. Only install one: 16:9 users install the normal fix, 21:9 ultrawide 
users install the ultrawide fix. 

** When installing in NMM click "No" and "No" when the version/upgrade dialogs pop up, and then click "Yes to all" when asked about replacing files with the same names **

Then after starting up Skyrim SSE SKSE564 go into MOD SETTINGS -> SkyUI and turn off version checking for these 4 menus: 
inventory, barter, container, and crafting. Otherwise you will see warning popups when you initially use them.

Instructions here for disabling those version checks and setting up your Frostfall meters to sit compactly at the top 
right of your screen: 
>
>  https://imgur.com/a/YYP6F
>

That's it, you're ready to roll!

# Known issues

The ultrawide fix has a known issue where the bottom black bar doesn't fully extend across the screen when in certain menus 
but it is purely cosmetic. 

If you run into any issues with Frostfall not behaving right, especially the meters not showing up, you can use the following 
method to reset frostfall but you'll lose all of your frostfall progress. To do this try disabling frostfall and this fix 
temporarily in nexus mod manager. You can then load up your save, click ok when it warns you frostfall is missing, make 
another save that no longer contains frostfall, then exit Skyrim and re-enable Frostfall and this fix, and load that new 
save back up. You will now get to start frostfall from the beginning. For me this corrected an issue where no matter what my 
frostfall gauges would not show up on an existing playthrough.
