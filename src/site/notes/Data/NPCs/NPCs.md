---
{"dg-publish":true,"permalink":"/data/np-cs/np-cs/","dgPassFrontmatter":true}
---

Last modified: 

```statblock
name: Kavie
columnWidth: 320
hp: 60
ac: 14
speed: 30 ft.
stats: [8,8,12,8,18,10]
cr: 6
type: Ooze
skillsaves:
- Perception: 7
- Deception: 6
- Arcana: 5
- Intimidation: 3
saves:
- Wisdom: 7
- Dexterity: 2
languages: Common, Abyssal, Infernal
senses: Darkvision 120 ft., Passive Perception 17
traits:
- name: Porcelain Doll
  desc: Your body could break and spill out your true form. After taking damage, if bloodied (<=50% HP), roll 1d4. On a 1, you are broken (+8 to Dexterity). The instant you are broken, you can use your reaction to move up to your speed without provoking opportunity attacks. Mending for 1 minute will restore your body and remove your broken status.
actions:
- name: Multiattack
  desc: Perform two of the following as one action (can repeat attacks).
- name: Tentacle Whip
  desc: Ink tendrils dripping with darkness seep from your cracks. Melee weapon attack. +7 to hit, reach 10 ft., 1d10+4 Bludgeoning damage. Increase number of targets to two when broken.
- name: Tentacle Grasp
  desc: One creature you can see within 10 ft. must succeed on a DC 15 Dexterity save or be grappled until the start of your next turn. Increase number of targets to two when broken.
- name: Open Sanctuary (Recharge 5-6)
  desc: Concentrate on opening a gateway to your sanctuary in the Second Weave. At the start of your next turn, if your concentration is not broken, summon 2 lost puppets in positions within 15 ft. of you. They share your initiative and disappear when 1 minute has passed or you consume/dismiss them as a bonus action. You cannot have more than 4 on the field at once.
- name: Shed Porcelain Shell
  desc: Concentrate on escaping your own body. At the start of your next turn, if your concentration is not broken, you are broken.
spells:
- You are a 5th level spellcaster. Your spellcasting ability is Wisdom (spell save DC 15, +7 to hit with spell attacks).
- Cantrips (at will): mending, mage hand, message
- 1st level (4 slots): arms of hadar, dissonant whispers, fog cloud
- 2nd level (3 slots): hold person, wither and bloom
- 3rd level (2 slots): blink, speak with dead
bonus_actions:
- name: Swap Souls
  desc: Swap positions with one of your lost puppets you can see within 60 ft.
- name: Consume Puppet (4/day)
  desc: Consume a lost puppet to heal yourself for its remaining health.
```{ #statblock}

```statblock
name: Lost Puppet
columnWidth: 600
hp: 10 (1d8+6)
ac: 10
speed: 15 ft.
stats: [12,8,10,6,8,6]
cr: 1/4
type: Undead
languages: Common, Abyssal
damage_immunities: Cold, Necrotic, Poison
condition_immunities: Charmed, Exhaustion, Poisoned
senses: Darkvision 60 ft., Passive Perception 8
traits:
- name: Porcelain Body
  desc: Using Mending on this creature will heal it for 1d8+4 HP.
actions:
- name: Slam
  desc: +3 to hit, reach 5 ft., 1d6+1 Bludgeoning damage.
- name: Hug
  desc: One large or smaller creature the puppet can see within 5 ft. of it must succeed on a DC 11 Strength saving throw or be restrained by the puppet. The target can repeat the saving throw at the start of each of their turns.
```
