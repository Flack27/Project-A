---
scaling:
  - DEF
  - HP
buffs:
  - shield
  - immunity
debuffs:
  - taunt
  - stun
recovery: []
effects:
  - strip
---

## S1

- X% damage, 1 hit
	- X% damage, 2 hits — apply [Taunt] 
		- DEF _(Guardian, Warden, Revenant)_
		- HP _(Bruiser, Bulwark)_
	- X% damage, 2 hits — apply [Stun] 
		- DEF _(Guardian, Warden, Revenant)_
		- HP _(Bruiser, Bulwark)_

---

## S2

- X% damage, 1 hit
	- No damage — apply [Taunt] to all enemies _(Guardian, Bruiser, Bulwark, Warden)_
		- No damage — apply [Taunt] to all enemies, apply [Immunity] to all allies _(Guardian, Bulwark)_
			- DEF _(Guardian, Warden)_
			- HP _(Bruiser, Bulwark)_
		- No damage — apply [Taunt] to all enemies, apply [Shield] to all allies _(Guardian, Bruiser, Bulwark, Warden)_
			- DEF _(Guardian, Warden)_
			- HP _(Bruiser, Bulwark)_
	- X% damage, 2 hits
		- X% damage, 2 hits — [Strip] then apply [Stun] 
			- DEF _(Guardian, Warden, Revenant)_
			- HP _(Bruiser, Bulwark)_
		- X% damage, 2 hits — [Strip] then apply [Taunt] 
			- DEF _(Guardian, Warden, Revenant)_
			- HP _(Bruiser, Bulwark)_

---

