# Necessary mods
mod descriptions (with slight edits from mac) yoinked from their mod page

**Required**<br>mods that are required to be on client or death

[![image-20220214140039410](/home/macimas/.config/Typora/typora-user-images/image-20220214140039410.png)Fabrication](https://www.curseforge.com/minecraft/mc-mods/fabrication) - A huge collection of vanilla tweaks and small features. Trident improvements, bug fixes, furnace minecart changes, and more<br>[![image-20220214140035766](/home/macimas/.config/Typora/typora-user-images/image-20220214140035766.png)Diggus Maximus](https://www.curseforge.com/minecraft/mc-mods/diggus-maximus) -  Quick and easy "Vein Mining".<br> ^ this mod might actually not be required. if not, it will be moved to the Recommended section

[Repurposed Structures](https://www.modrinth.com/mod/repurposed-structures-fabric) - Adds more variations of vanilla structures and features such as a Jungle Fortress!<br>[![image-20220214140030596](/home/macimas/.config/Typora/typora-user-images/image-20220214140030596.png)Gate of Babylon](https://www.curseforge.com/minecraft/mc-mods/gate-of-babylon) - Mod that adds in a bunch of new weapons & gear.<br>[![image-20220214140028621](/home/macimas/.config/Typora/typora-user-images/image-20220214140028621.png)Staff of Building](https://www.curseforge.com/minecraft/mc-mods/staff-of-building) - Adds staffs which can be used to speed up building<br>[Universal Graves](https://www.modrinth.com/mod/universal-graves) - Customizable grave mod for Fabric!<br>[![image-20220214140021980](/home/macimas/.config/Typora/typora-user-images/image-20220214140021980.png)Fixed Waterlogging](https://www.curseforge.com/minecraft/mc-mods/fixed-waterlogging) - Adds waterlogging to almost all blocks that could need it<br>[![image-20220214140025868](/home/macimas/.config/Typora/typora-user-images/image-20220214140025868.png)Enchant the Rainbow](https://www.curseforge.com/minecraft/mc-mods/enchant-the-rainbow) - Choose the enchantment glint color for your enchanted items!<br>

**Dependencies** (aka Required the Sequel)<br>mods that are required by other mods or smth

[Fabric API](https://www.modrinth.com/mod/fabric-api) - Core API library for the Fabric toolchain<br>
[![img](https://external-content.duckduckgo.com/ip3/www.curseforge.com.ico)Architectury API](https://www.curseforge.com/minecraft/mc-mods/architectury-fabric) - An intermediary api aimed to ease developing multiplatform mods.<br>
[![img](https://external-content.duckduckgo.com/ip3/www.curseforge.com.ico)Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config) - A config screen api.<br>
^ may be moved to misc branch as this is not required. might be wrong on this one

[![img](https://external-content.duckduckgo.com/ip3/www.curseforge.com.ico)GeckoLib](https://www.curseforge.com/minecraft/mc-mods/geckolib) - A 3D animation library for entities, blocks, items, armor, and more!<br>[![img](https://external-content.duckduckgo.com/ip3/www.curseforge.com.ico)Feature NBT Deadlock Be Gone](https://www.curseforge.com/minecraft/mc-mods/feature-nbt-deadlock-be-gone) - Fixes deadlocks caused by https://bugs.mojang.com/browse/MC-246262<br>[![img](https://external-content.duckduckgo.com/ip3/www.curseforge.com.ico)No Null Processors](https://www.curseforge.com/minecraft/mc-mods/no-null-processors) - Fixes structure crash in 1.17+ due to null processor lists coming from nowhere<br>

**Recommended**<br>mods that aren't required but is important for smth like improving gameplay without changing things too much

[AppleSkin](https://www.modrinth.com/mod/appleskin) - Food/hunger-related HUD improvements <br>[EditSign](https://www.modrinth.com/mod/editsign) - Allows you to edit signs without destroying them.<br>[![img](https://external-content.duckduckgo.com/ip3/www.curseforge.com.ico)Roughly Enough Items](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items) - An easy way to browse recipes.<br>
[![img](https://external-content.duckduckgo.com/ip3/www.curseforge.com.ico)Roughly Enough Resources](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-resources) - Worldgen support for Roughly Enough Items<br>[![image-20220214140849002](/home/macimas/.config/Typora/typora-user-images/image-20220214140849002.png)Xaero's World Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map) - Adds a fullscreen worldmap which shows you what you have explored in the world.<br>[![image-20220214140853882](/home/macimas/.config/Typora/typora-user-images/image-20220214140853882.png)Xaero's Minimap](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap) - Displays the nearby world terrain, players, mobs, entities in the corner of your screen. <br>[WTHIT](https://www.modrinth.com/mod/wthit) - What the hell is that?<br>[Mod Menu](https://www.modrinth.com/mod/modmenu) - Adds a mod menu to view the list of mods you have installed.<br>[Mouse Wheelie](https://www.modrinth.com/mod/mouse-wheelie/versions) - A "small" client-side mod featuring item scrolling, inventory sorting, item refilling and more!

**Optimization**<br>See [optimization branch](https://github.com/bittermc/modpack/tree/optimization).

**Miscellaneous**<br>See [misc branch](https://github.com/bittermc/modpack/tree/misc).

**Not recommended**<br>mods that are for some reason not yeeted off this modpack but is listed as not recommended to be used. you should have at least put this section in the misc branch (you even added that you *might* move the only mod in this section to the misc branch) but instead you did this. good grief mac

[![img](https://external-content.duckduckgo.com/ip3/www.curseforge.com.ico)Fabrilous Updater](https://www.curseforge.com/minecraft/mc-mods/fabrilous-updater) - Easy update-checker for Fabric mods.<br>
 ^ may be moved to misc branch as this is not necessary<br>
 ^ may be replaced with another mod with similar features<br>
 ^ may be removed as mods in client-side may be too new with new features that might break parity with server until server-side mods are updated. might be wrong on this one

**Recent changes**

```````diff
* Update mods
+ Added Feature NBT Deadlock Be Gone and No Null Processors as dependecies for Repurposed Structures
+ Added Gate of Babylon
+ Added Xaero's World Map and Minimap
- Removed Alternative Current as it's only required in server-side
