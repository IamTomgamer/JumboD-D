---
statblock: true
layout: Basic 5e Layout
name: Blob of Annihilation
source: XMM
size: Gargantuan
type: ooze
subtype: titan
alignment: neutral evil
ac: 18
hp: 448
hit_dice: 23d20 + 207
speed: 30 ft.
stats:
- 27
- 14
- 28
- 10
- 16
- 10
saves:
- dex: 9
- con: 16
damage_resistances: bludgeoning, piercing, slashing
damage_immunities: acid, necrotic, poison
condition_immunities: charmed, exhaustion, frightened, grappled, paralyzed, petrified, poisoned, prone, restrained, stunned, unconscious
senses: Blindsight 120 ft., passive Perception 13
languages: —
cr: '23'
traits:
- name: Astral Implosion
  desc: If the blob is reduced to 0 Hit Points, it implodes and ejects any creatures and objects engulfed by it into the Astral Sea. The blob itself vanishes, leaving behind a layer of slime on everything that was within 600 feet of it. In 1d20 years, the blob reconstitutes on a random world in the Material Plane.
- name: Legendary Resistance (4/Day)
  desc: If the blob fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The blob has Advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The blob makes two Pseudopod attacks and uses Engulf. It can replace one attack with a use of Restraining Glob.
- name: Pseudopod
  desc: 'm +15, reach 30 ft. Hit: 24 (3d10 + 8) Force damage.'
- name: Engulf
  desc: |-
    The blob moves up to its Speed and can move through the spaces of Huge or smaller creatures and objects. str DC 23, each creature or object whose space the blob enters for the first time during this move.  The target is engulfed. While engulfed, a target has Total Cover against attacks and other effects outside the blob, and when the blob moves, the engulfed target moves with it. A nonmagical object is destroyed after spending 1 minute engulfed.
    While engulfed, a creature takes 21 (6d6) Force damage at the start of each of its turns, is suffocating, has the Restrained condition, and repeats the save at the end of each of its turns. An engulfed creature that is reduced to 0 Hit Points dissolves into ash, which is ejected into the Astral Sea.  The target escapes and enters the nearest unoccupied space.
- name: Restraining Glob
  desc: The blob lobs a slimy glob at one Large or smaller creature it can see within 600 feet of itself. dex DC 23, the targeted creature.  18 (3d6 + 8) Acid damage. The glob rolls the target 60 feet straight toward the blob, and the target has the Restrained condition until the end of its next turn, when the glob harmlessly dissolves.  Half damage only.
legendary_actions:
- name: Decay
  desc: The blob deals 14 (4d6) Necrotic damage to each creature engulfed by it. The blob can't take this action again until the start of its next turn.
- name: Grasping Glob
  desc: The blob uses Restraining Glob. The blob can't take this action again until the start of its next turn.
- name: Lashing Goop
  desc: The blob makes one Pseudopod attack.
legendary_description: The blob of annihilation can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The blob of annihilation regains spent legendary actions at the start of its turn.
---
