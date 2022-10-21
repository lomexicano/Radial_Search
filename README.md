# Radial_Search
##### A simple MKB script to search for a block nearby. It searches within a rectangular prism that can be customized.

- **Installation**
	- Open Minecraft singleplayer;
	- Open the Macro KeyBind Mod keyboard screen;
	- Open one of the gray keys;
	- Type the following code:
		 `$$<Radial_Search.txt>`
	- Click the button `Edit File`;
	- Type `Radial_Search` and press `Create`;
	- Paste the script and Save.
- **Usage**
	- The script is easy to custom. You can change the ID of the item you are looking for, the 2d (XZ plane) radius up to which you'd like to search and also the vertical limits (making it a rectangular prism).
	- To test it out the way it is, just go in Minecraft Singleplayer and place a `bed` somewhere near you, then run the script.
	  - The nearer you are to the bed, the faster the script will find it. 

	- The 2.0 version brings the possibility to display particles in order to locate the target faster (after it is found), and in order to visualize what blocks the script is reading. For this to happen, there is the need to download the Klacaiba Module, which can be found [here](https://spthiel.github.io/Modules/).
<br />

### References:
- [Macro KeyBind Mod](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1275039-macro-keybind-mod), the mod used to run this script ~ by [Mumfrey](https://github.com/mumfrey)
- [LiteLoader](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1290155-liteloader), the mod loader required to use this mod ~ by [Mumfrey](https://github.com/mumfrey)
- [Unofficial documentation](https://beta.mkb.gorlem.ml/docs/actions/), containing lots of information about the custom programming language created by the mod ~ by [Gorlem](https://github.com/Gorlem/)  
- [MKB Syntax Highlighting](https://github.com/KeeMeng/MKB-Syntax-Highlighting), a plugin for the software Sublime Text that provides lots of features to programmers of this language ~ by [KeeMeng (TKM)](https://github.com/KeeMeng) 
- [Klacaiba](https://github.com/spthiel/klacaiba), a module for the MKB mod that allows to display particles on the specified coordinates, without the use of chat commands. It also contains many other features that were not used by this script ~ by [Elspeth](http://github.com/spthiel) 
