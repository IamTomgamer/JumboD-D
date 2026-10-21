---
statblock: true
layout: Basic 5e Layout
name: Haunting Revenant
source: XMM
size: Gargantuan
type: undead
alignment: neutral
ac: 20
hp: 203
hit_dice: 14d20 + 56
speed: 30 ft.
stats:
- 20
- 12
- 18
- 16
- 18
- 20
saves:
- con: 8
- wis: 8
damage_resistances: necrotic, psychic
damage_immunities: poison
condition_immunities: charmed, exhaustion, frightened, grappled, paralyzed, petrified, poisoned, prone, restrained, unconscious
senses: Truesight 60 ft., passive Perception 14
languages: Common plus two other languages
cr: '10'
traits:
- name: Haunted Zone
  desc: con DC 17, any creature that casts a spell while inside the revenant's space.  The spell fails and is wasted.
- name: Undead Restoration
  desc: If the revenant dies, it revives 24 hours later unless Dispel Evil and Good is cast on its remains. If it revives, it animates another Gargantuan object or structure elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its Hit Points.
actions:
- name: Multiattack
  desc: The revenant makes two Object Slam attacks and uses Invitation.
- name: Object Slam
  desc: 'm,r +9 (with Advantage if the target is inside the revenant''s space), reach 10 ft. or range 30/90 ft. Hit: 27 (5d8 + 5) Bludgeoning damage.'
- name: Invitation
  desc: |-
    cha DC 17, each creature in a 60-foot Cone.  The target is teleported inside the revenant's space and swallowed. A swallowed creature has Total Cover against attacks and other effects outside the revenant.
    While the revenant has Hit Points, a swallowed creature can leave the revenant's space only by using magic that enables planar travel, such as the Plane Shift spell.
---
