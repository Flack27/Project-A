---
scaling:
  - ATK
  - DEF
buffs: []
debuffs:
  - RES-
  - ATK-
  - DEF-
recovery: []
effects:
---
## S1

- X% damage, 1 hit
	- X% damage, 2 hits, X% chance to apply [DEF-]
		- ATK _(Warrior, Duelist, Infernus, Paladin)_
		- DEF _(Guardian, Warden, Revenant)_
	- X% damage, 2 hits, X% chance to apply [Bleed]
		- ATK _(Warrior, Duelist, Infernus, Paladin)_
		- DEF _(Guardian, Warden, Revenant)_


---

## S2

- X% damage, 1 hit
	- X% damage to all enemies, 1 hit
	    - DEF _(Guardian, Warden, Revenant)_
	        - X% damage to all enemies, 2 hits, X% chance to apply [ATK-] 
	        - X% damage to all enemies, 2 hits, X% chance to apply [RES-] 
	    - ATK _(Warrior, Duelist, Infernus, Paladin)_
	        - X% damage to all enemies, 2 hits, X% chance to apply [Bleed] _(Warrior)_
	        - X% damage to all enemies, 1 hit
	- X% damage, 1 hit
	    - DEF _(Guardian, Warden, Revenant)_
	        - X% damage, 2 hits, X% chance to apply [Taunt] 
	        - X% damage, 1 hit _(Warden, Revenant)_
	    - ATK _(Warrior, Duelist, Infernus, Paladin)_
	        - X% damage, 3 hits, X% chance to apply [Bleed] _(Warrior)_
	        - X% damage, 2 hits, damage scales with target missing HP