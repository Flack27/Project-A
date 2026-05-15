---
role: damage
scaling:
  - ATK
damage type:
  - single target
  - AoE
  - burst
playstyle:
  - aggressive
  - attrition
  - sustained
weapons: [battleaxe, longsword, claws, spear, sword and shield]
stats: ++ATK =SPD --DEF =HP
buffs: []
debuffs:
  - burn
  - RES-
  - unhealable
  - vulnerable
  - turn meter-
  - brand
recovery:
effects:
  - turn meter+
---
Aggressive fire melee damage dealer built around burn application and self-resurrection. Two distinct passive identities both centre on a stack resource that builds through burn application and unit deaths — one cashes stacks out as a resurrection safety net, the other converts them into DEF ignore on weapon attacks. Both can revive but on different conditions and different timings. The kit functions as a pure damage dealer without either passive drawn, with Corpse Detonation and Searing Brand providing burst payoffs independently of the resurrection system.

---

## Major Pool

Class-defining skills and passives. Two are drawn across slots 3 and 4, with at least one always being an active.

**Undying Flame** — Passive. Gain 1 stack at turn start if currently at 2 or fewer stacks. Gain 1 stack per burn stack applied per turn. Gain 3 stacks on ally or enemy death, ally or enemy. Cap at 7 stacks. Maximum 3 stacks gained per turn. On death, if Infernus has 5 or more stacks consume 5 stacks and revive.

**Ashen Core** — Passive. Gain 1 stack at turn start if currently at 2 or fewer stacks. Gain 1 stack per burn stack applied per turn. Cap at 7 stacks. On ally or enemy death gain 3 stacks. Basic attacks apply 1 [Burn] stack per hit. Weapon S2 consumes all current stacks and ignores a percentage of the target's DEF per stack consumed on that hit. On death, if any stacks remain consume all stacks and revive. Long internal CD. 

**Corpse Explosion** — Single target active. Apply [Turn Meter-] and [Brand] to the target. Brand is unremovable. Only one Brand can exist on the battlefield at a time. Apply 1 [Burn] stack to the target. 
If cast on a corpse instead, immediately trigger the AoE explosion and apply [Burn]
When the Branded target dies, automatically trigger the AoE explosion.

**Infernal Surge** — AoE active. Single hit. Chance to apply [RES-] and [Unhealable] to all enemies. Apply 1 [Burn] stack to all enemies.

**Searing Brand** — Single target active. Strike the target 3 times applying 1 [Burn] stack per hit. If the target has 10 [Burn] stacks after the third hit, detonate all stacks.

---

## Minor Pool

Smaller refinements drawn at slots 5 and 6. Always passives.

**Deathwish** — Each unit death permanently increases Infernus's ATK by a fixed amount for the rest of combat. Infernus's own revives count as a death trigger. caps at X amount.

**Ember Skin** — At the start of each turn cleanse 1 debuff from self.

**Pyre** — On revive or on [Branded] target death, apply [Unhealable] and [Vulnerable] to all enemies. (requires Undying Flame, Ashen Core or Corpse Explosion)

**Ignition** — On revive or on [Branded] target death, gain a large [Turn Meter+]. (requires Undying Flame, Ashen Core or Corpse Explosion)

---

## Notes

Undying Flame and Ashen Core cannot be drawn together. Undying Flame requires 5 stacks to revive and builds stacks faster through death triggers, rewarding fights with multiple units dying. Ashen Core revives on any remaining stacks but has a long internal CD, rewarding sustained burn application and deliberate stack management around weapon S2 usage.

Searing Brand checks burn stack count after the third hit resolves. If stacks reach 10 during the first or second hit the remaining hits still apply burn normally — detonation only fires at the end of the skill.

Brand is a debuff in the dark red LD-adjacent icon colour to distinguish it from standard debuffs. It cannot be cleansed, stolen, copied or extended. Only one Brand can exist at a time — applying Brand to a new target removes it from the previous target without triggering the explosion.

Corpse Detonation's AoE explosion triggered by Brand death and the direct cast on a corpse produce identical output — same damage, same burn application. The trigger method does not change the explosion value.

Pyre and Ignition both trigger on revive and on Corpse Detonation explosion. Drawing both produces a character who gains turn meter and applies team-wide debuffs simultaneously on either trigger. Strong in content where Infernus dies frequently or where Corpse Detonation fires often.
