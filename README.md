### Gift Collector

**You can create models that you can then take, create custom rewards and randomly select them.
All with Config!**

**To download Type me: https://discord.com/invite/WNK777rhwg**


[▶️ Full preview](http://madgames.eu/2025-07-04%2017-29-56.mp4)

https://github.com/user-attachments/assets/14f04c0c-9802-41f2-8c1a-2d3e2b4dd5a4




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
  "PickUp_Sound": "sounds/ui/counter_beep.vsnd",
  "AllowAnimation": true,
  "Animation": "csgo_drop_crate_open",
  "GlowModel": true,
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
      "text": "Get AK-47"
    },
    {
      "health": 0,
      "armor": 0,
      "command": "css_ban {PLAYERNAME}",
      "item": "",
      "text": "Get Ban"
    },
    {
      "health": 10,
      "armor": 0,
      "command": "",
      "item": "",
      "text": "+10 HP"
    },
    {
      "health": 0,
      "armor": 10,
      "command": "",
      "item": "",
      "text": "+10 ARMOR"
    },
    {
      "health": 10,
      "armor": 10,
      "command": "",
      "item": "",
      "text": "+10 ARMOR , +10 HP"
    }
  ],
  "ConfigVersion": 1
}```
