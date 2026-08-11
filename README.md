# Artifacts of Myth

Artifacts of Myth adds powerful, myth-inspired relics to your game, each with powerful effects.

## Last Major Updates: 1.9
- Added Shinto (Japanese) artifacts with gamerule control
- Supported Version is now 1.19.*
- Added Reseed Missing Artifacts with gamerule control which reseeds missing artifacts every 5 years by default but can be changed to 10 years or disabled

## Artifact Spawn Conditions
- **Norse** artifacts will spawn with Asatru rulers, and if none of those exist, then North Germanic rulers  
- **Greco-Roman** artifacts will spawn with Greek rulers  
- **Abrahamic** artifacts will spawn with their respective rulers, whether that be Christianity, Islam, or Judaism  
- **Celtic** artifacts will spawn with Goidelic rulers  
- **Arthurian** artifacts will spawn with Brythonic rulers  
- **Finno-Ugric** artifacts will spawn with Finno-Ugric rulers, and if none of those exist, then Balto-Finnic / Ugro-Permian / Volga-Finnic rulers  
- **Slavic** artifacts will spawn with Slavic rulers, and if none of those exist, then West Slavic / East Slavic rulers  
- **Lovecraftian** artifacts will spawn with lunatic / possessed / eccentric characters  
- **Mesopotamian** artifacts will spawn with Caucasian / Syriac / Iranian rulers  
- **Egyptian** artifacts will spawn with Egyptian and East African rulers  
- **Chinese** artifacts will spawn with Chinese / Qiangic / Tibetan rulers  
- **Easter Egg** artifacts will spawn with any rulers
- **Shinto (Japanese)** artifacts will spawn with Japonic rulers

## Planned Development
- Hindu (Indian) artifacts with gamerule control  
- Tengri (Mongol) artifacts with gamerule control  
- Artifact search  
- Cultural/religious artifact acquisition  

Inspired by *More Unique Artifacts* and the many great CK2 artifact mods.

The art is generated using ChatGPT's image tools, with editing by me.

French, German, Russian, Simplified Chinese, and Spanish localization is machine-translated through Google Translate and ChatGPT.

Overwrites the following vanilla files and code:
```
game/common/character_interactions/00_artifact_interactions.txt: destroy_artifact_interaction
game/common/customizable_localization/ledger_custom_loc.txt: artifact_rarity_ledger
game/localization/english/inventory/inventory_l_english.yml: ARTIFACT_RARITY_AND_TYPE
game/localization/english/inventory/inventory_l_english.yml: ARTIFACT_RARITY_AND_SLOT_TYPE
game/gui/window_inventory.gui: InventoryViewTypes.icon_artifact
game/gui/window_inventory.gui: InventoryViewTypes.button_artifact
game/gfx/interface/icons/artifact/artifact_bg.dds
```

Should be compatible with most mods, except total conversions.

**Hope you enjoy!**
