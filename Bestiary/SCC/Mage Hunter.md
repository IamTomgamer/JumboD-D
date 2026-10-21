---
statblock: true
layout: Basic 5e Layout
name: Mage Hunter
source: SCC
size: Large
type: monstrosity
alignment: typically lawful evil
ac: 15 (natural armor)
hp: 85
hit_dice: 10d10 + 30
speed: 40 ft., climb 40 ft. (hunter form only), fly 10 ft. (hover) (hover sentry form only)
stats:
- 19
- 15
- 16
- 11
- 17
- 10
saves:
- int: 3
- wis: 6
- cha: 3
skillsaves:
- perception: 9
- stealth: 5
condition_immunities: blinded, charmed, deafened, frightened, prone
senses: blindsight 120 ft. (blind beyond this radius), passive Perception 19
languages: understands Common but can't speak
cr: '5'
traits:
- name: Magic Sense
  desc: The hunter knows the location of every spellcaster, active spell, and magic item within 120 feet of itself.
- name: Spider Climb (Hunter Form Only)
  desc: The hunter can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.
actions:
- name: Multiattack (Hunter Form Only)
  desc: The hunter makes two Claw attacks.
- name: Claw (Hunter Form Only)
  desc: 'Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 15 (2d10 + 4) slashing damage.'
- name: Tail
  desc: 'Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 22 (4d8 + 4) piercing damage, and the target is grappled (escape DC 15). Until this grapple ends, the target is restrained, and the hunter can''t make a Tail attack against another target.'
- name: Mage Tracker (Sentry Form Only)
  desc: |-
    The hunter emits a pulse of energy that helps it better locate its magical quarry. Each creature within 120 feet of the hunter that has the ability to cast spells must succeed on a DC 14 Wisdom saving throw or be mystically marked by the hunter for 1 hour.
    While marked, a creature can't become hidden from the hunter and gains no benefit from the invisible condition against the hunter. Additionally, while a marked creature is on the same plane of existence as the hunter, the hunter always knows the distance and direction to the creature.
bonus_actions:
- name: Shift Form
  desc: The hunter folds into its drone-like sentry form or unfolds into its hunter form. Its game statistics are the same in each form.
reactions:
- name: Consume and Destroy
  desc: When the hunter takes damage from a spell, it takes only half the triggering damage (rounded down). If the creature that cast the spell is within 60 feet of the hunter, that creature must succeed on a DC 14 Dexterity saving throw or take the other half of the damage.
---
