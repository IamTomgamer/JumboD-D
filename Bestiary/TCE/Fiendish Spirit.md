---
statblock: true
layout: Basic 5e Layout
name: Fiendish Spirit
source: TCE
size: Large
type: fiend
alignment: unaligned
ac: 12 + the level of the spell (natural armor)
hp: 50 (Demon only) or 40 (Devil only) or 60 (Yugoloth only) + 15 for each spell level above 6th
speed: 40 ft., climb 40 ft. (demon only), fly 60 ft. (devil only)
stats:
- 13
- 16
- 15
- 10
- 10
- 16
damage_resistances: fire
damage_immunities: poison
condition_immunities: poisoned
senses: darkvision 60 ft., passive Perception 10
languages: Abyssal, Infernal, telepathy 60 ft.
cr: ''
traits:
- name: Magic Resistance
  desc: The fiend has advantage on saving throws against spells and other magical effects.
- name: Death Throes (Demon Only)
  desc: When the fiend drops to 0 hit points or the spell ends, the fiend explodes, and each creature within 10 feet of it must make a Dexterity saving throw against your spell save DC. A creature takes 2d10 + summonSpellLevel fire damage on a failed save, or half as much damage on a successful one.
- name: Devil's Sight (Devil Only)
  desc: Magical darkness doesn't impede the fiend's darkvision.
actions:
- name: Multiattack
  desc: The fiend makes a number of attacks equal to half this spell's level (rounded down).
- name: Bite (Demon Only)
  desc: 'Melee Weapon Attack:  to hit, reach 5 ft., one target. Hit: 1d12 + 3 + summonSpellLevel necrotic damage.'
- name: Claws (Yugoloth Only)
  desc: 'Melee Weapon Attack:  to hit, reach 5 ft., one target. Hit: 1d8 + 3 + summonSpellLevel slashing damage. Immediately after the attack hits or misses, the fiend can magically teleport up to 30 feet to an unoccupied space it can see.'
- name: Hurl Flame (Devil Only)
  desc: 'Ranged Spell Attack:  to hit, range 150 ft., one target. Hit: 2d6 + 3 + summonSpellLevel fire damage. If the target is a flammable object that isn''t being worn or carried, it also catches fire.'
---
