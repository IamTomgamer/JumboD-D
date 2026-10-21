---
statblock: true
layout: Basic 5e Layout
name: Xzar the Chaos Clone
source: MaBJoV
size: Medium
type: humanoid
subtype: human
alignment: chaotic evil
ac: 15, 18 with mage armor
hp: 121
hit_dice: 22d8 + 22
speed: 30 ft.
stats:
- 12
- 16
- 12
- 20
- 10
- 12
saves:
- int: 9
- wis: 4
skillsaves:
- arcana: 13
- history: 13
damage_resistances: acid, cold, fire, lightning, thunder
senses: darkvision 60 ft., passive Perception 10
languages: Abyssal, Common, Infernal, Primordial, Undercommon, telepathy 60 ft.
cr: '11'
traits:
- name: Chaos Phage
  desc: |-
    Xzar's infusion with the Chaos Phage gives him the following benefits:
    - Xzar regains 10 hit points at the start of his turn if he has at least 1 hit point
    - Xzar has advantage on saving throws against spells and other magical effects
    - Xzar has resistance to acid, cold, fire, lightning, thunder
    - Xzar has darkvision and telepathy to 60 feet
- name: Grim Harvest (1/Turn)
  desc: When Xzar kills a creature that is neither a Construct nor Undead with a spell of 1st level or higher, Xzar regains hit points equal to twice the spell's level, or three times if it is a necromancy spell.
- name: No Soul
  desc: Since Xzar doesn't have a soul, resurrection magic is able to work upon him no matter how much time has passed. For example, the revivify spell would work on Xzar even a week after he died. However, spells like true resurrection and wish are unable to bring Xzar back to life if no body exists.
- name: Spellcasting
  desc: |-
    Xzar casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 17, +9 to hit with spell attacks):
    At will: acid splash, fire bolt, mage hand
    2/day each: animate dead*, blight*, false life*, mage armor, ray of enfeeblement*, ray of sickness*, scrying, vampiric touch*
    1/day each: abi-dalzim's horrid wilting*, finger of death*
    *Necromancy spell of 1st level or higher
actions:
- name: Multiattack
  desc: Xzar makes two Deprive attacks and uses Spellcasting.
- name: Deprive
  desc: 'Melee or Ranged Spell Attack: +9 to hit, reach 5 ft., or range 120 ft., one target. Hit: 27 (4d10 + 5) necrotic damage.'
- name: Death Eruption (1/Day)
  desc: Negative energy erupts from Xzar, intensified by the Chaos Phage. Any creature in a 60-foot-radius sphere around Xzar (but not including Xzar) must make a DC 17 Constitution saving throw. A creature takes 36 (8d6) necrotic damage on a failed save, or half as much damage on a successful one. A Humanoid killed by this ability rises at the start of Xzar's next turn as a zombie under his command.
---
