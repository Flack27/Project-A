
Ideas that came up but don't have a home yet. Pull from here when the relevant 
system file gets written.

---

**Permadeath Penalty System**
Characters don't permanently die but losing one has a real cost — resources, 
time, something that makes it sting without being punishing. The penalty should 
be significant enough that players feel the loss but never so harsh that it 
kills attachment to risky characters. Exact mechanic not decided.

---

**Morale & Relationship System**
Characters are affected by who they fight with, who they've bonded with, who 
they've lost. Touched on this in the context of auto-battle behavior and 
personality but never defined how deep it goes mechanically. Could be as light 
as combat stat modifiers or as deep as characters refusing certain actions based 
on relationships. Needs a boundary set so it stays a flavor system and doesn't 
become a management chore.

---

**Guild Content**
Flagged as a milestone unlock somewhere in the mid tower. Never discussed what 
it actually is — cooperative boss fights, shared progression, competitive guild 
vs guild, some combination. Needs its own systems file eventually.

---

**PvP System Specifics**
Late game tower unlock, the format is completely open. Async or live, how teams 
are submitted, how matchmaking works, how to keep it from immediately becoming 
p2w once competitive stakes exist. The philosophy is that it should reward gear 
and synergy knowledge over spending but the actual design is untouched.

---

**Economy Balancing** The crystal, energy and summoning economy requires extensive simulation and playtesting before any numbers are finalised. The core tension between summoning and energy recharging, the rate at which crystals flow through normal play, the time cost of training a character to 3 star before evaluation, the dismiss value relative to ascension material costs — all of these interact in ways that are impossible to balance theoretically. A simulation model should be built early that models a typical player's crystal income versus spend across several months of progression before launch. Numbers in all related documents are placeholders until that simulation validates them.

---
**Bond-Based Reactive Combat** Characters with a strong lobby bond occasionally react to each other mid-fight — covering a debuff, following up on a kill, throwing a small shield when a partner drops below a threshold. Not scripted combos, emergent reactions based on bond strength. Needs boundary-setting so it stays a flavor layer and doesn't become a required synergy system. Ties directly into the morale and relationship systems and makes lobby attachment feel mechanical rather than just flavor. Design belongs in a combat addendum or relationship systems doc when those get written.

---
**Loose Thread: Visual Asset Generation Pipeline Spec** Design the input spec for AI art and mesh generation alongside the character system rather than retrofitting it later. When generation tools are ready, a defined set of inputs per character - race templates, body type parameters, age reads, personality visual signals, style reference anchors - means the transition from placeholder to real assets is clean and consistent across a large roster. Mirrors the tag structure already designed for memory fragment generation. No action needed until the art and mesh pipeline is being built, but the input schema should be drafted when the character system is stable.

---

Using actual statistics for the testing / balancing and data management?
make sure to save A LOT of data when game is live

---

PvP ideas
actually attacking a lobby?
tournament style event with 1 v 1, 2 v 2, 4 v 4?

---

leaderboards with meaningful rewards in pvp and pve
rewards for unlocking unique classes and skills
rewards for achievements

---

**Duplicate Class Stacking** A hard one-per-class party restriction was considered and rejected on attachment philosophy grounds — players raise the characters they have and should be able to run two of the same class if that's what they built. The concern is real though: certain class combinations become degenerate at two copies in ways that single instances don't. Speed supports trivializing turn order through stacked bar manipulation, tank classes creating unkillable walls, debuff classes overwhelming cleanse capacity. These need to be checked per class during balance passes rather than solved with a blanket rule. The fix in each case likely lives at the mechanic level — diminishing returns on stacked bar push effects, unique debuff rules limiting one instance per effect type per target, numbers tuning. Doom is already partially addressed by being Harrower-exclusive, limiting the most obvious multi-copy loop. Other classes need equivalent checks when their stacking case is clearly broken.

---

what happens when a character has a weapon equipped but gets a class that cant have that weapon equipped

---
game mode to obtain angel / demon
event where rare drop chance increases, gold increases etc.

---
cool animations in game when you go into tower / dungeon zoom into portal