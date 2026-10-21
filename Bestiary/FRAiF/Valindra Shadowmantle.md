---
statblock: true
layout: Basic 5e Layout
name: Valindra Shadowmantle
source: FRAiF
size: Medium
type: undead
subtype: wizard
alignment: neutral evil
ac: 20
hp: 315
hit_dice: 42d8 + 126
speed: 30 ft.
stats:
- 11
- 16
- 16
- 21
- 14
- 16
saves:
- dex: 10
- con: 10
- int: 12
- wis: 9
skillsaves:
- arcana: 19
- history: 12
- insight: 9
- perception: 9
damage_resistances: cold, lightning
damage_immunities: necrotic, poison
condition_immunities: charmed, exhaustion, frightened, paralyzed, poisoned
senses: Truesight 120 ft., passive Perception 19
languages: all
cr: '21'
traits:
- name: Legendary Resistance (4/Day or 5/Day in Lair)
  desc: If Valindra fails a saving throw, she can choose to succeed instead.
- name: Spirit Gem
  desc: If destroyed, Valindra re-forms in 1d10 days if her spirit gem is intact, reviving with all her Hit Points. The new body appears in an unoccupied space within her lair.
- name: Spellcasting
  desc: |-
    Valindra casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 20):
    At will: Detect Magic, Detect Thoughts, Dispel Magic, Fly, Invisibility, Lightning Bolt (level 5 version), Mage Hand, Prestidigitation
    2/day each: Animate Dead, Plane Shift
    1/day each: Cone of Cold (level 8 version), Finger of Death, Power Word Kill, Scrying
- name: Illusory Disguise
  desc: |-
    Valindra casts Disguise Self, using the same spellcasting ability as Spellcasting. The spell lasts until Valindra drops to 30 Hit Points or fewer or uses her Life-Rending Gaze Legendary Action. Intelligence (Investigation) checks made to discern her true appearance are made with Disadvantage.
    At will: Disguise Self
- name: Protective Magic
  desc: |-
    Valindra casts Counterspell or Shield in response to the spell's trigger, using the same spellcasting ability as Spellcasting.
    At will: Counterspell, Shield
actions:
- name: Multiattack
  desc: Valindra makes three attacks, using Eldritch Burst or Paralyzing Touch in any combination. She can replace two attacks with a use of Spellcasting to cast Lightning Bolt (level 5 version).
- name: Eldritch Burst
  desc: 'm,r +12, reach 5 ft. or range 120 ft. Hit: 31 (4d12 + 5) Force damage.'
- name: Paralyzing Touch
  desc: 'm +12, reach 5 ft. Hit: 14 (2d8 + 5) Cold damage, and the target has the Paralyzed condition until the start of Valindra''s next turn.'
- name: Deathly Grasp (Recharge 5-6)
  desc: 'dex DC 20, each creature in a 30-foot Emanation originating from Valindra. 1 39 (6d12) Force damage and the target has the Restrained condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. Subsequent Failures: 39 (6d12) Necrotic damage, and Valindra gains 20 Temporary Hit Points.'
legendary_actions:
- name: Disrupt Life
  desc: con DC 20, each creature that isn't Undead in a 20-foot Emanation originating from Valindra.  21 (6d6) Necrotic damage.  Half damage.  Valindra can't take this action again until the start of her next turn.
- name: Eldritch Jaunt
  desc: Valindra makes one Eldritch Burst attack. Before or after the attack, Valindra can teleport up to 20 feet to an unoccupied space she can see.
- name: Life-Rending Gaze
  desc: wis DC 20, one creature Valindra can see within 30 feet.  22 (4d10) Necrotic damage, and the target has the Frightened condition until the end of its next turn.  Half damage only.
legendary_description: The valindra shadowmantle can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The valindra shadowmantle regains spent legendary actions at the start of its turn.
---
