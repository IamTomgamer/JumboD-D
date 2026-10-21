---
statblock: true
layout: Basic 5e Layout
name: Death Knight
source: XMM
size: Small or Medium
type: undead
alignment: chaotic evil
ac: 20
hp: 199
hit_dice: 21d8 + 105
speed: 30 ft.
stats:
- 20
- 11
- 20
- 12
- 16
- 18
saves:
- dex: 6
- wis: 9
damage_immunities: necrotic, poison
condition_immunities: exhaustion, frightened, poisoned
senses: Darkvision 120 ft., passive Perception 13
languages: Abyssal, Common
cr: '17'
traits:
- name: Legendary Resistance (3/Day)
  desc: If the death knight fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The death knight has Advantage on saving throws against spells and other magical effects.
- name: Marshal Undead
  desc: Undead creatures of the death knight's choice (excluding itself) in a 60-foot Emanation originating from it have Advantage on attack rolls and saving throws. It can't use this trait if it has the Incapacitated condition.
- name: Undead Restoration
  desc: If the death knight is destroyed before it atones for its evil, it gains a new body in 1d10 days, reviving with all its Hit Points. The new body appears in a location significant to the death knight.
- name: Spellcasting
  desc: |-
    The death knight casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 18):
    At will: Command, Phantom Steed
    2/day each: Destructive Wave (Necrotic), Dispel Magic
actions:
- name: Multiattack
  desc: The death knight makes three Dread Blade attacks.
- name: Dread Blade
  desc: 'm +11, reach 5 ft. Hit: 12 (2d6 + 5) Slashing damage plus 13 (3d8) Necrotic damage.'
- name: Hellfire Orb (Recharge 5-6)
  desc: dex DC 18, each creature in a 20-foot-radius Sphere centered on a point the death knight can see within 120 feet.  35 (10d6) Fire damage plus 35 (10d6) Necrotic damage.  Half damage.
reactions:
- name: Parry
  desc: ' The death knight is hit by a melee attack roll while holding a weapon.  The death knight adds 6 to its AC against that attack, possibly causing it to miss.'
legendary_actions:
- name: Dread Authority
  desc: The death knight uses Spellcasting to cast Command. The death knight can't take this action again until the start of its next turn.
- name: Fell Word
  desc: con DC 18, one creature the death knight can see within 120 feet.  17 (5d6) Necrotic damage, and the target's Hit Point maximum decreases by an amount equal to the damage taken.  The death knight can't take this action again until the start of its next turn.
- name: Lunge
  desc: The death knight moves up to half its Speed, and it makes one Dread Blade attack.
legendary_description: The death knight can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The death knight regains spent legendary actions at the start of its turn.
---
