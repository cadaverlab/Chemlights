 #########   ########   ########     ########   ###      ###  ##########  ########
##########  ##########  ##########  ##########  ###      ###  ##########  ##########
###         ###    ###  ###    ###  ###    ###   ###    ###   ###         ###    ###
###         ###    ###  ###    ###  ###    ###   ###    ###   ########    ##########
###         ##########  ###    ###  ##########    ###  ###    ########    ########
###         ##########  ###    ###  ##########    ###  ###    ###         ###  ###
##########  ###    ###  ##########  ###    ###     ######     ##########  ###   ###
 #########  ###    ###  ########    ###    ###      ####      ##########  ###    ###

CHEMLIGHTS for Ostranauts
By Cadaver. MIT licence.

Phoebus-brand chemical lights in cyan, blue, red and green, sold in bundles
of five at station supply kiosks, and found in derelicts and police kits.

Crack one and it lights up fully within seconds. It stays bright for a while,
then fades over 30 minutes of game time, goes out, and crumbles to ash that
is gone two minutes later. Hold it to light your way, or drop it to mark a
route through a dark derelict.

You can eat one. Don't. It makes you sick to your stomach and gives you a dose
of radiation, sometimes enough for radiation sickness.


INSTALL

There are two parts. The data mod adds the items. The plugin makes them fade
and burn out. Install both.

1. The data mod
   Workshop: subscribe, then enable ChemLights in the game's Mods menu.
   By hand: copy this folder to Ostranauts_Data/Mods/ChemLights and add
   "ChemLights" to aLoadOrder in Ostranauts_Data/Mods/loading_order.json.

2. The plugin (needs BepInEx 5 installed in the game folder)
   Copy BepInEx/plugins/ChemLights/ChemLights.dll from this folder into
   BepInEx/plugins/ChemLights/ in the game folder. The workshop can't do
   this step for you.

To get some, open the console (backtick key) and type
   spawn ItmChemLightBundle01Cyan
or Blue, Red, Green in place of Cyan.


USING THEM

Bundle      Open it like a pill bottle and drag the sticks out first. If you
            crack one inside the bundle, it falls at your feet. An empty
            bundle turns into trash.
Crack       Right-click a sealed stick and pick Crack.
Equip       Hold a lit stick to light the way in its colour.
Carry       A lit stick in a pocket or on a suit clip still glows, dimmer.
            In your backpack it glows through, dimmer still.
Drop        Drag it onto the floor next to you, or pick Drop.
Eat         Works on any stick, even with your helmet on.

Sealed sticks stack up to five, like pills.
