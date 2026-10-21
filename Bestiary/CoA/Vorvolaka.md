---
statblock: true
layout: Basic 5e Layout
name: Vorvolaka
source: CoA
size: Medium
type: undead
alignment: neutral evil
ac: 18 (natural armor)
hp: 190
hit_dice: 20d8 + 100
speed: 20 ft., fly 50 ft.
stats:
- 15
- 19
- 21
- 8
- 13
- 16
saves:
- con: 10
- wis: 6
skillsaves:
- insight: 6
- perception: 11
- religion: 4
- survival: 6
damage_resistances: bludgeoning, piercing, slashing from nonmagical attacks
damage_immunities: necrotic
condition_immunities: charmed, exhaustion, paralyzed
senses: darkvision 120 ft., passive Perception 21
languages: the languages it knew in life
cr: '14'
traits:
- name: Fear Aura
  desc: Any hostile creature that starts its turn within 20 feet of the vorvolaka must succeed on a DC 18 Wisdom saving throw or have frightened condition until the start of the creature's next turn. If a creature's saving throw is successful, they're immune to the vorvolaka's Fear Aura for the next 24 hours. This ability does not function if the vorvolaka is unconscious.
- name: Magic Resistance
  desc: The vorvolaka has advantage on saving throws against spells and other magical effects.
- name: Regeneration
  desc: The vorvolaka regains 15 hit points at the start of its turn if it has at least 1 hit point. If the vorvolaka takes radiant damage, this trait doesn't function at the start of the vorvolaka's next turn.
actions:
- name: Multiattack
  desc: The vorvolaka makes two Talon attacks. It can replace one of the attacks with Rend Armor (if available).
- name: Talon
  desc: 'Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 22 (4d8 + 4) piercing damage plus 14 (4d6) necrotic damage.'
- name: Rend Armor (Recharge 4-6)
  desc: The vorvolaka makes a Talon attack against a creature. On a hit, the creature's AC is reduced by 2 for 1 minute. Creatures not wearing armor are immune to this effect, and the total reduction can't bring a creature below an AC of 10.
---
