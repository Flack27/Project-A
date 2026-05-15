---
scaling:
  - ATK
  - HP
buffs: []
debuffs:
  - DEF-
recovery:
effects:
---

## S1

- X% damage, 1 hit
	- X% damage, 2 hits — apply [DEF-] 
		- ATK _(Berserker, Rogue, Ranger)_
		- HP _(Bruiser, Bulwark)_
	- X% damage, 2 hits — ignores X% of target DEF
		- ATK _(Berserker, Rogue, Ranger)_
		- HP _(Bruiser, Bulwark)_

---

## S2

- X% damage to all enemies, 1 hit
	- X% damage, 1 hit
		- ATK _(Berserker, Rogue, Ranger)_
			- X% damage, 1 hit — apply [HP Lock], duration scales with damage dealt 
			- X% damage, 1 hit — heal self for X% of damage dealt
		- HP _(Bruiser, Bulwark)_
			- X% damage, 2 hits — execute target below 10% HP {5% against bosses} 
			- X% damage, 2 hits — X% chance to [Steal] a buff, apply [DEF-]
	- X% damage to all enemies, 1 hit
		- ATK _(Berserker, Rogue, Ranger)_
			- X% damage to all enemies, 2 hits — apply [DEF-]
			- X% damage to all enemies, 2 hits — ignores X% of target DEF
		- HP _(Bruiser, Bulwark)_
			- X% damage to all enemies, 1 hit — deals additional true damage equal to X% of own current HP
			- X% damage to all enemies, 1 hit — heal self for X% of damage dealt

---

##### Notes

**HP Lock** sets the target's current HP as a healing ceiling for the duration — the target cannot be healed above their HP value at the moment the effect was applied. Duration scales with the total damage dealt by the applying hit. Distinct from Unhealable which prevents all healing outright — HP Lock allows healing up to the locked threshold only.

True damage on the HP AoE branch bypasses DEF entirely and is not reduced by any damage reduction effects. Magnitude scales with the wielder's current HP, making HP investment directly translate into bonus damage output.