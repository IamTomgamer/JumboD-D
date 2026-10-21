---
statblock: true
layout: Basic 5e Layout
name: Zagum
source: CoA
size: Medium
type: fiend
subtype: devil
alignment: lawful evil
ac: 19 (natural armor)
hp: 255
hit_dice: 30d8 + 120
speed: 30 ft.
stats:
- 17
- 16
- 18
- 22
- 25
- 27
saves:
- int: 12
- wis: 13
- cha: 14
skillsaves:
- arcana: 12
- deception: 20
- insight: 13
- intimidation: 14
- performance: 14
- persuasion: 20
damage_resistances: cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
damage_immunities: fire, poison, psychic
condition_immunities: charmed, poisoned
senses: darkvision 120 ft., passive Perception 17
languages: Celestial, Common, Draconic, Infernal, telepathy 120 ft.
cr: '20'
traits:
- name: Contractually Obligated
  desc: Zagum has advantage to hit creatures under an infernal contract and when he hits such creatures he delivers an additional 9 (2d8) damage of a type the target is most vulnerable to. A creature bound under an infernal contract also makes all saving throws against effects originating from Zagum with disadvantage.
- name: Devil's Sight
  desc: Magical darkness doesn't impede Zagum's darkvision.
- name: Magic Resistance
  desc: Zagum has advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: Zagum makes three attacks with Disarming Tongue or Oration.
- name: Disarming Tongue
  desc: 'Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 10 (3d4 + 3) slashing damage. A target hit by this attack has vulnerability to psychic damage until the start of their next turn.'
- name: Oration
  desc: 'Ranged Spell Attack: +14 to hit, range 60 ft., one target. Hit: 35 (6d8 + 8) psychic damage.'
- name: Legal Jargon (Recharge 4-6)
  desc: |-
    Zagum chooses a point he can see within 90 feet of him. All creatures within a 20-foot-radius sphere centered on that point must make a DC 22 Wisdom saving throw. Creatures that fail the save are confused for up to 1 minute and must roll a d10 at the start of each of their turns.
    On a 1, a creature moves in a random direction then ends their turn. On a 2-6, a creature can't use actions this turn. On a 7-8, a creature must use their action to make a melee attack against a randomly determined creature within their reach that is not a Fiend. On a 9-10, a creature can move and act normally.
    A confused creature may repeat the saving throw at the end of its turn, ending the effect on a success.
---
