### Gift Collector

**You can create models that you can then take, create custom rewards and randomly select them.
All with Config!**

**To download Type me: https://discord.com/invite/WNK777rhwg**


[▶️ Full preview](http://madgames.eu/2025-07-04%2017-29-56.mp4)




https://github.com/user-attachments/assets/eb08b70a-a1e5-46c9-a162-271826996da2




### Supported Language
Czech, English

### Commands
• css_recreategift | **Recreate gift on map** (@css/root)

• css_getposition | **Get your actuall position**

• css_reload_gifts | **Reload Gifts config** (@css/root)

• css_addgift <NAME> | **Add new Gift on map and type in config!** (@css/root)

### Config
```json
{
  "model": "models/props/crates/csgo_drop_crate_winteroffensive.vmdl",
  "PickUp_Sound": "sounds/ui/csgo_ui_crate_item_scroll.vsnd",
  "AllowAnimation": true,
  "Animation": "csgo_drop_crate_open",
  "GlowModel": true,
  "Rarity_sound1": "sounds/ui/item_drop2_uncommon.vsnd",
  "Rarity_sound2": "sounds/ui/item_drop3_rare.vsnd",
  "Rarity_sound3": "sounds/ui/item_drop4_mythical.vsnd",
  "Rarity_sound4": "sounds/ui/item_drop5_legendary.vsnd",
  "Rarity_sound5": "sounds/ui/item_drop6_ancient.vsnd",
  "ADs": [
    {
      "pos_x": 663,
      "pos_y": -1168,
      "pos_z": -127,
      "rot_x": 0,
      "rot_y": 0,
      "rot_z": 0,
      "entity": "TSpawnBox",
      "map": "de_mirage"
    }
  ],
  "Rewards": [
    {
      "health": 0,
      "armor": 0,
      "command": "",
      "item": "weapon_ak47",
      "text": "Get AK-47",
      "rarity": 1
    },
    {
      "health": 0,
      "armor": 0,
      "command": "css_ban {PLAYERNAME}",
      "item": "",
      "text": "Get Ban",
      "rarity": 5
    },
    {
      "health": 10,
      "armor": 0,
      "command": "",
      "item": "",
      "text": "+10 HP",
      "rarity": 1
    },
    {
      "health": 0,
      "armor": 10,
      "command": "",
      "item": "",
      "text": "+10 ARMOR",
      "rarity": 1
    },
    {
      "health": 10,
      "armor": 10,
      "command": "",
      "item": "",
      "text": "+10 ARMOR , +10 HP",
      "rarity": 1
    }
  ],
  "ConfigVersion": 1
}```
