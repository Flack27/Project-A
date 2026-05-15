---
role: tank
scaling:
  - HP
damage type:
  - single target
  - sustained
playstyle:
  - attrition
  - reactive
  - team-dependent
weapons:
  - mace and shield
  - meteor hammer
  - scythe
  - maul
stats: --ATK --SPD ++DEF ++HP
buffs:
  - shield
  - heal over time
debuffs:
  - taunt
  - entangle
  - ATK-
  - DEF-
recovery:
  - cleanse
  - heal
effects:
  - turn meter-
---
Immovable frontline tank that becomes progressively harder to kill and more punishing to attack the longer enemies focus it. Two passive identities produce meaningfully different builds — the thorns passive rewards sustained aggression against Bulwark and eventually forces it through auto-taunt, the mitigation passive rewards enemies for pushing Bulwark low and punishes them for doing so. Neither direction deals significant damage. Combat contribution is measured entirely in how long Bulwark stays standing and how much it costs the enemy to bring it down.

---

## Major Pool

Class-defining skills and passives. Two are drawn across slots 3 and 4, with at least one always being an active.

**Ensnare** — Single target active. Apply [Entangle] and [Turn Meter-] to the target.

**Nature’s Defiance** — AoE active. Apply [Taunt] to all enemies. Apply [DEF-] to all enemies.

**Oakheart Will** — AoE active. Cleanse debuffs from all allies. Apply a HP-scaling [Shield] to all allies.

**Bramble** — Passive. Reflect a fixed percentage of all pre-mitigation damage taken back to the attacker as true damage. Each time damage is reflected, gain one stack. At maximum stacks, apply [Taunt] to all enemies and consume all stacks.

**Undying Grove** — Passive. Damage taken from all sources is reduced by an increasing percentage the lower Bulwark's current HP is. Effect resistance increases by the same scaling. Both effects ramp smoothly from full HP downward with no threshold — the lower Bulwark gets, the harder it becomes to damage or debuff him.

---

## Minor Pool

Smaller refinements drawn at slots 5 and 6. Always passives.

**Rooted** — Each time Bulwark is hit by an enemy attack, gain a small amount of turn meter.

**Immovable** — Turn meter reduction effects applied to Bulwark are reduced by a fixed percentage.

**Ironbark** — The first hit Bulwark receives each turn heals Bulwark for a percentage of max hp

**Undergrowth** — Reduce all critical hit damage received by all allies by a fixed percentage.

---

## Notes

Thornwall and Stone Resolve cannot be drawn together — both are passives and only one major passive slot is available. Thornwall rewards enemies for consistently attacking Bulwark, building stacks toward an auto-taunt that then feeds further reflect and further stacks. Stone Resolve rewards enemies for pushing Bulwark low, making the last portion of his HP the most costly to remove.

Thornwall stack threshold and reflect percentage are placeholder pending balance testing. The reflect is pre-mitigation true damage — it bypasses DEF and damage reduction on the attacker, making it meaningful against high DEF targets.

Rooted and Immovable interact naturally — Rooted generates turn meter from being hit, Immovable prevents that turn meter from being pulled back. Drawing both makes Bulwark increasingly difficult to slow down through bar manipulation the more enemies attack him.

Stone Resolve's damage reduction and effect resistance both scale with missing HP. At full HP the effect is minimal. At low HP both values are significant. Specific scaling curve is placeholder pending balance testing.
