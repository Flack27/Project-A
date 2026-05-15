---
role: support
scaling:
  - HP
  - ATK
damage type:
  - sustained
  - AoE
playstyle:
  - attrition
  - team-dependent
  - setup
weapons:
  - staff
  - tome
  - orb
stats: -ATK +SPD +HP -DEF
buffs: [shield, heal over time]
debuffs:
  - entangle
  - CRIT Rate-
recovery:
effects:
  - steal
---
Shield-focused support built around generating, cycling and weaponising ally shields. HP investment drives shield value throughout. Two distinct major passive directions — the turn-based shield pulse is self-contained and consistent, the stack-based passive rewards sustained fights where enemies are actively breaking through shields and scales harder the longer the fight goes. Steal and distribute creates a unique mid-fight power swing unavailable to any other class, converting enemy buff states into team fuel. Purely supportive combat contribution measured entirely in team survivability and buff manipulation.

---

## Major Pool

Class-defining skills and passives. Two are drawn across slots 3 and 4, with at least one always being an active.

**Spirit Drain** — Single target active. Deal damage to the target equal to a percentage of Terramancer's max HP, ignoring DEF. Apply a shield to all allies for the same amount.

**Soul Circle** — Single target active. apply [endure] to self then [Steal] all buffs from the target. Distribute all buffs currently on Terramancer evenly across all allies, applying each buff with its remaining duration.

**Earthen Grasp** — AoE active. Deal damage to all enemies. Apply [Entangle] and [CRIT Rate-] to all enemies hit.

**Leafguard** — Passive. At the start of Terramancer's turn, apply a HP-scaling [shield] to all allies and remove 1 debuff.

**Symbiosis** — Passive. Gain a stack each time an ally takes an action or an enemy breaks through a shield applied by Terramancer. At a fixed stack threshold, pulse a HP-scaling shield onto all allies and gain one permanent max HP stack. Max HP stacks cap at a fixed number — placeholder, requires balance testing. Shield pulsing continues indefinitely after the max HP cap is reached, stacks simply stop increasing.

---

## Minor Pool

Smaller refinements drawn at slots 5 and 6. Always passives.

**Forestward** — Reduce all AoE damage taken by shielded allies by a fixed percentage.

**Verdant Bloom** — Shields applied by Terramancer also apply a 1 turn [Heal Over Time] to the recipient for the shield's duration.

**Thornwall** — When an enemy attacks a shield on any ally, reflect a fixed percentage of the damage absorbed back to the attacker as true damage.

**Overgrowth** — Increase all shield values applied by Terramancer by a fixed percentage.

