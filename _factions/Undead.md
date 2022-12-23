---
layout: faction

faction: Undead
ingame_description:
  - Undeads are resilient and tireless, but most importantly, they can't die.
  - Affiliating yourself with the Undead faction will grant you a steady flow of production which increases drastically as time passes.
alignment: Evil
description: Part of the Evil Vanilla Factions, the Undead become more powerful with time. Their Heritage and Bloodline give assistants based on playtime and reincarnations and is more frequently used in late games.
faction_spell: NightTime
upgrades:
  "Tier 1 Upgrades":
    - name: Undead Trade Treaty
      image: "http://musicfamily.org/realm/Factions/picks/UndeadTradeTreaty.png"
      cost: 20 Undead Coins
      effect: Unlocks Undead upgrades.
    - name: The Walking Dead
      image: "http://musicfamily.org/realm/Factions/picks/UndeadUpgrade1.png"
      cost: 50 M (5e7)
      effect: Increase Faction Coin find chance additively based on assistants owned.
      formula: +(ln(1 + x) ^ 1.75)%, where x is assistants owned.
    - name: Deadened Muscles
      image: "http://musicfamily.org/realm/Factions/picks/UndeadUpgrade2.png"
      cost: 500 M (5e8)
      effect: Increase the production of all buildings based on the highest amount of Necropolises you built in this Reincarnation.
      formula: (4 * x ^ 0.8)%, where x is the the highest amount of Necropolises you built in this Reincarnation.
    - name: Death Temples
      image: "http://musicfamily.org/realm/Factions/picks/UndeadUpgrade3.png"
      cost: 5 B (5e9)
      effect: Increase Mana Regeneration additively based on the highest amount of Necropolises you built in this Reincarnation.
      formula: +(x ^ 0.3), where x is the highest amount of Necropolises you built in this Reincarnation.
---
