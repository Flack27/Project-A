---
role: damage
scaling:
  - DEF
damage type:
  - sustained
  - single target
  - AoE
playstyle:
  - aggressive
  - attrition
weapons:
  - staff (Solar Staff)
stats: =ATK -SPD ++DEF -HP
buffs:
  - DEF+
  - SPD+
  - shield
debuffs: []
recovery: []
effects:
  - steal
  - turn meter+
  - turn order swap
---
DEF-scaling damage dealer built around basic attack cycling and follow-up attacks. Damage output, survivability and follow-up rate all draw from the same stat investment, creating a unified gearing identity. Equipping a staff transforms it into a Solar Staff with a Lightweaver-exclusive technique tree — different visuals, different abilities, DEF scaling throughout. Two distinct major passive directions produce meaningfully different builds: the stack passive is team-dependent and rewards ally skill usage, the DEF passive is fully self-contained. Both are viable. Neither is required for the kit to function.

---

## Solar Staff

Lightweaver exclusive. Any staff equipped by a Lightweaver becomes a Solar Staff with a unique technique tree. Cannot equip other magic weapon types. Techniques scale with DEF throughout.

**S1 — Basic Attack**
DEF scaling strike. Develops through three mastery levels increasing damage at each. No specialisation.

**S2**
AoE strike hitting all enemies. DEF scaling. Mastery increases damage at levels 2 and 3.

_Specialisation_ — AoE strike with a chance to apply [Unhealable] to all enemies hit, or AoE strike where the main target receives a follow-up basic attack after the skill resolves.

---

## Major Pool

Class-defining skills and passives. Two are drawn across slots 3 and 4, with at least one always being an active.

**Solar Flare** — AoE active. Strike all enemies with a basic attack. Chance to [Steal] one buff from each enemy hit.

**Blink** — Single target active. Blink to the ally with the lowest turn meter. Strike a selected enemy with a basic attack. Blink back. Swap turn order positions between that ally and the highest turn order enemy. Apply a small [Bar Push] to the targeted ally and to self.

**Luminous Guard** — AoE active. Apply [DEF+], [SPD+] and a DEF-scaling [Shield] to all allies.

**Radiance** — Passive. Each time an ally uses a skill, gain one Radiance stack up to a cap. Each stack increases DEF by a fixed amount. Each time an ally lands a critical hit, chance to consume one stack and immediately follow up with a basic attack against the enemy that was hit.

**Solar Aegis** — Passive. Gain damage reduction and follow-up attack chance both equal to a fixed percentage of total DEF. Follow-up attacks trigger on basic attacks only, once per turn.

---

## Minor Pool

Smaller refinements drawn at slots 5 and 6. Always passives.

**Bulwark** — Increase DEF by a fixed amount.

**Afterimage** — When Lightweaver triggers a follow-up attack, that follow-up has a chance to trigger one additional follow-up. Cannot chain beyond a single additional proc per turn.

**Radiant Tempo** — Basic attacks apply a small [Bar Push] to all allies.

**Illuminate** — Basic attacks deal bonus damage against enemies with no active buffs. Pairs naturally with Solar Flare — stripping buffs then punishing the stripped targets on subsequent turns.

---

## Notes

Solar Staff S2 specialisation branches produce meaningfully different builds. The Unhealable branch leans attrition and pairs with Solar Aegis for sustained pressure. The follow-up branch leans burst and pairs with Radiance or Afterimage for follow-up chaining.

Blink's turn order swap is not a bar push or bar pull effect and does not interact with Pinned. It replaces two characters' exact queue positions simultaneously. The ally and enemy affected are determined at the moment of casting based on current turn order state — both the ally selection and the enemy selection are fixed by the mechanic, not chosen by the player.

Radiance and Solar Aegis pull in different directions. Radiance is team-dependent and rewards building around crit-heavy allies. Solar Aegis is self-contained and rewards pure DEF investment. A character who draws both will benefit from DEF stacking across both passives but the follow-up triggers from each are independent and both can proc in the same turn.
