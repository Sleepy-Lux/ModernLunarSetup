## 💙 Lux's modern LunarClient guide for Performance & QOL
This is how I, Lux as probably a T3 *(I'll get tested once I don't have covid)* play modern Minecraft (1.18+)

### Install LunarClient
> https://www.lunarclient.com/download

### How to open the mods folder in LunarClient
<p float="center">
  <img src="https://github.com/Sleepy-Lux/ModernLunarSetup/blob/main/Data/1.png" width="49%" />
  <img src="https://github.com/Sleepy-Lux/ModernLunarSetup/blob/main/Data/2.png" width="49%" /> 
</p>

<p float="center">
  <img src="https://github.com/Sleepy-Lux/ModernLunarSetup/blob/main/Data/3.png" width="49%" />
  <img src="https://github.com/Sleepy-Lux/ModernLunarSetup/blob/main/Data/4..png" width="49%" /> 
</p>

### Install my custom profile
<details>
  <summary>
    Basic Install (Deletes your profile)
  </summary>
  
  1. Download my basic profile zip [here](https://github.com/Sleepy-Lux/ModernLunarSetup/blob/main/Data/Basic-SleepyLuxProfile.zip)
  2. Extract the content into this folder `%USERPROFILE%\.lunarclient\settings\game\Default`
  3. Press "Replace the file in the destination"
  4. You're done!

</details>
<details>
  <summary>
    Advanced Install (Adds a new profile)
  </summary>

  1. Download my advanced profile zip [here](https://github.com/Sleepy-Lux/ModernLunarSetup/blob/main/Data/Advanced-SleepyLuxProfile.zip)
  2. Extract the content into this folder `%USERPROFILE%\.lunarclient\settings\game\`
  3. In that path open `profile_manager.json`
  4. Add the following json element before the final `]` and after the final `}` <br> `{"name":"SleepyLux","displayName":"SleepyLux","default":false,"active":true,"iconName":"apple","server":""}`
  5. You're done!
  
</details>

##

### Install my extra mods

| Type? | Mod Download | Description |
| ----- | ----- | ----- |
| Dependency | [Placeholder API](https://modrinth.com/mod/placeholder-api) | Allows ModMenu and others to use placeholders |
| Dependency | [Cloth Config](https://modrinth.com/mod/cloth-config) | Configuration library for a lot of mods |
| Dependency | [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin) | Allows mods which use Kotlin to work |
| Dependency | [MaLiLib](https://modrinth.com/mod/malilib/versions) | Allows use of Litematica |
| Dependency | [Architectury API](https://modrinth.com/mod/architectury-api) | Allows use of REI |
| Performance | [Nvidium](https://modrinth.com/mod/nvidium) | Uses NVIDIA Cuda & mesh shaders to render chunks extremely efficiently |
| Performance | [FastChest](https://modrinth.com/mod/fastchest) | Renders containers as blocks to significantly improve fps if many are present |
| QOL | [ModMenu](https://modrinth.com/mod/modmenu) | Shows a list of all installed mods *Highly recommended* |
| QOL | [Sodium Extra](https://modrinth.com/mod/sodium-extra) | Adds all the missing options from Optifine into Sodium |
| QOL | [Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options) | Reworks Sodium's UX design to be much nicer |
| QOL | [Bobby](https://modrinth.com/mod/bobby) | Allows much higher than default render distance *Works well with Nvidium* |
| Useful | [Roughly Enough Items](https://modrinth.com/mod/rei) | Allows you to see crafting recipes and such from your inventory |
| Useful | [Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat) | Proximity chat on supported servers |
| Useful | [Litematica](https://modrinth.com/mod/litematica) | Allows you to place building schematics into the world |
| Aesthetic | [Capes](https://modrinth.com/mod/capes) | Shows all cape types on players (Optifine, Labymod, etc) |
| Aesthetic | [Wavey Capes](https://modrinth.com/mod/wavey-capes) | Adds a wavey physics to capes |
| Feature | [Continuity](https://modrinth.com/mod/continuity) | Adds support for Optifine connected textures |
| Feature | [Fabric Skyboxes](https://modrinth.com/mod/fabricskyboxes) | Adds support for custom skyboxes including Optifine skyboxes |
| Feature | [OptiGUI](https://modrinth.com/mod/optigui) | Adds support for Optifine custom GUI's |
| Feature | [CIT Resawn](https://modrinth.com/mod/cit-resewn) | Adds support for MCPatcher & Optifine custom item models |