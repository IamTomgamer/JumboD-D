---
statblock: true
layout: Basic 5e Layout
name: Kraken
source: XMM
size: Gargantuan
type: monstrosity
subtype: titan
alignment: chaotic evil
ac: 18
hp: 481
hit_dice: 26d20 + 208
speed: 30 ft., swim 120 ft.
stats:
- 30
- 11
- 26
- 22
- 18
- 20
saves:
- str: 17
- dex: 7
- con: 15
- wis: 11
skillsaves:
- history: 13
- perception: 11
damage_immunities: cold, lightning
condition_immunities: frightened, grappled, paralyzed, restrained
senses: Truesight 120 ft., passive Perception 21
languages: understands Abyssal, Celestial, Infernal, and Primordial but can't speak; telepathy 120 ft.
cr: '23'
traits:
- name: Amphibious
  desc: The kraken can breathe air and water.
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the kraken fails a saving throw, it can choose to succeed instead.
- name: Siege Monster
  desc: The kraken deals double damage to objects and structures.
actions:
- name: Multiattack
  desc: The kraken makes two Tentacle attacks and uses Fling, Lightning Strike, or Swallow.
- name: Tentacle
  desc: 'm +17, reach 30 ft. Hit: 24 (4d6 + 10) Bludgeoning damage. The target has the Grappled condition (escape DC 20) from one of ten tentacles, and it has the Restrained condition until the grapple ends.'
- name: Fling
  desc: The kraken throws a Large or smaller creature Grappled by it to a space it can see within 60 feet of itself that isn't in the air. dex DC 25, the creature thrown and each creature in the destination space.  18 (4d8) Bludgeoning damage, and the target has the Prone condition.  Half damage only.
- name: Lightning Strike
  desc: dex DC 23, one creature the kraken can see within 120 feet.  33 (6d10) Lightning damage.  Half damage.
- name: Swallow
  desc: |-
    dex DC 25, one creature Grappled by the kraken (it can have up to four creatures swallowed at a time).  23 (3d8 + 10) Piercing damage. If the target is Large or smaller, it is swallowed and no longer Grappled. A swallowed creature has the Restrained condition, has Total Cover against attacks and other effects outside the kraken, and takes 24 (7d6) Acid damage at the start of each of its turns.
    If the kraken takes 50 damage or more on a single turn from a creature inside it, the kraken must succeed on a DC 25 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the kraken with the Prone condition. If the kraken dies, any swallowed creature no longer has the Restrained condition and can escape from the corpse using 15 feet of movement, exiting Prone.
legendary_actions:
- name: Storm Bolt
  desc: The kraken uses Lightning Strike.
- name: Toxic Ink
  desc: con DC 23, each creature in a 15-foot Emanation originating from the kraken while it is underwater.  The target has the Blinded and Poisoned conditions until the end of the kraken's next turn. The kraken then moves up to its Speed.  The kraken can't take this action again until the start of its next turn.
legendary_description: The kraken can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The kraken regains spent legendary actions at the start of its turn.
---
