---
statblock: true
layout: Basic 5e Layout
name: Sammaster (Lich Form)
source: FRAiF
size: Medium
type: undead
subtype: wizard
alignment: chaotic evil
ac: 18
hp: 322
hit_dice: 43d8 + 129
speed: 30 ft.
stats:
- 12
- 14
- 16
- 23
- 15
- 21
saves:
- dex: 9
- con: 10
- int: 13
- wis: 9
skillsaves:
- arcana: 20
- history: 13
- perception: 9
damage_resistances: acid, cold, lightning
damage_immunities: necrotic, poison
condition_immunities: charmed, exhaustion, frightened, paralyzed, poisoned
senses: Blindsight 60 ft., Darkvision 120 ft., passive Perception 19
languages: Common, Draconic, Infernal
cr: '22'
traits:
- name: Legendary Resistance (3/Day)
  desc: If Sammaster fails a saving throw, he can choose to succeed instead.
- name: Life Suppression
  desc: Creatures within 60 feet of Sammaster can't regain Hit Points.
- name: Magic Resistance
  desc: Sammaster has Advantage on saving throws against spells and other magical effects.
- name: Soul Gem
  desc: If Sammaster is reduced to 0 Hit Points while his magical soul gem exists, his lich form dissolves to dust. After 1d10 days, he appears in the space of his soul gem, using the Sammaster (Dracolich Form) stat block. The gem is a Tiny object that has AC 20; HP 50; and Immunity to Acid, Necrotic, Poison, and Psychic damage. The gem regains all its Hit Points at the end of every turn, but it turns to dust if reduced to 0 Hit Points. If the gem is destroyed, Sammaster can create a new one by completing an 8-hour ritual using a gem worth 1,000+ GP, which the ritual consumes, and by expending 5,000 GP.
- name: Spellcasting
  desc: |-
    Sammaster casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (spell save DC 21):
    At will: Cone of Cold, Detect Magic, Dispel Magic, Invisibility, Mage Hand, Prestidigitation
    2/day each: Speak with Dead, Wall of Force
    1/day each: Create Undead (level 8 version), Disintegrate, Power Word Kill
- name: Protective Magic
  desc: |-
    Sammaster casts Counterspell or Shield in response to the spell's trigger, using the same spellcasting ability as Spellcasting.
    At will: Counterspell, Shield
actions:
- name: Multiattack
  desc: Sammaster makes three attacks, using Corrosive Burst or Paralyzing Touch in any combination. He can replace two attacks with a use of Spellcasting.
- name: Corrosive Burst
  desc: 'm,r +13, reach 5 ft. or range 120 ft. Hit: 38 (5d12 + 6) Acid or Necrotic damage (Sammaster''s choice).'
- name: Paralyzing Touch
  desc: 'm +13, reach 5 ft. Hit: 16 (3d6 + 6) Cold damage, and the target has the Paralyzed condition until the start of Sammaster''s next turn.'
legendary_actions:
- name: Deathly Teleport
  desc: Sammaster teleports up to 60 feet to an unoccupied space he can see, and each creature within 10 feet of the space he left takes 19 (3d12) Necrotic damage.
- name: Dissolve
  desc: Sammaster makes one Corrosive Burst attack.
- name: Terrifying Presence
  desc: wis DC 21, each creature in a 20-foot Emanation originating from Sammaster.  13 (2d12) Psychic damage, and the target has the Frightened condition until the end of its next turn.  Sammaster can't take this action again until the start of his next turn.
legendary_description: The sammaster (lich form) can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The sammaster (lich form) regains spent legendary actions at the start of its turn.
---
