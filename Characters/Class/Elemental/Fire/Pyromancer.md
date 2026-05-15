---
role: damage
scaling:
  - ATK
damage type:
  - AoE
  - single target
  - burst
playstyle:
  - aggressive
  - attrition
  - burst
weapons: [staff, tome, orb]
stats: ++ATK =SPD -DEF -=HP
buffs:
  - crit rate+
debuffs:
  - burn
  - unhealable
  - RES-
  - vulnerable
recovery:
effects:
  - turn meter+
---
AoE-focused fire damage dealer built around burn stack generation and detonation. Every skill in the kit applies burn stacks, feeding into detonation payoffs or powering the conversion passive depending on draw. Burn applied by Pyromancer is unresistable — no accuracy investment required. Two distinct playstyles emerge from the minor pool: the stack builder who maximises burn application across the team and detonates for burst, and the converter who suppresses burn application entirely in exchange for higher immediate damage output. Both are self-sufficient without requiring specific major draws to function.

---

## Major Pool

Class-defining skills and passives. Two are drawn across slots 3 and 4, with at least one always being an active.

**Scorched Earth** — AoE active. Deal damage to all enemies. Chance to apply [Unhealable] to all enemies. Apply 1 [Burn] stack to all enemies. Apply 1 additional [Burn] stack to the main target.

**Conflagration** — AoE active. Deal damage to all enemies. Apply 1 [Burn] stack to all enemies. Detonate all [Burn] stacks on all enemies, dealing increased damage per stack consumed.

**Blazing Salvo** — Single target active. Apply [Crit Rate+] to all allies. Strike the target twice, applying 1 [Burn] stack per hit. If the target has 10 [Burn] stacks at the last hit, detonate all stacks instead of applying new ones.

**Searing Assault** — AoE active. Strike all enemies twice. Apply [RES-] and [Vulnerable] to all enemies. Apply 1 [Burn] stack per hit to all enemies.

**Ember Cyclone** — Passive. Every 2 actions, apply [Crit Rate+] to self and immediately cast a free AoE skill dealing a percentage of ATK damage and applying 1 [Burn] stack to all enemies. This action does not count toward the 2-action tracker.

---

## Minor Pool

Smaller refinements drawn at slots 5 and 6. Always passives.

**Intensify** — All class skills apply 1 additional [Burn] stack per hit.

**Smoldering Blade** — All weapon skills apply 1 [Burn] stack per hit.

**Flashpoint** — On critical hit, 50% chance to apply 1 [Burn] stack to the target.

**Pyroclasm** — Pyromancer's skills do not apply [Burn] stacks. Instead each stack that would be applied increases that skill's damage by a fixed percentage. Existing burn stacks on the target are unaffected. This passive converts Pyromancer into a selfish burst dealer — she contributes no burn to the team but deals higher direct damage on every hit.
