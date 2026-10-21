---
statblock: true
layout: Basic 5e Layout
name: Spitting Mimic
source: IDRotF
size: Large
type: monstrosity
subtype: shapechanger
alignment: neutral
ac: 14 (natural armor)
hp: 85
hit_dice: 10d10 + 30
speed: 20 ft.
stats:
- 21
- 12
- 17
- 9
- 15
- 10
skillsaves:
- stealth: 7
damage_immunities: acid
condition_immunities: prone
senses: darkvision 60 ft., passive Perception 12
languages: —
cr: '5'
traits:
- name: Shapechanger
  desc: The mimic can use its action to polymorph into an object or back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
- name: Adhesive (Object Form Only)
  desc: The mimic adheres to anything that touches it. A Huge or smaller creature adhered to the mimic is also grappled by it (escape DC 16). Ability checks made to escape this grapple have disadvantage.
- name: False Appearance (Object Form Only)
  desc: While the mimic remains motionless, it is indistinguishable from an ordinary object.
- name: Grappler
  desc: The mimic has advantage on attack rolls against any creature grappled by it.
- name: Magic Resistance
  desc: The mimic has advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: 'The mimic attacks three times: twice with its pseudopods and once with its bite.'
- name: Pseudopods
  desc: 'Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 10 (1d10 + 5) bludgeoning damage. If the mimic is in object form, the target is subjected to its Adhesive trait.'
- name: Bite
  desc: 'Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 10 (1d10 + 5) piercing damage plus 7 (2d6) acid damage.'
- name: Spit Acid (Recharge 5-6)
  desc: The mimic spits acid at one creature it can see within 30 feet of it. The target must make a DC 14 Dexterity saving throw, taking 32 (9d6 + 1) acid damage on failed save, or half as much damage on a successful one.
---
