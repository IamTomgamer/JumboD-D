---
statblock: true
layout: Basic 5e Layout
name: Hlam
source: WDH
size: Medium
type: humanoid
subtype: human
alignment: lawful good
ac: 22 (Unarmored Defense)
hp: 137
hit_dice: 25d8 + 25
speed: 60 ft.
stats:
- 11
- 24
- 13
- 14
- 21
- 14
saves:
- str: 5
- dex: 12
skillsaves:
- athletics: 5
- religion: 7
damage_immunities: poison
condition_immunities: charmed, frightened, poisoned, disease
senses: passive Perception 15
languages: all spoken languages
cr: '16'
traits:
- name: Evasion
  desc: If Hlam is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, he instead takes no damage if he succeeds on the saving throw, and only half damage if he fails. He can't use this trait if he's incapacitated.
- name: Magic Attacks
  desc: Hlam's unarmed strikes are magical.
- name: Unarmored Defense
  desc: While Hlam is wearing no armor and wielding no shield, his AC includes his Wisdom modifier.
- name: Spellcasting
  desc: |-
    Hlam is a 5th-level spellcaster. His spellcasting ability is Wisdom (spell save DC 18, +10 to hit with spell attacks) He has the following cleric spells prepared:
    Cantrips (at will): guidance, light, sacred flame, spare the dying
    1st level (4 slots): detect evil and good, healing word, sanctuary, shield of faith
    2nd level (3 slots): calm emotions, prayer of healing, silence
    3rd level (2 slots): protection from energy, remove curse, sending
actions:
- name: Multiattack
  desc: Hlam attacks three times using his unarmed strike, darts, or both.
- name: Unarmed Strike
  desc: |-
    Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 12 (1d10 + 7) bludgeoning, magic damage. If the target is a creature, Hlam can choose one of the following additional effects:
    The target must succeed on a DC 18 Strength saving throw or drop one item it is holding (Hlam's choice).
    The target must succeed on a DC 18 Dexterity saving throw or be knocked prone.
    The target must succeed on a DC 18 Constitution saving throw or be stunned until the end of Hlam's next turn.
- name: Dart
  desc: 'Ranged Weapon Attack: +12 to hit, range 20/60 ft., one target. Hit: 9 (1d4 + 7) piercing damage.'
- name: Quivering Palm (Recharge 6)
  desc: 'Melee Weapon Attack: +12 to hit, reach 5 ft., one creature. Hit: The target must make a DC 18 Constitution saving throw. On a failed save, the target is reduced to 0 hit points. On a successful save, the target takes 55 (10d10) necrotic damage.'
- name: Wholeness of Body (Recharges after a Long Rest)
  desc: Hlam regains 60 hit points.
reactions:
- name: Deflect Missile
  desc: In response to being hit by a ranged weapon attack, Hlam deflects the missile. The damage he takes from the attack is reduced by 1d10 + 27. If the damage is reduced to 0, Hlam catches the missile if it's small enough to hold in one hand and he has a hand free.
- name: Slow Fall
  desc: Hlam reduces the bludgeoning damage he takes from a fall by 100.
legendary_actions:
- name: Quick Step
  desc: Hlam moves up to his speed without provoking opportunity attacks.
- name: Unarmed Strike (Costs 2 Actions)
  desc: Hlam makes one unarmed strike.
- name: Invisibility (Costs 3 Actions)
  desc: Hlam becomes invisible until the end of his next turn. The effect ends if Hlam attacks or casts a spell.
legendary_description: The hlam can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The hlam regains spent legendary actions at the start of its turn.
---
