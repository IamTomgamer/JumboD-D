---
statblock: true
layout: Basic 5e Layout
name: Death Tyrant
source: XMM
size: Large
type: undead
subtype: beholder
alignment: lawful evil
ac: 19
hp: 195
hit_dice: 26d10 + 52
speed: 5 ft., fly 40 ft. (hover) (hover)
stats:
- 18
- 14
- 14
- 19
- 15
- 19
saves:
- con: 7
- wis: 7
skillsaves:
- perception: 12
damage_immunities: poison
condition_immunities: charmed, exhaustion, paralyzed, petrified, poisoned, prone
senses: Darkvision 120 ft., passive Perception 22
languages: Deep Speech, Undercommon
cr: '14'
traits:
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the death tyrant fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The death tyrant uses Eye Rays three times.
- name: Bite
  desc: 'm +9, reach 5 feet. Hit: 13 (2d8 + 4) Piercing damage.'
- name: Eye Rays
  desc: |-
    The death tyrant randomly shoots one of the following magical rays at a target it can see within 120 feet of itself (roll 1d10; reroll if the death tyrant has already used that ray during this turn):
    - **1: Charm Ray** wis DC 17.  13 (3d8) Psychic damage, and the target has the Charmed condition for 1 hour or until it takes damage.  Half damage only.
    - **2: Paralyzing Ray** con DC 17.  The target has the Paralyzed condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
    - **3: Fear Ray** wis DC 17.  10 (3d6) Psychic damage, and the target has the Frightened condition until the end of its next turn.  Half damage only.
    - **4: Slowing Ray** con DC 17.  18 (4d8) Necrotic damage. Until the end of the target's next turn, the target can't take Reactions; its Speed is halved; and it can take either an action or a Bonus Action on its turn, not both.  Half damage only.
    - **5: Enervation Ray** con DC 17.  16 (3d10) Poison damage, and the target has the Poisoned condition until the end of its next turn. While Poisoned, the target can't regain Hit Points.  Half damage only.
    - **6: Telekinetic Ray** str DC 17 (the target succeeds automatically if it is Gargantuan).  The death tyrant moves the target up to 30 feet in any direction. The target has the Restrained condition until the start of the death tyrant's next turn or until the death tyrant has the Incapacitated condition. The death tyrant can also exert fine control on objects with this ray, such as manipulating a tool or opening a door or container.
    - **7: Sleep Ray** wis DC 17 (the target succeeds automatically if it is a Construct or an Undead).  The target has the Unconscious condition for 1 minute. The condition ends if the target takes damage or a creature within 5 feet of it takes an action to wake it.
    - **8: Petrification Ray** con DC 17. 1 The target has the Restrained condition and repeats the save at the end of its next turn if it is still Restrained, ending the effect on itself on a success. 2 The target has the Petrified condition instead of the Restrained condition.
    - **9: Disintegration Ray** dex DC 17.  36 (8d8) Force damage. If the target is a nonmagical object or a creation of magical force, a 10-foot Cube of it disintegrates into dust.  Half damage.  If the target is a creature and this damage reduces it to 0 Hit Points, it disintegrates into dust.
    - **10: Death Ray** dex DC 17.  55 (10d10) Necrotic damage.  Half damage.  The target dies if the ray reduces it to 0 Hit Points.
bonus_actions:
- name: Negative Energy Cone
  desc: The death tyrant's central eye emits an imperceptible, magical wave of negative energy in a 150-foot Cone. Creatures in that area can't regain Hit Points until the start of the death tyrant's next turn. An intact Humanoid corpse there instantly rises as a Zombie under the death tyrant's control and takes its turn immediately after the death tyrant on the same initiative count.
legendary_actions:
- name: Chomp
  desc: The death tyrant makes two Bite attacks.
- name: Glare
  desc: The death tyrant uses Eye Rays.
legendary_description: The death tyrant can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The death tyrant regains spent legendary actions at the start of its turn.
---
