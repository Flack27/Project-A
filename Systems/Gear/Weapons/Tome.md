---
scaling:
  - ATK
  - HP
buffs:
  - shield
  - heal
  - heal over time
debuffs:
recovery:
  - heal
  - heal over time
effects:
  - cd reduction
---
### Basic Attack

Single target magic strike. ATK scaling. Branches into shielding, healing or cooldown manipulation through technique development.

→ **Shield path** — lower damage, small self-shield on hit, shield magnitude scales with HP
→ **Heal path** — lower damage, small self-heal on hit, heal magnitude scales with HP 
→ **Cooldown path** — lower damage, small chance on hit to reduce a random ally cooldown by 1 turn

---

### Technique Tree

Tome is the support magic weapon. Three branches, each with its own scaling stat. Tome is the weapon where scaling branches genuinely fork — unlike staff and wand which stay ATK across all paths, tome's branches scale on different stats to fit the classes that gravitate toward them.

→ **Shielding branch** — techniques that apply shields to allies. Shield magnitude scales with the caster's HP. Fits Earth Mage and any class building toward shield identity. 
→ **Healing branch** — techniques that restore HP to allies, including direct heals and heal over time. Heal magnitude scales with the caster's HP. Fits Water Support, Wind Support and any class that wants real healing access. 
→ **Cooldown reduction branch** — techniques that reduce ally skill cooldowns. ATK scaling on the damage component. Two technique variants exist within the branch:
- **All allies, single turn** — reduces every ally skill cooldown by 1 turn. Broad utility, moderate cooldown.
- **Single ally, all skills** — reduces all of one ally's cooldowns by 1 turn. Concentrated value on a single character, moderate cooldown.

---

##### Notes

Tome is the only magic weapon where the equipping character's class scaling stat meaningfully changes what techniques produce. A Fire Mage using the healing branch generates smaller heals than a Water Support using the same technique, because the magnitude scales with HP and Fire Mage builds against HP. This is intended — tome rewards alignment between class scaling and branch choice while remaining universally equippable.

The cooldown reduction branch is the universal third option. Power ceiling is intentionally capped at -1 turn rather than full skill resets to keep the mechanic from compounding into rotation breaking.

Specific technique lists, shield and heal magnitudes, cooldown values and the balance between the two cooldown reduction variants are placeholder until combat is playtested.