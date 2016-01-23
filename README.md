 Short description:
 
 nt2mice.pie - script for desktop computers
 nt2mice.pie_laptop - script for laptops
 nt2key.pie - script for keyboard only player 2
 
 Supported operating systems:
 
 Windows 7
 Windows 8/8.1
 Windows 10
 
 Requirements:
 
 PPJoy 0.8.4.6
 GlovePIE 0.45
 XBOX360 Controller Emulator
 
 Long sescription:
 
This tutorial is for Windows operating systems. Tested on Windows 7/8.1/10.
Presumably does not work on Windows XP for some reason (needs confirmation)
If you find ways to do it on other operating systems, message me, I will put a link to your guide or your information here.

Tools you will need:

PPJoy 0.8.4.6
http://uploaded.net/file/fzhe96kn

GlovePIE 0.45
http://glovepie.org/lpghjkwer.php

XBOX360 Controller Emulator (preconfigured)
https://mega.nz/#!Op5HkSxJ!-fztAvWSTh08sthXEn-F37ZZIkOZRNlsmQMeBn79zXM
or
X360CE
http://www.x360ce.com/

Step 1. Installing PPJoy.

Run ppjoy setup.

--------------------------------------------------
[This part concerns only 64 bit operating systems. If you're using a 32 bit OS, skip until after the next line of dashes!]

The setup will display a window saying your OS does not allow installation of unsigned drivers. Click OK
Then a window will pop up saying configuration data is updated. On clicking OK YOUR COMPUTER WILL REBOOT
After the reboot, run setup again.

Warning! PPJoy drivers are not digitally signed. Installing PPJoy will put your computer into "test mode" that allows installation of unsigned drivers. It's not really considered dangerous, and you shouldn't have a problem with it, but I still recommend that you read up on that to understand the risks should there be any. But If for some reason you don't want your pc running in "test mode", don't use this guide.

If you disable test mode after installation, the driver won't run = you can't play.

If you're no longer playing NT with two mice though, it would be sensible to disable test mode, even if only to get rid of the watermark. Which is easily done, use microsoft's guide.
https://support.microsoft.com/en-us/kb/2509241
----------------------------------------------------

Follow instructions of the installer

During setup a couple of scary red messages will pop up, informing you that the driver is not signed, click "install anyway"

After setup finishes, uncheck "run PPJoy joystick driver" and reboot again to be on the safe side.

Now you should have PPJoystick Driver category in your start menu.

Run "Configure Joysticks"

Click "Add"

In the next window under "Parallel port" select "Virtual Joysticks". Controller number - controller 1

Click "add"

Select "PPJoy Virtual Joystick 1 under "configured joysticks"

Click "Mapping"

In the next window select "Modify the mapping for this controller", click "Next"

Select 4 axes, 8 buttons, 0 POV hats

All the rest should be set by default, but check nonetheless:

Axis 1 - X axis
Axis 2 - Y Axis
Axis 3 - Z Axis
Axis 4 - Z rotation

click "Next"

X Axis - Analog 0
Y Axis - Analog 1
Z Axis - Analog 2
Z Rotation - Analog 3

click "Next"

buttons 1 to 8 - Digital 0 to 7

click "Next"

click "Finish"

click "Done"

Step 2. Installing XBOX360 Controller Emulator

Unzip files from xinputemu3.zip to Nuclear Throne Root folder (On Steam: right click Nuclear Throne in your Steam library and go to Properties. Go to Local Files tab.
Click Browse local files. This will open the Nuclear Throne files folder.)

Note: If you want to use x360ce instead of xinputemu3, set up your layout like this in x360ce program:
Left Trigger - button 2
Right Trigger - button 1
Y button - button 3
X button - button 4
Left Stick Axis X - Axis 6
Left Stick Axis Y - Axis 3
Right Stick Axis X - Axis 1
Right Stick Axis Y - Inverted Axis 2

Step 3. Setting up GlovePIE

Unzip glovePIE to any desired location.

Set glovepie to run as administrator (Right click on PIEFree.exe => Compatibility tab => Check "run program as administrator" box => Apply)

run PIEFree.exe

File => Open

Select the "nt2mice.PIE" script from where you saved it

If you're playing on a laptop select "nt2mice_laptop.pie" instead, unless you want to play with touchpad.

We're good to go!


Step 4. Play the game

Plug in the other mouse.
DO NOT PLUG IN PS/2 MOUSE WHILE COMPUTER IS ON
Note: The mice I used were both USB. Supposedly it shouldn't matter if both mice are USB or one is PS/2 (or COM, or whatever), but you never really know for sure.

Click on "Run" button in glovePie (one of the mice will stop responding after that. The one that keeps responding will be player 1 mouse. It's always hard to tell which mouse will be considered primary by windows from the start, but the one plugged in last will always be second. Use F2 key to switch mice around.)

Launch Nuclear Throne

If everything is all right, the second mouse should be operational (Not in the menu though, but that's how NT handles it. You select characters with "move left" and "move right" keys)

So every time you want to play with 2 mice, you 1) launch GlovePIE 2)Open nt2mice script 3)Press "run" 4)Launch the game

To return your computer controls to normal state, simply press "stop" in GlovePIE


Controls:

Nuclear throne has controls all over the keyboard (wasd AND arrow keys AND numpad), which makes it kind of complicated, because even if you have two keyboards, you can't use the same keys for both players.

Note: As of update 95 it's possible to remap controls in-game, which allows to easily customize player 1 keys. However, the alternative control sets are still hardcoded in, so basically this gives us nothing.

