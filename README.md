# 🎆 Hit Landing Effects 🎆   

🎇 Mod allows to play custom animations and sounds for post-shot bursts, where it looks appropriate (fireballs, lighning bolts and other magical projectiles).  

🎇 All settings are configurable in one script and are tied to creature type, not projectile type. The customization is pretty flexible, one can make both strict pairs and universal rules alike. Siege towers are affected by same settings as the creatures inside.  

🎇 Melee attacks are also supported, but due to technical limitations are played at the start of attacker's swing, not at defender's hit like shots. Hence all the melee defs should have some amount of 'empty' frames at the beginning, allowing to artificially delay the burst triggering. Also keep in mind that game plays spell defs mirrored to what they appear in .pac, so don't forget to mirror your animations for melee bursts from right to left before adding (see the defs included in the mod for reference).  

🎇 Mod includes a resource folder with 125 burst defs which use same colors and can be mixed and matched before recoloring to fit your creatures. You can reverse the frame order for more interesting results as well, also don't forget to end your every burst def with an empty frame. The sounds in .snd are nothing new (except few HotA ones), it's just a selection of vanilla sounds that could potentially fit for a burst. They are there as a library so you have easier time creating your own hit effects.  

## ⚠️  W A R N I N G  ⚠️     
If you are using Amethyst in your mod, or have enabled some other mod based on it (Knightmare Kingdoms, TUM and all its variations, Alternative Upgrade etc), then you shouldn't use Melee Resistance/Shooting Resistance fields in AmeEdit, since it will prevent this plugin from playing its bursts. Instead you should set the damage resistances at the bottom part of same script where main bursts are customized. This will also fix Amethyst battle tooltip to display correct theoretical damage. So do a folder search for "resitance=" in Creatures folder and manually correct each case.

## ___🌟 Included Creatures:___
🔅 __Monk__ *(melee and ranged bursts)*  
🔅 __Zealot__ *(melee and ranged bursts)*  
🔅 __Angel__ *(melee burst)*  
🔅 __Archangel__ *(melee burst)*  
🔅 __Supreme Archangel__ *(melee burst)*  
🔅 __Unicorn__ *(melee burst)*  
🔅 __War Unicorn__ *(melee burst)*  
🔅 __Mage__ *(ranged burst)*  
🔅 __Arch Mage__ *(ranged burst)*   
🔅 __Genie__ *(melee burst)*  
🔅 __Master Genie__ *(melee burst)*  
🔅 __Giant__ *(melee burst)*  
🔅 __Titan__ *(melee and ranged bursts)*  
🔅 __Lord of Thunder__ *(melee and ranged bursts)*  
🔅 __Gog__ *(ranged burst)*  
🔅 __Efreeti__ *(melee burst)*  
🔅 __Efreet Sultan__ *(melee burst)*  
🔅 __Archdevil__ *(melee burst)*  
🔅 __Hell Baron__ *(melee burst)*  
🔅 __Wight__ *(melee burst)*  
🔅 __Wraith__ *(melee burst)*   
🔅 __Lich__ *(ranged burst, for towers only since Death Cloud will prevent it from playing, same reason Magog was skipped)*  
🔅 __Ghost Dragon__ *(melee burst)*  
🔅 __Beholder__ *(melee and ranged bursts)*  
🔅 __Evil Eye__ *(melee and ranged bursts)*  
🔅 __Thunderbird__ *(melee burst)*  
🔅 __Cyclops__ *(ranged burst)*  
🔅 __Cyclops King__ *(ranged burst)*  
🔅 __Ghost Behemoth__ *(melee burst)*  
🔅 __Dragon Fly__ *(melee burst)*  
🔅 __Gorgon__ *(melee burst)*  
🔅 __Mighty Gorgon__ *(melee burst)*  
🔅 __Pixie__ *(melee burst)*  
🔅 __Sprite__ *(melee burst)*  
🔅 __Air Elemental__ *(melee burst)*  
🔅 __Storm Elemental__ *(melee and ranged bursts)*  
🔅 __Ice Elemental__ *(ranged burst)*  
🔅 __Fire Elemental__ *(melee burst)*  
🔅 __Energy Elemental__ *(melee burst)*  
🔅 __Crystal Dragon__ *(melee burst)*  
🔅 __Enchanter__ *(ranged burst)*  
🔅 __Ghost__ *(melee burst)*  
🔅 __War Zealot__ *(melee and ranged bursts)*  
🔅 __Arctic Sharpshooter__ *(ranged burst)*  
🔅 __Lava Sharpshooter__ *(ranged burst)*  
🔅 __Santa Gremlin__ *(melee burst)*  
🔅 __Sorceress__ *(melee and ranged bursts)*  
🔅 __Werewolf__ *(melee burst)*  
🔅 __Hierophant__ *(melee and ranged bursts)*  
🔅 __Succubus__ *(melee and ranged bursts)*  
🔅 __Soul Eater__ *(ranged burst)*  
🔅 __Brute__ *(ranged burst)*  
🔅 __Shaman__ *(ranged burst)*  
🔅 __Astral Spirit__ *(melee and ranged bursts)*  

💥 ___Authors:___  
*JackSlater*, *Raistlin* - the main plugin  
*Dalion* - graphics and sounds selection  
*Archer30* - script workaround to bypass incompatibility with damage resistance fields of Amethyst  
(but the manual adjustment of every config where they were set ___is still required___)  

###### Inspired by similar functionality from HotA.  
