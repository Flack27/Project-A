---
role: tank
scaling:
  - DEF
damage type:
  - single target
playstyle:
  - reactive
  - team-dependent
weapons: [sword and shield, mace and shield, longsword, meteor hammer]
stats: --ATK -SPD ++DEF +HP
buffs:
  - damage reduction
  - endure
  - DEF+
  - shield
  - immunity
debuffs:
  - taunt
  - ATK-
recovery:
effects:
---
Active protection class that intercepts damage and punishment aimed at allies rather than just absorbing it through bulk. Intercept transfers incoming damage from a protected target to Guardian directly. Taunt pulls enemy attention. Damage output is low and not the point — Guardian's combat contribution is measured entirely in how much the rest of the team survives to act.

---

## Major Pool

Class-defining skills and passives. Two are drawn across slots 3 and 4, with at least one always being an active.

**Intercept** — Single target active. Apply a persistent buff to target ally. While active, Guardian takes X% of all damage directed at that target. Undispellable — cannot be stripped or cleansed from either character.

**Rallying Ground** — AoE active. Remove all debuffs from all allies and apply them to self. Grant Immunity to all allies except Guardian for the duration. Distinguishes from a clean mass cleanse — Guardian absorbs what the team shed, allies are protected from reapplication.

**Fortress Ward** — AoE active. Apply DEF+ and Endure to all allies.

**Shield Wall** — AoE active. Apply Taunt to all enemies. Apply a DEF-scaling Shield to self and a smaller DEF-scaling Shield to all allies.

**Iron Sentinel** — Passive. Gain a stacking DEF buff each time an ally takes damage from an enemy action. Stacks once per enemy action regardless of how many allies are hit — AoE attacks grant one stack. Cap at 10 stacks. Stacks are lost at the end of combat.

---

## Minor Pool

Smaller refinements drawn at slots 5 and 6. Always passives.

**Stalwart** — While Guardian has an active Intercept target or while any enemy is Taunted, reduce all damage taken by a fixed percentage.

**Provoke** — When this character takes damage, %chance to apply Taunt to the attacker.

**Bastion** — At combat start, apply a DEF-scaling Shield to all allies. Triggers before the first action regardless of turn order.

**Cover** — Passive with cooldown. When a hit that would kill an ally lands, Guardian intercepts it instead, taking the full hit at double damage. Guardian's DEF applies normally. Cooldown begins after activation.

**Unyielding** — When the last remaining ally would be killed, Guardian dies in their place. That ally is restored to Guardian's current HP at the moment of death and gains Invincibility for one turn.

**Retribution** — While Intercept is active on a target, Guardian counters with a basic attack whenever that target is attacked. Only appears in the minor draw pool if Stalwart already occupies a passive slot on this character. (Requires Intercept)