Luckily, it stops recognizing numpad keys when NumLock is on, while GlovePIE does not. So basic rig is one guy on the left side with WASD, the other on the other end with numpad (don't forget to switch NumLock ON), to give each player maximum room if you are playing with a single keyboard.
If your keyboard does not have a NumPad, you can use OKL; keys or edit the script and map your own keys (explained further), it's no rocket science.

Note: I'm not sure if it works at all, but it would most likely be a good idea to set gamepad autoaim to 0 in Nuclear Throne options menu

Note: Allegedly, using the same keys on two keyboards for two different players is possible on Windows XP (see here http://www.glovepie.org/w/index.php?title=Preliminary_Documentation_v0.43#Multiple_Keyboards ). I have not tried it, so you're on your own here. If you try it and make a script for it, write in the comments, I'll update this tutorial

Note: Even with a mouse player 2 is somewhat inferior to player 1 due to limited cursor boundaries and cursor jumping over the character. Maybe ask the devs to make it switchable in the options?

General controls:

F2: Switch mice around

Player 1 controls:

Left bracket: Player 1 mouse sensitivity -

Right bracket: Player 1 mouse sensitivity +


Player 2 controls:

NOTE: Keep NumLock ON If you want to use numpad keys

Aim: Second Mouse

Fire: Left Mouse Button

Special: Right Mouse Button

Swap Weapon: Mouse wheel / Mouse middle button / Numpad 0 / N

Pick Up: Numpad + / '


Up: Numpad 8 / O

Down: Numpad 5 / L

Left: Numpad 4 / K

Right: Numpad 6 / ;

- : Player 2 mouse sensitivity -

= : Player 2 mouse sensitivity +

Customization

To adjust mouse sensitivity permanently you'll have to open the nt2mice.pie script with a text editor (like notepad), or just do everything in GlovePIE window (script must NOT be running).

Then change the values at the end of line 2 for Player 1 mouse; and line 3 - for Player 2 mouse

Change "1.0" in each of these lines to lesser or higher value to increase or decrease sensitivity.
Example: 1.5 will increase sensitivity by 50%
0.9 will decrease sensitivity by 10%

To assign your own keys:

You can add lines like "ppjoy.digital2 = Keyboard.X" to nt2mice.pie, where
ppjoy.digital0 stands for fire
ppjoy.digital1 stands for special
ppjoy.digital2 stands for weapon swap
ppjoy.digital3 stands for weapon pickup
(in this example X key will swap weapons). It is pretty self-explanatory.
Movement is slightly more complex, there have to be two keys in one line
You can add lines like "PPJoy1.Analog2 = - Keyboard.X + Keyboard.Z" to nt2mice.pie, where
PPJoy1.Analog2 stands for up-down movement
PPJoy1.Analog3 stands for left-right movement
(in this example X key will move character down, Z key will move character up)
All key names: http://www.glovepie.org/w/index.php?title=Preliminary_Documentation_v0.45#Number_Keys
Don't forget that mapping a key that is already in use by player 1 or the game is a bad idea.


Keyboard only

If you don't have a spare mouse and want to play coop with one mouse and one keyboard, you can use another script nt2key.pie
https://mega.nz/#!y4ZGADaZ!7J6OrdfhuT0wJNs3hdfyGSbhqe2TZejF8EPbc4nQ1bw
This is by no means recommended unless you are masochistic or regular game is just not challenging enough for you.
Controls (Keep NumLock ON):
Aim: Numpad
Move: OKL;
Fire: Right Alt / Numpad 0
Special: N / Numpad Enter
Pick up weapon: /(slash) / Left Bracket
Swap weapons: Numpad Plus / '
Toggle cursor closer/farther away: Numpad -
The difference between this script and something you can easily do in any joystick emulation software is that key combinations like Numpad7+Numpad8 will provide additional aiming angles.
Too many simultaneous keypresses will mess up your game with unresponsive keys. Use Right Alt as your fire button, because Numpad 0 is more prone to that.

Known issues:
There's been reports of an issue where after loading the script in glovePIE all buttons on both mice stop responding. If this happens, press ALT+F4. It will close glovePIE window, which will revert your controls back to normal. 
Reasons for this behavior are unknown, and so are the reasons for it fixing itself. It possibly goes away after you reboot your PC with both mice connected. If you can provide clues on this situation, it would be much appreciated.


With some minor tweaking (button and axis mapping) this tutorial should be applicable to any game that supports 360 controllers.

To do list:
- WinXP support for the script
- Support for 2 keyboards in WinXP

Credits

Thanks go to

Carl Kenner for his wonderful free GlovePIE software
http://glovepie.org/

Deon van der Westhuysen for his wonderful free PPJoy software

Racer_S for his great free XBOX360 Controller Emulator
http://www.tocaedit.com/

zd_ for his MousePad script
https://github.com/zd/MousePad

hristotodorov for his Mouse to Joystick script
https://sites.google.com/site/hristotodorov/mousetojoystick

GlovePIE Community
http://glovepie.org/forum/


Change History
v1.1 - Mousewheels now operational
v1.2 - Sensitivity customization added
v1.3 - Added keys to control sensitivity in-game
v1.31 - Sensitivity does not go below 0
v1.4 - Added a key to switch mice around

Contacts

Tutorial by Rigel. Contact me: fakeidmail@yandex.ru

P.S. You can thank me with a spare copy of Nuclear Throne. Just sayin'. 
