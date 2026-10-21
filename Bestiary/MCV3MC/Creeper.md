---
statblock: true
layout: Basic 5e Layout
name: Creeper
source: MCV3MC
size: Medium
type: monstrosity
alignment: typically neutral evil
ac: 12 (natural armor)
hp: 19
hit_dice: 3d8 + 6
speed: 30 ft.
stats:
- 10
- 11
- 14
- 6
- 8
- 3
skillsaves:
- perception: 3
- stealth: 4
damage_immunities: lightning
condition_immunities: exhaustion
senses: darkvision 60 ft., passive Perception 13
languages: —
cr: 1/2
traits:
- name: Bizarre Physiology
  desc: The creeper can't take actions except for Dash, Disengage, Hide, and Search. It can't take bonus actions or reactions.
- name: Creeper Head
  desc: When a creeper drops to 0 hit points from a charged creeper's explosion (see the Destruction trait), it dies and its head falls off. A creeper's fallen head is hollow and can be worn as a mask with eye and mouth openings.
- name: Destruction
  desc: |-
    When it ends its turn within 10 feet of a Humanoid that it can see, the creeper stops moving and emits a hiss loud enough to be heard by creatures within 30 feet of itself.
    If the creeper drops to 0 hit points before the start of its next turn, the hissing stops, and the creeper dies. Otherwise, at the start of the creeper's next turn, one of following things happens:
    - If there are no Humanoids within 10 feet of the hissing creeper, it stops hissing. It then uses any available movement to approach the nearest Humanoid it can see.
    - If there are one or more Humanoids within 10 feet of the hissing creeper, the creeper explodes in a ball of energy that fills a 20-foot-radius sphere centered on itself. This energy spreads around corners. The creeper is destroyed, and every other creature in the explosion's area must make a DC 12 Dexterity saving throw, taking 14 (4d6) lightning damage on a failed save, or half as much damage on a successful one. Increase this damage by 7 (2d6) if the creeper is charged (see "Electrical Charge" below). Objects in the area that aren't being worn or carried take 14 (4d6) lightning damage, or 21 (6d6) lightning damage if the creeper is charged.
- name: Electrical Charge
  desc: Whenever the creeper is subjected to lightning damage, it takes no damage and instead becomes charged for 1 minute. While charged, the creeper emits dim blue light in a 5-foot radius.
- name: Fear of Felines
  desc: The creeper has the frightened condition whenever it starts its turn within 60 feet of a feline creature it can see. The condition lasts until the start of the creeper's next turn.
---
