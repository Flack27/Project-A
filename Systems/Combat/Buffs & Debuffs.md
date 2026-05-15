All buffs and debuffs in the game use a standardized vocabulary. Every effect has a fixed name and fixed mechanical definition regardless of which class, weapon or skill applies it. A warrior's ATK up buff and a support's ATK up buff are identical in effect — the difference is in how and when they are applied.

Effects are applied to a single target unless otherwise noted. Duration is defined per skill. Buffs appear as blue icons on the affected character, debuffs as red icons. Light and dark exclusive effects use their own icon colour and are described in their own section at the end of this document.

Effects fall into six categories. The first five are persistent — they sit on a character with a defined duration and can interact with cleanse, immunity, block and similar systems. The sixth category covers instant effects that resolve at the moment of application and have no duration.

---

## Buffs

Persistent positive effects with a defined duration.

**ATK Up** — increases ATK by a fixed percentage for the duration.

**DEF Up** — increases DEF by a fixed percentage for the duration.

**SPD Up** — increases SPD for the duration, accelerating action bar fill rate.

**Crit Rate Up** — increases crit rate by a fixed percentage for the duration.

**Crit Damage Up** — increases crit damage by a fixed percentage for the duration.

**Effect Accuracy Up** —  increases effect accuracy by a fixed percentage for the duration.

**Shield** — absorbs a set amount of damage before HP is affected. Removed when the shield value is depleted or the duration expires. Shield value is defined by the skill that applies it, often scaling with the caster's DEF or HP.

**Heal Over Time** — restores a fixed amount of HP at the start of each turn for the duration.

**Damage Reduction** — reduces all incoming damage by a fixed percentage for the duration.

**Immunity** — blocks all incoming debuffs for the duration. Debuffs that would land during immunity are ignored entirely.

**Invincibility** — blocks all incoming damage for the duration. Cannot be extended or refreshed. Always short duration.

**Counter** — perform a basic attack counter when attacked for the duration.

**Guard** —  the caster of this skill will take %of the damage reduced by a % instead of the attacked ally 

**Stealth** —  cannot be selected as the main target of enemy skills and decrease aoe dmg by 50%

**Endure** — cannot fall below 1 hp.

---

## Recovery

Effects that restore HP, clear debuffs or return fallen characters to combat.

**Heal** — restores a fixed amount of HP. Instant.

**Cleanse** — removes a set number of debuffs from the target immediately. Not a duration effect. Number of debuffs removed is defined per skill.

**Revive** — brings a fallen character back at a set HP threshold when triggered. Applied proactively before death as a persistent buff and consumed on activation.

---

## Debuffs

Persistent negative effects with a defined duration. Crowd control and damage over time are categorised separately.

**ATK Down** — decreases ATK by a fixed percentage for the duration.

**DEF Down** — decreases DEF by a fixed percentage for the duration.

**SPD Down** — decreases SPD for the duration, slowing action bar fill rate.

**Crit Rate Down** — decreases crit rate by a fixed percentage for the duration. Counters crit-heavy damage dealers specifically without affecting non-crit builds.

**Effect Accuracy Down** — decreases the target's effect accuracy for the duration.

**Effect Resistance Down** — decreases the target's effect resistance for the duration, making further debuffs easier to land.

**Unhealable** — prevents the target from receiving any healing for the duration. Does not affect shields already applied.

**Block** — prevents the target from receiving buffs for the duration.

**Pinned** — Unable to gain Action bar+ effects.

**Mark** — perform a basic attack follow-up when a crit is scored against this target by an ally (only 1 mark can be active at a time)

**Vulnerable** — target takes increased damage from all sources for the duration. Amplifies the whole team's damage against a single target, creating a focus fire dynamic distinct from DEF Down.

---

## Crowd Control

Persistent effects that prevent or restrict a character's actions. All CC effects pause cooldown progression for their duration except silence.

**Stun** — target cannot act for one turn.

**Entangle** — target cannot act for one turn. Action bar+ effects are 50% effective.

