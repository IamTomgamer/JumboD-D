---
statblock: true
layout: Basic 5e Layout
name: Drelnza
source: QftIS
size: Medium
type: undead
subtype: vampire
alignment: lawful evil
ac: 18 (plate armor)
hp: 187
hit_dice: 22d8 + 88
speed: 30 ft., climb 30 ft.
stats:
- 18
- 18
- 18
- 17
- 15
- 18
saves:
- dex: 9
- int: 8
- wis: 7
- cha: 9
skillsaves:
- arcana: 8
- deception: 9
- perception: 7
damage_resistances: necrotic
condition_immunities: exhaustion
senses: darkvision 120 ft., passive Perception 17
languages: Abyssal, Common, Giant
cr: '15'
traits:
- name: Legendary Resistance (3/Day)
  desc: If Drelnza fails a saving throw, she can choose to succeed instead.
- name: Special Equipment
  desc: Drelnza wields Heretic.
- name: Spider Climb
  desc: Drelnza can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.
- name: Sunlight Hypersensitivity
  desc: Drelnza takes 20 radiant damage when she starts her turn in sunlight. While in sunlight, she has disadvantage on attack rolls and ability checks.
actions:
- name: Multiattack
  desc: Drelnza makes one Bite attack and one Heretic attack.
- name: Bite
  desc: 'Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. Hit: 7 (1d6 + 4) piercing damage plus 10 (3d6) necrotic damage. The target''s hit point maximum is reduced by an amount equal to the necrotic damage taken, and Drelnza regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. A Humanoid slain in this way and then buried rises the following night as a vampire spawn under Drelnza''s control.'
- name: Heretic
  desc: 'Melee Weapon Attack: +12 to hit, reach 5 ft. one target. Hit: 40 (6d10 + 7) slashing damage, and the target must succeed on a DC 17 Constitution saving throw or have the paralyzed condition until the start of Drelnza''s next turn. Celestials have disadvantage on the saving throw.'
- name: Charm
  desc: |-
    Drelnza targets one Humanoid she can see within 30 feet of herself. The target must succeed on a DC 17 Wisdom saving throw or have the charmed condition. While charmed in this way, the target regards Drelnza as a trusted friend to be heeded and protected. The target isn't under Drelnza's control, but it takes her requests and actions in the most favorable way.
    Each time Drelnza or her allies do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until Drelnza is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect.
reactions:
- name: Move
  desc: Immediately after a creature Drelnza can see ends its turn, Drelnza moves up to her speed without provoking opportunity attacks.
- name: Parry
  desc: Drelnza adds 5 to her AC against one melee attack that would hit her. To do so, she must see the attacker and be wielding a melee weapon.
---
