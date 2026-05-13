---
scaling:
  - ATK
buffs: []
debuffs: []
recovery:
  - self heal
effects:
---

## Fury

Battleaxe generates Fury passively — gain 1 stack on skill use, up to 5. Stacks persist until consumed by an S2 technique or until combat ends. This is a base weapon property active regardless of which techniques are equipped. The Fury S1 branch increases generation speed or adds a second trigger source. The Bloodcharge S1 branch adds HP threshold effects independently. Both S2 branches are accessible regardless of S1 choice — base generation is always active.

---

## S1

- X% damage, 1 hit — gain 1 Fury on skill use (max 5)
	- Fury branch — X% damage, 1 hit _(Warrior, Berserker, Infernus, Paladin)_
		- X% damage, 1 hit — Fury gains +1 on skill use
		- X% damage, 1 hit — Fury gains +1 on taking damage 
	- Bloodcharge branch — X% damage, 1 hit _(Berserker, Infernus, Paladin)_
		- X% damage, 1 hit — lifesteal for X% of damage dealt while below 60% HP
		- X% damage, 1 hit — bonus damage while below 60% HP 

---

## S2

- X% damage to all enemies, 1 hit — consumes all Fury stacks, deals bonus damage per stack consumed
	- Fury branch — X% damage to all enemies, 1 hit _(Warrior, Berserker, Infernus, Paladin)_
		- X% damage to all enemies, 1 hit — consumes Fury for increased bonus damage per stack 
			- X% damage to all enemies, 1 hit — at 5 stacks, executes targets below 10% HP {5% against bosses} 
			- X% damage to all enemies, 1 hit — at 5 stacks, S2 autocasts immediately after use 
		- X% damage to all enemies, 1 hit — consumes Fury to ignore X% DEF per stack consumed 
			- X% damage to all enemies, 1 hit — at 5 stacks, executes targets below 10% HP {5% against bosses} 
			- X% damage to all enemies, 1 hit — at 5 stacks, S2 autocasts immediately after use 
	- Bloodcharge branch — X% damage to all enemies, 1 hit _(Berserker, Infernus, Paladin)_
		- X% damage to all enemies, 1 hit — lifesteal for X% of damage dealt while below 60% HP
			- X% damage to all enemies, 1 hit — executes targets below 10% HP while below 60% HP {5% against bosses}
			- X% damage to all enemies, 1 hit — ignores X% DEF while below 60% HP 
		- X% damage to all enemies, 1 hit — bonus damage while below 60% HP
			- X% damage to all enemies, 1 hit — executes targets below 10% HP while below 60% HP {5% against bosses} 
			- X% damage to all enemies, 1 hit — ignores X% DEF while below 60% HP 

---

##### Notes

The S2 autocast fires once per use — the second cast does not trigger a third. Fury stacks are consumed on the first cast only.