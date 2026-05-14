---
role: tank
scaling:
  - DEF
damage type:
  - single target
  - sustained
playstyle:
  - reactive
  - attrition
weapons:
  - mace and shield
  - sword and shield
  - longsword
  - meteor hammer
stats: =ATK -SPD +DEF =HP
buffs:
  - shield
debuffs:
  - DEF-
  - RES-
  - CRIT Rate-
recovery:
effects:
  - turn meter-
---
DEF-scaling frontline that forces and punishes enemy attention through a persistent threat cycle. At the end of every turn Warden re-enters [Challenge], forcing single target attacks back onto itself — each resolved threat feeds into counter chance built from DEF investment, making the same stat that keeps Warden alive the source of its damage output. Two viable directions: the threat cycling build rewards enemies for attacking into it through guaranteed counters and CC immunity, the DEF stacking build rewards sustained attrition through a full fight. Slow and self-sufficient. Distinct from Guardian which sacrifices offensive presence entirely — Warden threatens through durability rather than despite it.

---

## Major Pool

Class-defining skills and passives. Two are drawn across slots 3 and 4, with at least one always being an active.

**Iron Vigil** — Passive. At the end of each of Warden's turns, enter [Challenge]. While [Challenge] is active, all enemy single target attacks must target Warden. [Challenge] is removed when Warden is hit by a single target skill. If [Challenge] is already active when this triggers, apply a [Shield] to self instead.

**Fortress Stance** — Passive. At the start of combat, gain counter chance equal to a percentage of total DEF. Scales with DEF investment for the duration of combat. Reaches 100% counter chance at maximum DEF investment. Mutually exclusive with Iron Vigil — both are passives and only one major passive slot is available.

**Threatening Blow** — Single target active. Deal X% damage. Apply [DEF-] to the target. Enter [Challenge] after the skill resolves.

**Sunder** — AoE active. Deal X% damage to all enemies. [Strip] one buff from all enemies. Apply [DEF-] and [RES-] to all enemies.

**Dominance** — AoE active. Pull all enemies' action bars back by X%. Apply [CRIT Rate-] to all enemies. Enter [Challenge] after the skill resolves.

---

## Minor Pool

Smaller refinements drawn at slots 5 and 6. Always passives.

**Unbreakable** — Cannot be affected by crowd control while [Challenge] is active. _Requires a skill that applies [Challenge] to be drawn._

**Iron Reprisal** — Counters are guaranteed while [Challenge] is active. _Requires a skill that applies [Challenge] to be drawn._

**Vital Counter** — Counters restore X% of damage dealt as HP. _Requires Fortress Stance or Iron Reprisal to be drawn._

**Ironhide** — The first skill hit received each turn deals X% reduced damage.

**Resilience** — Reduce all incoming damage by 10%.

**Tempered** — Increase DEF by X%.
