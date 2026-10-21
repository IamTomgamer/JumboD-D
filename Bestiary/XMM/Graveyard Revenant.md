---
statblock: true
layout: Basic 5e Layout
name: Graveyard Revenant
source: XMM
size: Huge
type: undead
alignment: neutral
ac: 14
hp: 161
hit_dice: 14d12 + 70
speed: 40 ft.
stats:
- 20
- 14
- 20
- 13
- 16
- 18
saves:
- str: 8
- con: 8
- wis: 6
- cha: 7
damage_resistances: necrotic, psychic
damage_immunities: poison
condition_immunities: charmed, exhaustion, frightened, paralyzed, petrified, poisoned, stunned, unconscious
senses: Darkvision 120 ft., passive Perception 13
languages: Common plus two other languages
cr: '7'
traits:
- name: Undead Restoration
  desc: If the revenant dies, it revives 24 hours later unless Dispel Evil and Good is cast on its remains. If it revives, it animates another group of corpses elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its Hit Points.
actions:
- name: Multiattack
  desc: The revenant makes two Suffocate attacks.
- name: Suffocate
  desc: 'm +8, reach 10 ft. Hit: 10 (1d10 + 5) Bludgeoning damage plus 10 (3d6) Necrotic damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 15). Until the grapple ends, the target is suffocating. The revenant can have up to two targets Grappled in this way at a time.'
- name: Haunting Glare (Recharge 5-6)
  desc: wis DC 15, each creature in a 30-foot Emanation originating from the revenant.  The target has the Paralyzed condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
---
