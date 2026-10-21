---
statblock: true
layout: Basic 5e Layout
name: Arch-hag
source: XMM
size: Large
type: fey
alignment: neutral evil
ac: 20
hp: 333
hit_dice: 29d10 + 174
speed: 40 ft.
stats:
- 24
- 15
- 23
- 19
- 19
- 25
saves:
- dex: 9
- wis: 11
skillsaves:
- deception: 14
- perception: 11
- persuasion: 21
damage_resistances: cold, fire, psychic
condition_immunities: charmed, exhaustion, frightened
senses: Truesight 60 ft., passive Perception 21
languages: all
cr: '21'
traits:
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the hag fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The hag has Advantage on saving throws against spells and other magical effects.
- name: Spiteful Escape
  desc: When the hag drops to 0 Hit Points, it dies only if it is within 30 feet of its anathema (a thing the DM chooses as the hag's most hated thing). Otherwise, the hag drops to 1 Hit Point and teleports to a harmless demiplane, and it can't return to the plane it left for 2d6 days. When the hag teleports away, each creature within 60 feet of the space it left is cursed. Until the curse ends, a creature has Disadvantage on ability checks and saving throws, and the hag knows its location anywhere in the multiverse.
- name: Coven Magic
  desc: 'While within 30 feet of at least two hag allies, the hag can cast one of the following spells, requiring no Material components, using the spell''s normal casting time, and using Intelligence as the spellcasting ability (spell save DC 19): Augury, Find Familiar, Identify, Locate Object, Scrying, or Unseen Servant. The hag must finish a Long Rest before using this trait to cast that spell again.'
- name: Spellcasting
  desc: |-
    The hag casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 22):
    At will: Detect Thoughts, Dimension Door, Dispel Magic, Hypnotic Pattern
    2/day each: Mass Suggestion, Modify Memory, Plane Shift
- name: Tongue Twister
  desc: |-
    The hag casts Counterspell in response to that spell's trigger, using the same spellcasting ability as Spellcasting. If the target fails its saving throw, it is cursed until the end of its next turn. Until the curse ends, the target can't cast spells with a Verbal component, and when it speaks, it says the opposite of what it means.
    At will: Counterspell
actions:
- name: Multiattack
  desc: The hag makes two Spectral Claw attacks and uses Crackling Wave.
- name: Spectral Claw
  desc: 'm,r +14, reach 10 ft. or range 60 ft. Hit: 17 (3d6 + 7) Force damage. If the target is a Large or smaller creature, it has the Prone condition.'
- name: Crackling Wave
  desc: dex DC 22, each creature in a 60-foot Cone.  32 (5d12) Lightning damage.  Half damage.  The target is cursed until the end of the hag's next turn. The target can't take Reactions until the curse ends.
bonus_actions:
- name: Witch Strike
  desc: Each creature cursed by the hag and within 60 feet of it takes 14 (4d6) Lightning damage.
legendary_actions:
- name: Hag's Swipe
  desc: The hag makes one Spectral Claw attack.
- name: Malicious Magic
  desc: The hag uses Spellcasting to cast Dimension Door or Hypnotic Pattern. The hag can't take this action again until the start of its next turn.
legendary_description: The arch-hag can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The arch-hag regains spent legendary actions at the start of its turn.
---
