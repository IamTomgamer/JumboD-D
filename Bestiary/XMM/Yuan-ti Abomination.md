---
statblock: true
layout: Basic 5e Layout
name: Yuan-ti Abomination
source: XMM
size: Large
type: monstrosity
alignment: neutral evil
ac: 15
hp: 127
hit_dice: 15d10 + 45
speed: 40 ft., climb 30 ft.
stats:
- 19
- 16
- 17
- 17
- 18
- 15
skillsaves:
- perception: 7
- stealth: 6
damage_immunities: poison
condition_immunities: poisoned
senses: Darkvision 60 ft., passive Perception 17
languages: Abyssal, Common, Draconic
cr: '7'
traits:
- name: Magic Resistance
  desc: The yuan-ti has Advantage on saving throws against spells and other magical effects.
- name: Spellcasting (Yuan-ti Form Only)
  desc: |-
    The yuan-ti casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 15):
    At will: Animal Friendship (snakes only)
    3/day: Suggestion
actions:
- name: Multiattack
  desc: The yuan-ti makes two Bite attacks, and it can use Spellcasting to cast Suggestion if available.
- name: Bite
  desc: 'm +7, reach 5 ft. Hit: 11 (2d6 + 4) Piercing damage plus 10 (3d6) Poison damage.'
- name: Constrict
  desc: str DC 15, one Large or smaller creature within 5 feet.  28 (7d6 + 4) Bludgeoning damage. The target has the Grappled condition (escape DC 14), and it has the Restrained condition until the grapple ends.  Half damage only.
- name: Poison Spray (Recharge 5-6)
  desc: con DC 14, each creature in a 30-foot Cone.  21 (6d6) Poison damage, and the target has the Poisoned condition until the end of the yuan-ti's next turn. While Poisoned, the target has the Blinded condition.  Half damage only.
bonus_actions:
- name: Shape-Shift
  desc: The yuan-ti shape-shifts into a Large snake or returns to its true form. If it dies, it stays in its current form. The yuan-ti's game statistics are the same in each form, except where noted. Any equipment it is wearing or carrying isn't transformed.
---
