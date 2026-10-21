---
statblock: true
layout: Basic 5e Layout
name: Hazlik
source: RHW
size: Medium
type: humanoid
subtype: human, wizard
alignment: chaotic evil
ac: 16
hp: 154
hit_dice: 28d8 + 28
speed: 30 ft.
stats:
- 10
- 16
- 12
- 20
- 15
- 16
saves:
- int: 10
- wis: 7
skillsaves:
- arcana: 10
- history: 10
- perception: 7
damage_immunities: psychic
condition_immunities: charmed
senses: passive Perception 17
languages: Abyssal, Common, Draconic, Giant, Infernal, Undercommon
cr: '14'
traits:
- name: Darklord Restoration
  desc: If Hazlik dies, he revives with all his Hit Points in 1d10 weeks somewhere in Hazlan.
- name: Legendary Resistance (3/Day, or 4/Day in Domain)
  desc: If Hazlik fails a saving throw, he can choose to succeed instead.
- name: Magic Resistance
  desc: Hazlik has Advantage on saving throws against spells and other magical effects.
- name: Spellcasting
  desc: |-
    Hazlik casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 18):
    At will: Detect Magic, Detect Thoughts, Disguise Self, Invisibility, Light, Mage Armor (included in AC), Mage Hand, Prestidigitation
    2/day each: Fly, Lightning Bolt (level 5 version)
    1/day each: Cone of Cold, Mind Blank (cast before combat), Scrying, Teleport
- name: Protective Magic (3/Day)
  desc: |-
    Hazlik casts Counterspell or Shield in response to the spell's trigger, using the same spellcasting ability as Spellcasting.
    3/day: Counterspell, Shield
actions:
- name: Multiattack
  desc: Hazlik makes three Arcane Burst attacks.
- name: Arcane Burst
  desc: 'm,r +10, reach 5 ft. or range 150 ft. Hit: 21 (3d10 + 5) Force damage.'
bonus_actions:
- name: Wild Magic Surge
  desc: |-
    Hazlik manifests one of the following magic surges, targeting a creature he can see within 120 feet. While Bloodied, Hazlik manifests two surges (roll 1d4; reroll if Hazlik has already used that surge during this turn):
    - **1: Misty Movement** Hazlik can teleport the target up to 30 feet to an unoccupied space he can see on a surface or liquid large enough to support the target.
    - **2: Eye Blight** con DC 18.  The target has the Blinded condition until the end of its next turn.
    - **3: Mind Flare** int DC 18.  13 (2d12) Psychic damage, and the target can't take the Magic action until the end of its next turn.
    - **4: Implode** dex DC 18.  The target takes 10 (3d6) Force damage.  Each creature within 5 feet of the target takes 10 (3d6) Force damage.
legendary_actions:
- name: Arcane Strike
  desc: Hazlik makes one Arcane Burst attack.
- name: Arcane Teleport
  desc: Hazlik teleports up to 60 feet to an unoccupied space he can see, and each creature within 10 feet of the space he left takes 11 (2d10) Force damage. Hazlik can't take this action again until the start of his next turn.
legendary_description: The hazlik can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The hazlik regains spent legendary actions at the start of its turn.
---
