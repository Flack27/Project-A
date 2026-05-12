---
scaling:
  - ATK
  - DEF
buffs: []
debuffs: [DEF-, bleed, RES-, ATK-, taunt]
recovery: []
effects:
---
## S1

- X% damage, 1 hit
	- X% damage, 2 hits
		- X% damage, 2 hits, X% chance to apply [Bleed] *(Duelist, Warrior, Revenant)*
		- X% damage, 3 hits, X% chance to apply [DEF-] *(Warden, Guardian, Warrior, Revenant, Paladin)*
	- X% damage, 1 hit *(Paladin, Duelist, Warrior, Revenant)*
		- X% damage, 1 hit

[ATK / DEF toggle unlocks on completing any endpoint]

---

## S2

- X% damage, 1 hit
	- X% damage to all enemies, 1 hit
	    - DEF _(Guardian, Warden, Revenant)_
	        - X% damage to all enemies, 2 hits, X% chance to apply [ATK-] _(Guardian, Warden, Revenant)_
	        - X% damage to all enemies, 2 hits, X% chance to apply [RES-] _(Guardian, Warden, Revenant, Paladin)_
	    - ATK _(Warrior, Duelist, Infernus)_
	        - X% damage to all enemies, 2 hits, X% chance to apply [Bleed] _(Warrior, Duelist)_
	        - X% damage to all enemies, 1 hit _(Warrior, Duelist, Infernus)_
	- X% damage, 1 hit
	    - DEF _(Guardian, Warden, Revenant, Paladin)_
	        - X% damage, 2 hits, X% chance to apply [Taunt] _(Guardian, Warden, Revenant)_
	        - X% damage, 3 hits _(Warden, Revenant)_
	    - ATK _(Warrior, Duelist, Infernus)_
	        - X% damage, 3 hits, X% chance to apply [Bleed] _(Warrior, Duelist)_
	        - X% damage, 2 hits, damage scales with target missing HP _(Duelist, Infernus)_