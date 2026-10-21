---
statblock: true
layout: Basic 5e Layout
name: Usagt
source: AitFR-THP
size: Medium
type: aberration
subtype: shapeshifter
alignment: lawful neutral
ac: 12
hp: 97
hit_dice: 13d8 + 39
speed: 30 ft.
stats:
- 10
- 15
- 16
- 15
- 20
- 12
saves:
- int: 5
- wis: 8
- cha: 4
skillsaves:
- history: 5
- insight: 8
- perception: 8
- performance: 7
- stealth: 5
damage_resistances: bludgeoning, piercing, slashing from nonmagical attacks
senses: darkvision 100 ft., passive Perception 18
languages: all, telepathy 30 ft.
cr: '5'
traits:
- name: Invisibility
  desc: The usagt's true form is invisible.
- name: Shapechanger
  desc: The usagt can use its action to polymorph into a Small, Medium, or Large humanoid it has seen in person or telepathically, or back into its true form. Its statistics, other than its size, are the same in each form. While polymorphed, the usagt is not invisible. Its new form appears to wear clothes, carry equipment, and even wield weapons, but these are all parts of the usagt itself; they vanish if dropped or removed from the creature. It can't activate, use, wield, or otherwise benefit from any of its apparent equipment. It reverts to its true form if it dies.
- name: Innate Spellcasting
  desc: |-
    The usagt's innate spellcasting ability is Charisma (spell save DC 15). It can cast the following spells, requiring no spell components:
    At will: banishment, detect thoughts, disguise self
actions:
- name: Multiattack
  desc: The usagt makes two attacks with its claws.
- name: Claws
  desc: 'Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (2d4 + 2) slashing damage plus 11 (2d6 + 4) psychic damage.'
- name: Personal Insight
  desc: |-
    The usagt targets one creature it can see within 30 feet of it. The target must contest its Charisma (Deception) check against the usagt's Wisdom (Insight) check.
    The target has advantage on the roll if it is immune to being charmed. A target can choose to fail this check.
    If the usagt wins, it magically learns the identity of a creature from the target's past, someone the target wishes it could speak to again or with whom the target has left something unsaid. If somehow no such creature exists in the target's past, the usagt learns that instead.
reactions:
- name: Invisibility Response (Recharges When the Usagt Uses Its Shapechanger Ability)
  desc: When the usagt takes damage, it can choose to revert to its default, invisible form and move up to 15 feet without provoking opportunity attacks.
---
