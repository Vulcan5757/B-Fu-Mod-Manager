# B-Fu Mod Manager
This is a mod manager for Boomerang Fu. It allows you to easily enable &amp; disable mods in game, automatically reboots the game so changes can take effect, and supports previews and descriptions for the mods. It also comes with controller support.

This mod requires BepInEx installed for it to work: [Guide](https://docs.bepinex.dev/articles/user_guide/installation/index.html)

To install, download the latest release [here](https://github.com/Vulcan5757/B-Fu-Mod-Manager/releases), extract the folder, and put it into C:/Program Files (x86)/Steam/steamapps/common/Boomerang Fu/BepInEx/plugins. 

In order for mod previews & descriptions to work in the mod manager each mod (.dll file) must be in it's own subfolder with an info.json following the same format included with this mod. A preview image must also be in the same subfolder to work, and must match the image name specified in the info.json.
For convenience, it's recommended for all mod creators to upload their mods to github in a subfolder including an info.json (and preview image if you want your mod to stand out).

Example info.json format:
{
  "id": "BoomerangFoo",
  "name": "Chaos Mod",
  "author": "FuzzyJeffTheory",
  "version": "0.5.4",
  "description": "A mod for the couch PvP game Boomerang Fu that adds custom gamemodes, powerups, and settings.",
  "preview": "preview.png",
  "repository": "Jeffjewett27/BoomerangFoo"
}


Planned future features: browsable online mod catalog where you can quick install mods and feature to auto check mods for newer releases & quick update them.

<img width="1536" height="864" alt="image" src="https://github.com/user-attachments/assets/d89d6b43-aeaa-4488-90fd-a5bdd5922b15" />
