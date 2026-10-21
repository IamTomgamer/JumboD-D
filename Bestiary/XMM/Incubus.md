---
statblock: true
layout: Basic 5e Layout
name: Incubus
source: XMM
size: Medium
type: fiend
alignment: neutral evil
ac: 15
hp: 66
hit_dice: 12d8 + 12
speed: 30 ft., fly 60 ft.
stats:
- 8
- 17
- 13
- 15
- 12
- 20
skillsaves:
- deception: 9
- insight: 5
- perception: 5
- persuasion: 9
- stealth: 7
damage_resistances: cold, fire, poison, psychic
senses: Darkvision 60 ft., passive Perception 15
languages: Abyssal, Common, Infernal; telepathy 60 ft.
cr: '4'
traits:
- name: Succubus Form
  desc: When the incubus finishes a Long Rest, it can shape-shift into a Succubus, using that stat block instead of this one. Any equipment it's wearing or carrying isn't transformed.
- name: Spellcasting
  desc: |-
    The incubus casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 15):
    At will: Disguise Self, Etherealness
    1/day each: Dream, Hypnotic Pattern
actions:
- name: Multiattack
  desc: The incubus makes two Restless Touch attacks.
- name: Restless Touch
  desc: 'm +7, reach 5 ft. Hit: 15 (3d6 + 5) Psychic damage, and the target is cursed for 24 hours or until the incubus dies. Until the curse ends, the target gains no benefit from finishing Short Rests.'
bonus_actions:
- name: Nightmare (Recharge 6)
  desc: wis DC 15, one creature the incubus can see within 60 feet.  If the target has 20 Hit Points or fewer, it has the Unconscious condition for 1 hour, until it takes damage, or until a creature within 5 feet of it takes an action to wake it. Otherwise, the target takes 18 (4d8) Psychic damage.
---