**Sleep** — target cannot act. Breaks immediately on taking damage. Characters in sleep take increased damage from the hit that wakes them.

**Silence** — target cannot use skills for the duration. Basic attack still available. Cooldowns continue to progress.

**Taunt** — target is forced to attack the character who applied the taunt for the duration.

---

## Damage Over Time

Persistent effects that deal damage at the start of the affected character's turn. Multiple stacks of the same DoT type can exist simultaneously unless otherwise noted.

**Burn** — deals damage each turn. Scales with the ATK of the character who applied it (ignoring def). Associated with fire element. Interacts with fire skills and passives. Detonation mechanic that consumes the stack and deals some %hp damage based on stack count

**Bleed** — deals 1%HP damage each turn (ignoring def). Stackable up to 5-8 times. Detonation mechanic that deals stack count × multiplier × caster ATK

---

## Instant Effects

No duration. Resolve at the moment of application. Cannot be blocked, cleansed, prevented by immunity, or interact with any persistence-based system.

**Strip** — removes a buff from the target. Number of buffs removed is defined per skill.

**Steal** — removes a buff from the target and applies it to the caster with the remaining duration. Distinct from strip — the buff is not destroyed, it is transferred.

**Bar Push** — moves the target's action bar forward by a fixed percentage immediately. Ally only.

**Bar Pull** — moves the target's action bar backward by a fixed percentage immediately. Enemy only. (can be blocked by immunity)

**CD Reduction** —  reduces the target's remaining cooldowns by x amount of turns.

---

## Light & Dark Exclusive

Effects only appliable by light and dark subclasses. Standard elemental and physical classes cannot apply these under any circumstance, regardless of gear, technique tree or passive draws. This is the primary mechanical expression of LD distinctness — LD subclasses access a vocabulary of effects the rest of the roster cannot reach. The rarity of LD characters is reinforced by the rarity of these effects appearing on the battlefield.

LD effects use their own icon colour distinct from standard buffs and debuffs.

### Dark Exclusive

**Oblivion** — suppresses the target's passive effects for the duration. Passives that are active on the target are disabled and do not trigger while oblivion is applied. Distinct from silence which blocks active skills only. Particularly relevant in PvP where passive identity is a significant part of a character's combat contribution.

**Doom** — countdown debuff with a visible turn counter. Ticks down at the start of each of the target's turns. When the counter reaches zero, deals significant damage to the target and is removed. Cannot crit, damage scales with casters attack, ignore defense and stun at the end?

**Wither** — absorb healing equal to a %. When the effect expires naturally deal true damage equal to the remaining amount.

### Light Exclusive

**Sanctuary** — buff. The target cannot be targeted by any skill or attack, single target or AoE, and cannot receive debuffs for the duration. A stronger and more restrictive version of conventional protection effects, balanced by long cooldown on the skills that apply it. The target can still act normally — sanctuary only blocks incoming targeting and debuff application.

**Resurrection** — passive buff that triggers once per combat. When the target would be reduced to zero HP, instead they are restored to full HP and the buff is consumed. Distinct from revive — resurrection prevents the death outright rather than reversing it.

not a status effect but a passive that passively grants the whole team healing, shielding or cleanses a debuff at the start of the light characters turn

---

## Notes

Specific percentage values, durations and damage numbers for all effects are placeholder until combat is playtested. The definitions and category placements above are fixed. Numbers are not.

Immunity does not remove existing debuffs — it only blocks new ones. A character with existing debuffs who gains immunity retains those debuffs until they expire naturally or are cleansed.

Instant effects bypass immunity, cleanse and block entirely. A character with immunity can still have their buffs stripped or stolen — these effects are not considered debuffs and do not check against immunity systems.

Cleanse removes debuffs only. Buffs cannot be cleansed from a character by their own team. Strip removes them, on the enemy side.

Oblivion, doom, wither and deep wither cannot be applied by any non-dark class. Sanctuary, resurrection, aegis, foresight and grace cannot be applied by any non-light class. This restriction is absolute — no gear, technique tree, passive draw or status interaction grants access to LD effects to a non-LD character.