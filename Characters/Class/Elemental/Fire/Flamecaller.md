---
role: support
scaling:
  - ATK
damage type:
  - AoE
  - single target
playstyle:
  - team-dependent
  - attrition
  - setup
weapons:
  - staff
  - tome
  - orb
stats: =ATK ++SPD -DEF -HP
buffs:
  - ATK+
  - immunity
  - shield
debuffs:
  - burn
  - turn meter-
recovery:
  - heal
  - cleanse
effects:
---
ATK-scaling fire support built around burn as both an offensive tool and a healing amplifier. Healing and shielding scale with ATK rather than HP, making damage investment serve double duty. The passive aura applies burn to all enemies each turn and heals allies simultaneously, with healing output increasing as enemy burn stacks accumulate — rewarding sustained burn pressure from the whole team. Untargetable while not the last standing character, disabled by CC alongside both the aura and healing. Unique burn spread mechanic creates strong synergy with Pyromancer and Infernus, redistributing a single target's burn stacks across the entire enemy team.

---

## Major Pool

Class-defining skills and passives. Two are drawn across slots 3 and 4, with at least one always being an active.

**Equilibrium** — AoE active. Apply [ATK+] and [Immunity] to all allies. Redistribute all ally HP so each ally has an equal HP percentage. Calculated by summing all current HP values, dividing by the number of living allies, and applying the result proportionally to each ally's max HP. 

**Emberstorm** — Passive. The Flamecaller is untargetable. At the start of Flamecaller's turn, apply 1 [Burn] stack to all enemies and heal all allies for a small amount scaling with Flamecaller's ATK. Healing increases per [Burn] stack currently active across all enemies. CC disables this passive and makes Flamecaller targetable for the duration of the CC.

**Searing Touch** — Single target active. Inflict [Burn] 3 times on the target. Heal all allies for an amount scaling with Flamecaller's ATK, increased by the total [Burn] stacks on the target. 

**Wildfire** — Single target active. Apply [Burn] stacks to the target and steal a fixed percentage of their turn meter. Spread all [Burn] stacks currently on the target evenly across all enemies.

**Scorching Veil** — AoE active. Deal damage to all enemies applying 1 [Burn] stack to each. Apply an ATK-scaling [shield] to all allies, increased by the total number of [Burn] stacks currently active across all enemies.

---

## Minor Pool

Smaller refinements drawn at slots 5 and 6. Always passives.

**Ember Start** — All enemies begin combat with 2 [Burn] stacks.

**Cauterize** — When Flamecaller heals or shields an ally, chance to cleanse 1 debuff from that ally.

**Smoldering Aura** — Enemies that attack Flamecaller receive 2 [Burn] stacks.

**Flashfire** — ATK increases by a fixed percentage per [Burn] stack currently active across all enemies.
