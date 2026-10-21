---
statblock: true
layout: Basic 5e Layout
name: Construct Spirit
source: XPHB
size: Medium
type: construct
alignment: neutral
ac: 13 + the spell's level
hp: 40 + 15 for each spell level above 4
speed: 30 ft.
stats:
- 18
- 10
- 18
- 14
- 11
- 5
damage_resistances: poison
condition_immunities: charmed, exhaustion, frightened, paralyzed, poisoned
senses: Darkvision 60 ft., passive Perception 10
languages: Understands the languages you know
cr: ''
traits:
- name: Heated Body (Metal Only)
  desc: A creature that hits the spirit with a melee attack or that starts its turn in a grapple with the spirit takes 1d10 Fire damage.
- name: Stony Lethargy (Stone Only)
  desc: When a creature starts its turn within 10 feet of the spirit, the spirit can target it with magical energy if the spirit can see it. wis DC equals your spell save DC, the target.  Until the start of its next turn, the target can't make Opportunity Attacks, and its Speed is halved.
actions:
- name: Multiattack
  desc: The spirit makes a number of Slam attacks equal to half this spell's level (round down).
- name: Slam
  desc: 'm Bonus equals your spell attack modifier, reach 5 ft. Hit: 1d8 + 4 + summonSpellLevel Bludgeoning damage.'
reactions:
- name: Berserk Lashing (Clay Only)
  desc: ' The spirit takes damage from a creature.  The spirit makes a Slam attack against that creature if possible, or the spirit moves up to half its Speed toward that creature without provoking Opportunity Attacks.'
---
