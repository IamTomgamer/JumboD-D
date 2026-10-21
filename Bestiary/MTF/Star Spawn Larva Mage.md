---
statblock: true
layout: Basic 5e Layout
name: Star Spawn Larva Mage
source: MTF
size: Medium
type: aberration
alignment: chaotic evil
ac: 16 (natural armor)
hp: 168
hit_dice: 16d8 + 96
speed: 30 ft.
stats:
- 17
- 12
- 23
- 18
- 12
- 16
saves:
- dex: 6
- wis: 6
- cha: 8
skillsaves:
- perception: 6
damage_resistances: cold; bludgeoning, piercing, slashing from nonmagical attacks
damage_immunities: psychic
condition_immunities: charmed, frightened, paralyzed, petrified, poisoned, restrained
senses: darkvision 60 ft., passive Perception 16
languages: Deep Speech
cr: '16'
traits:
- name: Return to Worms
  desc: When the larva mage is reduced to 0 hit points, it breaks apart into a swarm of insects in the same space. Unless the swarm is destroyed, the larva mage reforms from it 24 hours later.
- name: Innate Spellcasting
  desc: |-
    The larva mage's innate spellcasting ability is Charisma (spell save DC 16, +8 to hit with spell attacks). It can innately cast the following spells, requiring no material components:
    At will: eldritch blast*, minor illusion
    1/day: circle of death
    3/day: dominate monster
    *3 beams, +3 bonus to each damage roll
actions:
- name: Slam
  desc: 'Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 7 (1d8 + 3) bludgeoning damage, and the target must succeed on a DC 19 Constitution saving throw or be poisoned until the end of its next turn.'
- name: Plague of Worms (Recharge 6)
  desc: Each creature other than a star spawn within 10 feet of the larva mage must make a DC 19 Dexterity saving throw. On a failure the target takes 22 (5d8) necrotic damage and is blinded and restrained by masses of swarming worms. The affected creature takes 22 (5d8) necrotic damage at the start of each of the larva mage's turns. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
reactions:
- name: Feed on Weakness
  desc: When a creature within 20 feet of the larva mage fails a saving throw, the larva mage gains 10 temporary hit points.
legendary_actions:
- name: Cantrip (Costs 2 Actions)
  desc: The larva mage casts one cantrip.
- name: Slam (Costs 2 Actions)
  desc: The larva mage makes one slam attack.
- name: Feed (Costs 3 Actions)
  desc: Each creature restrained by the larva mage's Plague of Worms takes 13 (3d8) necrotic damage, and the larva mage gains 6 temporary hit points.
legendary_description: The star spawn larva mage can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The star spawn larva mage regains spent legendary actions at the start of its turn.
---
