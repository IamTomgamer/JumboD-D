---
statblock: true
layout: Basic 5e Layout
name: Lesser Tyrant Shadow
source: CoA
size: Medium
type: aberration
alignment: lawful evil
ac: 20 (natural armor)
hp: 114
hit_dice: 12d8 + 60
speed: 30 ft.
stats:
- 20
- 18
- 20
- 18
- 16
- 18
saves:
- int: 8
- wis: 7
skillsaves:
- arcana: 8
- deception: 12
- perception: 7
- stealth: 12
damage_resistances: fire
damage_immunities: necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
condition_immunities: blinded, charmed, frightened, poisoned
senses: passive Perception 17
languages: understands all, telepathy 300 ft.
cr: '10'
traits:
- name: Empath
  desc: The shadow uses telepathy to sense nearby creatures. The shadow can see a creature if that creature has thoughts and is within the range of the shadow's telepathy. The shadow can't see creatures immune to telepathy.
- name: Undying Connection
  desc: The shadow was originally spawned from a specific devil and, if the shadow is slain, it returns to life in 10 (1d20) days within 1 mile of that devil. The shadow is killed permanently only if its progenitor devil is slain first.
actions:
- name: Multiattack
  desc: The shadow makes two Claw attacks.
- name: Claw
  desc: 'Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12 (2d6 + 5) necrotic damage, plus 3 (1d6) psychic damage.'
- name: Cloak of Shadows
  desc: The shadow bends darkness around itself, and now has the invisible condition for 1 minute. The invisibility ends if the shadow is subjected to a Daylight spell or similar.
- name: Empathic Link
  desc: The shadow attempts to form a link between itself and a creature it can see. The target must make a DC 16 Intelligence saving throw, taking 6 (1d12) psychic damage on a success. On a failed save, the creature and the shadow are linked. While linked, every time the shadow is damaged, the creature takes half of that damage as psychic damage. The creature may repeat the saving throw at the end of each of its turns, taking 6 (1d12) psychic damage on a failed save, or ending the effect on a successful one.
bonus_actions:
- name: Change Shape
  desc: The shadow transforms into a Beast, Humanoid or Fiend that it has an Empathic Link with, or back into its true form. In a new form, the shadow retains its alignment, hit points, hit dice, telepathy, and Intelligence, Wisdom, and Charisma scores, as well as this action. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features, lair actions, or legendary actions of that form.
---
