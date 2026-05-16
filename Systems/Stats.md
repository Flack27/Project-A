Stats govern every combat interaction in the game. Primary stats define a character's baseline capability. Secondary stats are built through gear and skills. Two derived values — effect accuracy and effect resistance — govern debuff application. All stats interact through defined formulas rather than flat comparisons.

---

## Primary Stats

**ATK** — determines damage output on offensive skills and basic attacks. Scales with gear and passives for damage dealing classes.

**DEF** — reduces incoming damage through a damage reduction formula rather than flat subtraction. Higher DEF produces diminishing returns, preventing pure DEF stacking from becoming an impenetrable wall.

**HP** — total health pool. Loss of all HP removes a character from combat. Unlike DEF, HP is a fixed value with no diminishing returns — it is always worth stacking for survivability.

**SPD** — determines how quickly the action bar fills. The most consequential primary stat in combat. Small SPD differences compound over a full fight — a faster character acts more frequently and can lap a slower one entirely. SPD is always a flat value, never a percentage.

All four primary stats have a base value determined by race and a variance range determined by growth rate. Two characters of the same race and star level will have similar but not identical stats. See [[Characters/Stats/Stats|Stats]].

---

## Secondary Stats

Secondary stats have no meaningful base value — differentiation comes entirely from gear, glyphs, skills and passives. All characters begin at the same baseline.

**Crit Rate** — probability of landing a critical hit. Base value is 15%. Caps at 100%. Once 100% is reached every attack crits and further crit rate investment has no value — pivot entirely to crit damage at that point.

**Crit Damage** — damage multiplier applied on a critical hit. Base value is 150%. No cap. The optimal balance point between crit rate and crit damage is when both are roughly equal — whichever is lower is the better investment until they meet.

**Effect Accuracy** — improves the chance of landing debuffs. Interacts with effect resistance through the formula below. Going above the resistance floor still has value — see formula section.

**Effect Resistance** — reduces the chance of receiving debuffs. Has a base floor of 15% that cannot be reduced below regardless of how much accuracy the attacker has. Worth investing in on characters who need to resist CC.

---

## Damage Formula

Damage is calculated as:

**ATK × Skill Multiplier × Crit Modifier × DEF Reduction Factor**

DEF reduces damage through a scaling formula rather than flat subtraction. The exact values are placeholder until combat is playtested — the principle is that DEF provides meaningful reduction at all investment levels without hard countering offensive stats entirely.

Crit Modifier is 1.0 on a normal hit and the character's crit damage value on a critical hit.

---

## Debuff Application Formula

When a skill attempts to apply a debuff the chance is calculated as:

**Skill Base Chance × (1 + Attacker Accuracy − Target Resistance)**

The result is the actual probability of the debuff landing. Key rules:

- Target resistance cannot go below 15% regardless of attacker accuracy. There is always a minimum chance of resisting.
- Each debuff on a multi-effect skill is calculated separately — landing one does not guarantee the others.
- On multi-hit skills each hit rolls independently. A skill that hits 4 times with a 25% base chance gives four separate rolls, not one 100% roll.
- The formula applies after the base chance check — a skill with a 50% base chance at 100% accuracy against 0% resistance gives 50% × (1 + 1.0 − 0.0) = 100%, but the 15% resistance floor reduces this to an 85% actual application chance.

_Example:_ A debuffer with 60% accuracy uses a skill with a 70% base chance against a target with 40% resistance. 70% × (1 + 0.60 − 0.40) = 70% × 1.20 = 84%. Target's resistance floor is 15% so actual chance is min(84%, 85%) = 84%.

_Example:_ Same debuffer against a high resistance target at 90% resistance. 70% × (1 + 0.60 − 0.90) = 70% × 0.70 = 49%.

---

## Crit Rate & Crit Damage Interaction

Average damage from a damage dealer is a function of both stats:

**Average Damage = Base Damage × (1 + Crit Rate × (Crit Damage − 1))**

Because crit damage starts at 150% (a 0.5 multiplier above baseline), crit rate needs to reach 50% before further crit damage investment outpaces further crit rate investment. Below 50% crit rate, crit rate is always the better stat to build. Above 50%, the better investment is whichever is lower — match them for optimal average damage output.

---

## Notes

Specific DEF formula values, skill multipliers and stat scaling numbers are placeholder until combat is playtested and the balance simulation is run. See Loose Threads — Economy Balancing. The structure and formulas above are fixed. The numbers are not.