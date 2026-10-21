---
statblock: true
layout: Basic 5e Layout
name: Goblin Psi Commander
source: PaBTSO
size: Small
type: aberration
subtype: goblinoid
alignment: any alignment
ac: 16 (studded leather armor)
hp: 58
hit_dice: 13d6 + 13
speed: 30 ft.
stats:
- 12
- 19
- 13
- 17
- 15
- 10
saves:
- int: 5
- wis: 4
skillsaves:
- stealth: 8
damage_resistances: psychic
senses: darkvision 60 ft., passive Perception 12
languages: Common, Goblin, telepathy 60 ft.
cr: '4'
traits:
- name: Mental Burst
  desc: When the goblin dies, its pent-up mental energy explodes in a psychic blast. Each creature within 5 feet of it must succeed on a DC 13 Intelligence saving throw or take 10 (4d4) psychic damage.
- name: Mental Fortitude
  desc: The goblin has advantage on saving throws against effects that would make it have the charmed or frightened conditions.
- name: Spellcasting (Psionics)
  desc: |-
    The goblin casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 13):
    At will: mage hand (the hand is invisible), minor illusion
    1/day each: charm person, dissonant whispers, telekinesis
actions:
- name: Multiattack
  desc: The goblin makes three Psychic Blade attacks.
- name: Psychic Blade
  desc: 'Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 60 ft., one creature. Hit: 11 (2d6 + 4) psychic damage, and the target must subtract 1d4 from the next attack roll or saving throw it makes before the end of the goblin''s next turn.'
- name: Synaptic Rend (Recharge 5-6)
  desc: The goblin unleashes a 30-foot-radius sphere of psychic energy, centered on a point the goblin can see within 60 feet of itself. Each creature in that area must make a DC 13 Intelligence saving throw. On a failed save, a creature takes 14 (4d6) psychic damage and has the incapacitated condition until the end of the goblin's next turn. On a successful save, a creature takes half as much damage only.
bonus_actions:
- name: Nimble Escape
  desc: The goblin takes the Disengage or Hide action.
reactions:
- name: Psionic Shield
  desc: When the goblin or one of its allies within 15 feet of it is hit by an attack roll, the goblin conjures a shield of force. The target of the attack gains a +3 bonus to its AC against the triggering attack roll, potentially causing it to miss.
---
