---
statblock: true
layout: Basic 5e Layout
name: Avarice
source: IDRotF
size: Medium
type: humanoid
subtype: tiefling
alignment: lawful evil
ac: 13
hp: 84
hit_dice: 13d8 + 26
speed: 30 ft.
stats:
- 8
- 16
- 14
- 17
- 10
- 9
saves:
- int: 6
- wis: 3
skillsaves:
- arcana: 6
- history: 6
damage_resistances: cold, fire
senses: darkvision 60 ft., passive Perception 10
languages: Common, Draconic, Infernal, Orc, Yeti
cr: '7'
traits:
- name: Icy Doom
  desc: When Avarice dies, her corpse freezes for 9 days, during which time it can't be thawed, harmed by fire, animated, or raised from the dead.
- name: Special Equipment
  desc: Avarice wields a staff of frost with 10 charges (see "Actions" below).
- name: Spellcasting
  desc: |-
    Avarice is a 10th-level spellcaster. Her spellcasting ability is Intelligence (spell save DC 14; +6 to hit with spell attacks). She has the following wizard spells prepared:
    Cantrips (at will): fire bolt (see "Actions" below), mage hand, message, minor illusion, prestidigitation
    1st level (4 slots): detect magic, mage armor, magic missile
    2nd level (3 slots): flaming sphere, knock, scorching ray
    3rd level (3 slots): counterspell, fireball, fly
    4th level (3 slots): banishment, fire shield
    5th level (2 slots): Bigby's hand, Rary's telepathic bond
actions:
- name: Fire Bolt (Cantrip)
  desc: 'Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit: 11 (2d10) fire damage.'
- name: Staff of Frost
  desc: 'While holding this staff, Avarice can expend 1 or more of its charges to cast one of the following spells from it (spell save DC 14): cone of cold (5 charges), fog cloud (1 charge), ice storm (4 charges), or wall of ice (4 charges). The staff regains 1d6 + 4 charges daily at dawn. If its last charge is expended, roll a d20; on a 1, the staff turns to water and is destroyed.'
reactions:
- name: Banishing Rebuke (Recharges after a Long Rest)
  desc: When Avarice is damaged by a creature that she can see within 60 feet of her, she can banish that creature to a frigid extradimensional prison for 1 minute. While there, the creature is incapacitated and takes 5 (1d10) cold damage at the start of each of its turns. At the end of each of its turns, the creature can make a DC 14 Charisma saving throw, escaping the prison on a success and reappearing in the space it left or in the nearest unoccupied space if that space is occupied. A creature that dies in the prison is trapped there indefinitely.
---
