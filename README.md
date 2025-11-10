botを作成
```txt
/npc create PvPKitBot
```
↓を実行
```txt
# ホットバー 0-8
/npc cmdadd -c console -t right replaceitem entity %player% slot.hotbar.0 minecraft:diamond_sword{Enchantments:[{id:"minecraft:sharpness",lvl:5},{id:"minecraft:knockback",lvl:2}]} 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.hotbar.1 minecraft:stone 64
/npc cmdadd -c console -t right replaceitem entity %player% slot.hotbar.2 minecraft:stone 64
/npc cmdadd -c console -t right replaceitem entity %player% slot.hotbar.3 minecraft:stone_pickaxe 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.hotbar.4 minecraft:ender_pearl 16
/npc cmdadd -c console -t right replaceitem entity %player% slot.hotbar.5 minecraft:totem_of_undying 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.hotbar.6 minecraft:totem_of_undying 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.hotbar.7 minecraft:totem_of_undying 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.hotbar.8 minecraft:totem_of_undying 1

# インベントリ 9-35
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.9 minecraft:totem_of_undying 5
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.10 minecraft:totem_of_undying 5
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.11 minecraft:totem_of_undying 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.12 minecraft:obsidian 64
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.13 minecraft:end_crystal 16
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.14 minecraft:end_crystal 32
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.15 minecraft:respawn_anchor 32
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.16 minecraft:glowstone 64
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.17 minecraft:golden_apple 10
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.18 minecraft:water_bucket 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.19 minecraft:splash_potion{Potion:"minecraft:strong_strength"} 2
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.20 minecraft:cobweb 16
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.21 minecraft:bow 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.22 minecraft:arrow 64
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.23 minecraft:potion{Potion:"minecraft:fire_resistance"} 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.24 minecraft:ender_chest 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.25 minecraft:tnt 16
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.26 minecraft:obsidian 64
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.27 minecraft:stone 64
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.28 minecraft:snowball 16
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.29 minecraft:slime_ball 16
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.30 minecraft:lava_bucket 1
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.31 minecraft:golden_carrot 16
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.32 minecraft:splash_potion{Potion:"minecraft:swiftness"} 2
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.33 minecraft:potion{Potion:"minecraft:healing"} 2
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.34 minecraft:cobblestone 64
/npc cmdadd -c console -t right replaceitem entity %player% slot.inventory.35 minecraft:stone_sword 1

```
