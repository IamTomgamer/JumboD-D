---
statblock: true
layout: Basic 5e Layout
name: Tarrasque
source: XMM
size: Gargantuan
type: monstrosity
subtype: titan
alignment: unaligned
ac: 25
hp: 697
hit_dice: 34d20 + 340
speed: 60 ft., burrow 40 ft., climb 60 ft.
stats:
- 30
- 11
- 30
- 3
- 11
- 11
saves:
- dex: 9
- int: 5
- wis: 9
- cha: 9
skillsaves:
- perception: 9
damage_resistances: bludgeoning, piercing, slashing
damage_immunities: fire, poison
condition_immunities: charmed, deafened, frightened, paralyzed, poisoned
senses: Blindsight 120 ft., passive Perception 19
languages: —
cr: '30'
traits:
- name: Legendary Resistance (6/Day)
  desc: If the tarrasque fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The tarrasque has Advantage on saving throws against spells and other magical effects.
- name: Reflective Carapace
  desc: If the tarrasque is targeted by a Magic Missile spell or a spell that requires a ranged attack roll, roll 1d6. On a 1-5, the tarrasque is unaffected. On a 6, the tarrasque is unaffected and reflects the spell, turning the caster into the target.
- name: Siege Monster
  desc: The tarrasque deals double damage to objects and structures.
actions:
- name: Multiattack
  desc: The tarrasque makes one Bite attack and three other attacks, using Claw or Tail in any combination.
- name: Bite
  desc: 'm +19, reach 15 ft. Hit: 36 (4d12 + 10) Piercing damage, and the target has the Grappled condition (escape DC 20). Until the grapple ends, the target has the Restrained condition and can''t teleport.'
- name: Claw
  desc: 'm +19, reach 15 ft. Hit: 28 (4d8 + 10) Slashing damage.'
- name: Tail
  desc: 'm +19, reach 30 ft. Hit: 23 (3d8 + 10) Bludgeoning damage. If the target is a Huge or smaller creature, it has the Prone condition.'
- name: Thunderous Bellow (Recharge 5-6)
  desc: con DC 27, each creature and each object that isn't being worn or carried in a 150-foot Cone.  78 (12d12) Thunder damage, and the target has the Deafened and Frightened conditions until the end of its next turn.  Half damage only.
bonus_actions:
- name: Swallow
  desc: |-
    str DC 27, one Large or smaller creature Grappled by the tarrasque (it can have up to six creatures swallowed at a time).  The target is swallowed, and the Grappled condition ends. A swallowed creature has the Blinded and Restrained conditions and can't teleport, it has Total Cover against attacks and other effects outside the tarrasque, and it takes 56 (16d6) Acid damage at the start of each of the tarrasque's turns.
    If the tarrasque takes 60 damage or more on a single turn from a creature inside it, the tarrasque must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the tarrasque and has the Prone condition. If the tarrasque dies, any swallowed creature no longer has the Restrained condition and can escape from the corpse using 20 feet of movement, exiting Prone.
legendary_actions:
- name: Onslaught
  desc: The tarrasque moves up to half its Speed, and it makes one Claw or Tail attack.
- name: World-Shaking Movement
  desc: The tarrasque moves up to its Speed. At the end of this movement, the tarrasque creates an instantaneous shock wave in a 60-foot Emanation originating from itself. Creatures in that area lose Concentration and, if Medium or smaller, have the Prone condition. The tarrasque can't take this action again until the start of its next turn.
legendary_description: The tarrasque can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The tarrasque regains spent legendary actions at the start of its turn.
---
