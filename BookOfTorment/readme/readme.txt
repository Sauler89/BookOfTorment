======================================
PLANESCAPE: TORMENT - ENHANCED EDITION
MOD UI: Book of Torment v1.57
======================================

Note that the installation alters the UI.menu, BGEE.lua, and L_en_US.lua files.
Since v1.50 these files will be patched, so theoriticaly BoT is more flexible and compatible with other mods.
I also adjusted a bit, the load/save screen to match the portrait mod, but failed to eliminate the ‘green corners’ :(.

Feedback of the new version welcome.

Before installing, download the following mod:
https://forums.beamdog.com/discussion/64382/mod-journal-portrait-conversations-for-pstee/p1
(DWN: https://forums.beamdog.com/uploads/editor/w2/53k6wv7d6y0z.zip
https://web.archive.org/web/20230707040057/https://forums.beamdog.com/uploads/editor/w2/53k6wv7d6y0z.zip)
(The above mod is required for the 'Book of Torment' to display portraits in dialogue boxes.)

WeiDU is also required (since v1.50):
https://github.com/WeiDUorg/weidu/releases
After download, rename .exe to Setup-BookOfTorment.exe

Installation (Windows&Wine):
    1. Unpack both mods and paste them into the game folder (where Torment.exe is situated);
    2. Run Setup-JournalPortraitConversations.exe (Select 'N' when asked about [Modify PSTEE UI.Menu]), next: install it 'I';
    3. Run Setup-BookOfTorment.exe, and install it.

How to set skins after install: Go to the graphics options in the game, look for BoT button ;).

---------------------------------------------------------------------------------------------------------------------------------
Important information: 
"Book of Torment" should be compatible with other mods.

---

The creator of the portraits mod:

"When installing or reinstalling this mod on a game in progress, NPCs in areas you've previously visited won't get portraits, but areas and NPCs you have not yet visited will get portraits. If you start a new game, then all NPCs that should get portraits will get them."

https://forums.beamdog.com/discussion/64382/mod-journal-portrait-conversations-for-pstee


----------------------------------------------------------------------------------------------------------------------------------
Uninstalling:
1. Run Setup-BookOfTorment.exe, Select 'U' to uninstall it.

----------------------------------------------------------------------------------------------------------------------------------
Special thanks for all ideas/inspiration/help to: 
discord channel - grimuar.pl(Grimuar Sferowca); Disco/smeagolheart/Pecca, Bubb, Argent77, lefreut.

----------------------------------------------------------------------------------------------------------------------------------
Desc:
Primarily, this modification was created as a test and in response to the question/need: a side dialogue box.

Mod was create mainly by copy/paste code, trial and error, although sometimes with the help of the kind souls on the forums.


-------------------------
Color clicked responses
-------------------------

I added option to color the clicked responses in Side Dialogue Mode.

Since this option increases the weight of the Baldur.lua configuration file with strings, it is uncertain whether and how it will affect the game;
so it is experimental and optional.

------------------------------------------------------
To turn this on, you must:

Edit the UI.menu file by searching in it, and deleting from the beginning line a "--"

    -- setDlgResponsesColor(worldPlayerDialogSelection)

    ...and save UI.menu.

If problem occurs, just add this "--" again.

------------------------------------------------------
As for slim down conf file: the simplest way is to delete Baldur.lua file, game creates it again, but keep in mind that all set options will back to default.

If you want slim down conf file by yourself: open Baldur.Lua (in my documents), then delete every entry starting with:

    SetPrivateProfileString('Graphics','Dlg Responses Color','1')
    SetPrivateProfileString('Dlg Color String','

Thanks @bbminner for tweaks!

---
https://github.com/szef501/BookOfTorment/releases
https://www.nexusmods.com/planescapetormentenhancededition/mods/9
https://www.gibberlings3.net/forums/topic/36119-uimodplanescape-ee-book-of-torment-discover-the-dialogues-of-torment-in-a-new-edition/

szef, FallDamage312.

