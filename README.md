# pfUI \[darkmod\]

**Do not install this extension unless you know what you're doing!**

The pfUI-darkmod is an example pfUI module that statically configures pfUI. Its purpose is for developers who want to modify pfUI without changing the addon core itself. This addon and its source-code are intended to give developers an idea of how to use the API, hook functions and change basic alignments of pfUI.

If you're not a developer on your own but like the darkmod as is, feel free to use it. But be aware that you are out of support and on your own.

Since this addon force-overwrites options, functions and positions that are usually set by pfUI, you might not be able to use those options within the pfUI settings dialog anymore without troubles.

## Screenshots
<img src="https://raw.githubusercontent.com/shagu/ShaguAddons/master/_img/pfUI-darkmod/castbar.jpg" align="right" width="48.87%">
<img src="https://raw.githubusercontent.com/shagu/ShaguAddons/master/_img/pfUI-darkmod/solo.jpg" width="48.87%">
<img src="https://raw.githubusercontent.com/shagu/ShaguAddons/master/_img/pfUI-darkmod/group.jpg" align="right" width="48.87%">
<img src="https://raw.githubusercontent.com/shagu/ShaguAddons/master/_img/pfUI-darkmod/raidloot.jpg" width="48.87%">

## Dependency
You need to have pfUI installed. Learn more how to download & install pfUI [HERE](https://shagu.org/pfUI).

## Installation
1. Download **[Latest Version](https://github.com/shagu/pfUI-darkmod/archive/master.zip)**
2. Unpack the Zip file
3. Rename the folder "pfUI-darkmod-master" to "pfUI-darkmod"
4. Copy "pfUI-darkmod" into Wow-Directory\Interface\AddOns
5. Make sure to have your screen resolution set to **"1920x1080"** (*)
6. Restart Wow Client
7. Select and Load the "pfUI darkmod" profile inside the pfUI settings

*) If you have another screen resolution, you might have to adjust the UIScale on your own to have everything fit together

## Supported Addons
* [DPSMate](https://github.com/Geigerkind/DPSMate) A Combat Analyzation Tool
* [KLHThreatMeter (KTM)](http://addons.us.to/addon/klhthreatmeter-0) A Threat Meter

## What is it doing?
#### Move Chat Frames
* Move left chat to the bottom-left without padding.
* Move right chat to the bottom-right without padding.

#### Draw Dark Bottom Line
* add a black gradient to the bottom and stretch it up to the chat-tab-bar.

#### Strech Viewport
* stretch the viewport by cutting off a few pixels at the bottom to not have the bottom gradient eat too much space and have the character more centered.

#### Autosize and Move Chat Input Box
* make chatinput box fit between chat docks.

#### Autosize and Move Castbar
* make the castbar fit between both chat docks.
* move the target castbar into the center of the screen.

#### Autosize and Move XP/Reputation
* adjust xp and reputation bar height.

#### Move Buffs
* move buffs to the topright of the screen.

#### Autosize and Move Minimap
* move the minimap to the center bottom.

#### Move Actionbars
* move the main actionbar bar to the minimap.
* move the top actionbar above the main actionbar.
* move the left actionbar to the right of minimap.
* move the right actionbar above the left actionbar.
* set the position of the shapeshift/stance bars to the right of the screen.
* set the position of the petactionbars to the right of the screen.

#### Move UnitFrames
* move the playerframe above the left actionbars.
* move the targetframe above the right actionbars.
* move the targettargetframe above the minimap.
* move the pet unitframe slightly higher to not have it collide with the castbar.
* set the position of all raidframes to the top of the left chat panel.
* set the position of all groupframes to the top of the left chat panel.

#### Merge Tracking Icon Into Chat-Tab
* move/merge the tracking icon into the right chattab panel.
* also set its parent to make it vanish when the meters are shown.

#### Move Loot Rolls
* set the position of all loot rolls to the top of the right chat panel.
* also decrease the spacing and make the width same as the panel.

#### Create Top Panel Background
* create a backdrop of the size and appearance of a chat tab dock.
* make the new backdrop toggle when the meters are shown by hooking the
