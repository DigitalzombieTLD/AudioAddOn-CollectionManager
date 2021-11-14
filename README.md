# AudioAddOn-CollectionManager v0.8
Tool to manage audio collections for TLD

# Prerequisites:
- MelonLoader
- AudioCore Plugin: https://github.com/DigitalzombieTLD/AudioCore
- AudioAddOn Mod: TBD

![alt text](https://github.com/DigitalzombieTLD/AudioAddOn-CollectionManager/blob/main/CollectionManager_HowTo.jpg)

# What is it?
This tool can help you to create & manage installed "audio collections" for the TLD mod "AudioAddOn".

# What are audio collections?
Audio collections help in sorting audioclips for different audio categories. 
With this everyone can create and share custom audio for TLD with ease.

# What does "custom audio" mean?
We've got different categories of audio. Voice / Music / Radio

A custom [voice collection] overwrites any voiceover line of the character ingame.
Say for example: You want to change what Mackenzie/Astrid say when picking up an object, you can do that.
Any "event" that got no clip in this category, won't have any voicelines anymore. You don't need to have
clips for every single event, but you don't need different voices playing when mixing them with the originals either.

There is no distinction between male and female collections. You can choose the active collection, independently of your 
character choice, in the ingame modsettings menu.

If any event got multiple clips, it will be choosen on random which one gets played ingame.

A custom [music collection] works almost the same way. Difference: Events without custom clips will play the original music.

Custom [radio collections] determine which audio is player on the radio during the aurora.

# Which file formats are supported?
At this time only .ogg files are supported. Please use only mono files, as stereo would mess with the 3D effects ingame.

# Where is the save button?
Collections are immediately saved after creation. Audioclips are copied instantly after selection. You don't need to save manually.

# Attention!!!
If you delete a collections, it will get deleted instantly and with all audioclips. You won't be able to restore it. 
If you delete an audioclip from a collection, it too will get deleted without the possibility of retrieval.
Please make sure you make a copy of all audioclips you want to keep.
# Attention!!!

# How does it work?
The tool manages the correct folder structure for audiofiles to use with the AudioAddOn mod. If creates the right hierarchy with folder names
and sorts audioclips accordingly. Audioclips get copied with their original name to the correct folder.
Folder structure can be created/changed manually. This tool is not strictly neccessary, but will hopefully make peoples lifes just a little bit easier.

# Known bugs
- List of audio clips doesn't always update correctly after adding a new clip. Click the open button of the event again to update it manually.

# Links
My YouTube channel: https://www.youtube.com/channel/UCYRu_uDOzozbXIXKGrznHxQ
Me on reddit: https://www.reddit.com/user/DigiZombie
TLD modlist: https://xpazeman.com/tld-mod-list/
The TLD modding Discord: https://discord.gg/AqpW9TjUfr
