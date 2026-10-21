---
statblock: true
layout: Basic 5e Layout
name: Behir
source: XMM
size: Huge
type: monstrosity
alignment: neutral evil
ac: 17
hp: 168
hit_dice: 16d12 + 64
speed: 50 ft., climb 50 ft.
stats:
- 23
- 16
- 18
- 7
- 14
- 12
skillsaves:
- perception: 6
- stealth: 7
damage_immunities: lightning
senses: Darkvision 90 ft., passive Perception 16
languages: Draconic
cr: '11'
actions:
- name: Multiattack
  desc: The behir makes one Bite attack and uses Constrict.
- name: Bite
  desc: 'm +10, reach 10 ft. Hit: 19 (2d12 + 6) Piercing damage plus 11 (2d10) Lightning damage.'
- name: Constrict
  desc: str DC 18, one Large or smaller creature the behir can see within 5 feet.  28 (5d8 + 6) Bludgeoning damage. The target has the Grappled condition (escape DC 16), and it has the Restrained condition until the grapple ends.
- name: Lightning Breath (Recharge 5-6)
  desc: dex DC 16, each creature in a 90-foot-long, 5-foot-wide Line.  66 (12d10) Lightning damage.  Half damage.
bonus_actions:
- name: Swallow
  desc: |-
    dex DC 18, one Large or smaller creature Grappled by the behir (the behir can have only one creature swallowed at a time).  The behir swallows the target, which is no longer Grappled. While swallowed, a creature has the Blinded and Restrained conditions, has Total Cover against attacks and other effects outside the behir, and takes 21 (6d6) Acid damage at the start of each of the behir's turns.
    If the behir takes 30 damage or more on a single turn from the swallowed creature, the behir must succeed on a DC 14 Constitution saving throw at the end of that turn or regurgitate the creature, which falls in a space within 10 feet of the behir and has the Prone condition. If the behir dies, a swallowed creature is no longer Restrained and can escape from the corpse by using 15 feet of movement, exiting Prone.
---
