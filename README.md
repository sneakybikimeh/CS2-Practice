# CS2's Practice Config
This practice.cfg file lets you setup a practice server very simple to tweak through console with visual feedback for CS2.
It comes with two additional files containing utility aliases.

# Installation
1. Open the archive and extract its content into the following path folder : 
...\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\

3. Launch the game, boot up a practice server where you can turn on sv_cheats 1 and type in the console the following command: "exec practice.cfg".

4. Your console should display the GUI and a sound will be played in-game; otherwise you must have a path issue and the file did not load correctly.

# Usage
- A self explanatory documentation will be displayed into the GUI in your console under this format :
VARS (STATUS) | ToggleCmd / ToggleOnCmd / ToggleOffCmd

- Toggle practice mode ON and OFF by simply typing "practice" in your console for example.

- Type helpprac to display the GUI in your console in order to see the current status of the vars.

- Type give_[nameofitem] to get it dropped instantly. (alias_stuff.cfg)
- Type [nameofmap] to change map instantly. (alias_maps.cfg)

- Everytime you change map, you will need to "exec practice.cfg" since the server convars are overwritten.
- The GUI will not keep in memory any var that is changed manually in the console.
