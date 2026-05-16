## Philosophy

This game is designed to be fully playable without spending money. A player who never spends progresses at the same pace, summons regularly, and reaches the same ceiling as a paying player. The battlepass is the only monetization layer and provides minor convenience, not power or meaningful acceleration.

Gems are earned by playing. They are not sold in quantities that change the equation between a spender and an engaged f2p player.

---

## Gem Flow

Gem income is built around two phases that naturally offset each other.

In the early game, tower floor first clears are the primary source. New players clear floors quickly, the progression guide provides structured one-time milestone rewards, and gems flow at a rate that feels generous. Summoning feels frequent and accessible.

As players climb deeper, floor progression slows and first-clear rewards thin out. This is offset by content unlocking across lobby tiers — guild activities, PvP, daily boss, RTA, guild raids, and lobby raids all come online and each carries its own gem income. A player engaged across all available content at a given tier earns comparable gems to a player blazing through early floors.

The income curve stays roughly smooth because content breadth compensates for progression slowdown. The player's relationship with the game shifts from climbing to breadth, but the reward rate holds.

---

## Gem Sources by Lobby Tier

**Tier 1–2 (floors 1–15)** — Tower first clears, progression guide milestones. High flow, finite.

**Tier 3 (floors 16–30)** — Tower clears slow. Guild activity rewards begin.

**Tier 4 (floors 31–50)** — Daily boss completion rewards, PvP season end rewards come online.

**Tier 5 (floors 51–70)** — RTA participation rewards, bounty board weekly completion, faction shrine passive trickle.

**Tier 6 (floors 71–90)** — Guild raid rewards, guild vs guild participation, lobby raid rewards.

**Tier 7 (floors 91+)** — Artifact content rewards, full content breadth active.

Events provide periodic gem injections at every tier outside this baseline.

---

## Energy Model

**Rates**

- Passive refill: 1 energy per 3 minutes — 480 per day
- Cap: 240 — full bar every 12 hours for players who log in twice daily
- Energy cost: 10 per run for tower, dungeons and trials. 5 per run for expeditions.
- Gems can be spent to purchase additional energy. Daily purchase limit applies.

**Run times**

- Tower floors: ~3 minutes average, harder at the current progression ceiling
- Dungeons: 3–5 minutes average (~4 minutes)
- Trials: ~3 minutes
- Expeditions: 10 minutes base, reduced to 6 minutes with a Tier 3 Scout

---

## Reference Players

Two reference profiles are used for all cost and income modelling. All building costs, upgrade costs and crafting recipes are balanced so the passive player can complete them over natural progression without feeling blocked. The active player reaches the same endpoints faster by converting gem income into energy rather than summons.

**Passive player — 480 energy per day**

- Expeditions: 150 energy → 30 runs (passive, background)
- Active content: 330 energy → 33 runs × 4 min ≈ 2 hours

**Active player — 1500 energy per day**

- Expeditions: 300 energy → 60 runs (passive, background)
- Active content: 1200 energy → 120 runs × 4 min = 8 hours

Active content split at steady state (shifts toward dungeons in late game):

|Content|Energy|Runs|
|---|---|---|
|Tower|400|40|
|Dungeons|500|50|
|Trials|300|30|

---

## Expedition Resource Income

Expedition zones each produce two resource types — a primary and a secondary. Base yield per run is 20 units primary, 10 units secondary. All tiers yield the same unit counts — resource tier determines which recipes the materials feed, not how much drops per run.

**Zone pairings**

- Forest: Wood (20) / Herbs (10)
- Mine: Stone (20) / Iron (10)
- Crystal Cave: Crystal (20) / Aether (10)

**Expedition slots** — start at 1, slot 2 unlocks at lobby tier 3, slot 3 at lobby tier 6. Each additional slot runs a separate zone simultaneously. Income scales directly with slots.

**Vocation bonuses**

- Scout (T3): 40% run time reduction — effectively increases daily runs in a fixed time window
- Harvester (T3): +50% yield per resource type per run
- Combined at lobby 6–7: assumed active for cost anchoring at that tier

**Daily primary resource income by lobby tier**

|                         | Passive (30 runs) | Active (60 runs) | Active + T3 Harvester / Scout |
| ----------------------- | ----------------- | ---------------- | ----------------------------- |
| **Lobby 1–2** (1 slot)  | 600               | 1200             | 2400                          |
| **Lobby 3–5** (2 slots) | 1200              | 2400             | 4800                          |
| **Lobby 6–7** (3 slots) | 1800              | 3600             | 9600                          |

Secondary resource income is half the primary values throughout.

---

## Building Cost Anchors

Costs are set against active player income (non-optimised baseline). Vocations compress these timescales by 50–100% at peak — floor 7 at full optimisation takes roughly 3 months rather than 8. Floor 1 costs reflect the tutorial pace where buildings feel cheap and fast to repair or construct.

| Lobby Floor | Timescale (base) | Active Income | Total Primary Units |
| ----------- | ---------------- | ------------- | ------------------- |
| 1           | ~100 min         | 1,200/day     | ~200                |
| 2           | 1 day            | 1,200/day     | 1,200               |
| 3           | 1 week           | 2,400/day     | 16,800              |
| 4           | 1 month          | 2,400/day     | 72,000              |
| 5           | 2 months         | 2,400/day     | 144,000             |
| 6           | 4 months         | 3,600/day     | 432,000             |
| 7           | 8 months         | 3,600/day     | 864,000             |

Total units are spread across all buildings and upgrade tiers on that floor. Individual building costs are derived by dividing the floor total across its building count and upgrade tier count. Specific values are set per building doc. All numbers are anchors pending simulation. See Economy Balancing in Loose Threads.