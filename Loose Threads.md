
Ideas that came up but don't have a home yet. Pull from here when the relevant 
system file gets written.

---

**Character Death & Recycling Narrative**
What happens to dismissed or dead characters in the world's logic — do they 
return to stasis? Is this even their real body? Player may be able to control 
information flow to remaining characters. Characters could have morale and 
relationship systems affected by losing someone they bonded with. Player can 
potentially deceive them about what happened. Ties into the grey moral tone of 
the Architect role. Belongs somewhere in Systems or Story, not figured out yet.

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

**The Manager's Backstory**
Hinted that the Manager has seen something like this before and knows more than 
they let on. Never decided what they actually know, how they ended up in the 
lobby, or how their knowledge drip feeds into the story without resolving things 
too early. Key character that needs proper thought when Story.md gets written.

---

**Faction Buffs & Story Branch Points**
Two major story choices that split the playerbase into factions, first choice 
creates two factions, later choice splits both again into four. Each faction gets 
a minor mechanical buff reflecting the philosophical choice made. The nature of 
the choices, what they are actually about, and what the buffs look like are all 
completely open. The principle is just that neither choice is clearly correct and 
the buffs are flavor not competitive advantage.

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

**The Ethics of Dismissal** Characters in this game are people pulled from a frozen world, not disposable units. If dismissal and summoning become routine economic actions the player is by default making morally significant decisions about real lives within the fiction — dismissing a character who has developed bonds, traits and memories is not a neutral act in the world's logic. This tension fits the grey moral tone of the Architect role and could be one of the most interesting narrative threads in the game if handled deliberately. What happens to dismissed characters — do they return to stasis, cease to exist, go somewhere unknown — and how much the player knows or is told about this is a significant story decision. Characters who witnessed a dismissal might react to it. The Manager almost certainly has an opinion they won't fully share. This is already touched on in Loose Threads under Character Death and Recycling Narrative and belongs in the Story document when that gets written.

---

**Synthesis Duality & Faction Alignment** A potential system where synthesis has two paths rather than one. Not strictly good vs evil but two philosophies about what these characters are and what they are worth. One path treats synthesis as a necessary pragmatic action — characters are tools for climbing the tower, their sacrifice serves the greater purpose. The other treats it as something weightier, more ceremonial, more costly but more respectful of what is being lost. Neither is objectively better mechanically but they produce different outcomes and different relationships with surviving characters.

This ties directly into the faction system already outlined — the first major story branch point could be rooted here. The player's approach to synthesis over time, or a single significant choice moment, aligns them with one philosophy. This shapes how the Manager behaves toward the player and the characters — a pragmatic Architect gets a Manager who becomes more efficient and detached, ordering characters around, not grieving losses. A more sympathetic Architect gets a Manager who becomes warmer, more protective of characters, more conflicted about the tower's demands. The Manager's behavior becoming a mirror of the player's choices is a strong narrative device that makes the faction choice feel lived rather than selected from a menu.

Needs full development in the Story document. Connects to the existing faction buff system in Loose Threads.

---

**The Manager's True Nature** The Manager knows more than they let on from the start. Early on this reads as competence and familiarity with the lobby. Later it becomes clear the knowledge runs deeper — she has seen something like this before, possibly been here before, possibly been something other than what she presents as.

Her story should unfold in layers across the full game. Early game she is helpful and slightly evasive. Mid game contradictions appear in what she says versus what she knows. Late game her actual nature and history become a central question. What she is — a previous Architect, a construct of whatever built the lobby, something that survived a previous version of this — is deliberately unresolved here and should be designed as part of the full story document.

Her behavior shifting based on player faction alignment adds another layer — the same underlying person expressing differently depending on what kind of Architect the player has chosen to be. Whether she approves or disapproves of that choice, and whether she ever says so directly, is a key character design question.

---

**The Architect's True Nature** The player experiences the game as the Architect — the unseen hand making decisions, moving characters, choosing who lives and who is synthesized. But whether the player actually is the Architect or is themselves just another piece of the mechanism is left deliberately open.

The Architect as a concept predates the player's arrival. The lobby existed before the player logged in. The Manager was already there. Who or what set this in motion, whether the Architect is a role being filled or an entity with its own history, and what the tower actually is at its deepest level are the central mysteries of the story. These should unfold slowly across the full game with no clean resolution — the grey is the point.

The synthesis duality and faction system should feed into this. The kind of Architect the player becomes shapes what the tower reveals and how the Manager interprets what is happening. Two players who reach the same late game floor may understand the Architect completely differently based on the choices made along the way.

Full development belongs in the Story document. The Manager's story and the Architect's true nature are probably the same story told from different angles.

---
**Bond-Based Reactive Combat** Characters with a strong lobby bond occasionally react to each other mid-fight — covering a debuff, following up on a kill, throwing a small shield when a partner drops below a threshold. Not scripted combos, emergent reactions based on bond strength. Needs boundary-setting so it stays a flavor layer and doesn't become a required synergy system. Ties directly into the morale and relationship systems and makes lobby attachment feel mechanical rather than just flavor. Design belongs in a combat addendum or relationship systems doc when those get written.

---
**Exotic Stat Scalings** Niche scaling stats that create distinct build identities beyond standard ATK/DEF/HP/SPD. All of these belong in class skills or major passives rather than weapons — exotic scalings are too niche to put on a weapon every class might use. Design these when class passive pools get built out.

- EFF ACC scaling — skill damage or effect magnitude scales with effect accuracy instead of ATK. Natural home: debuffer major passive. Creates a completely distinct gearing target for dedicated debuffers.
- Counter chance scaling — damage or utility scales with counter chance stat. Natural home: class passive or class skill for a counter-build archetype. Pairs with the Counter buff already in the status effects doc.
- Crit rate scaling — a skill or passive that converts excess crit rate above 100% into another stat, e.g. crit damage or ATK. Natural home: major passive. Rewards over-investing in crit rate rather than wasting it.
- HP scaling on offensive skills — skill damage scales with max HP rather than ATK. Natural home: water melee or tank-adjacent class, already partially flagged in Water Melee doc. Ties into the lifesteal / low HP mechanic noted there.
- DEF scaling on offensive skills — already exists on earth mage and earth melee. Worth ensuring this is expressed through a major passive option as well as the base class scaling, so non-earth classes can access a minor version through passive draws.
- SPD scaling on damage — already exists on wind classes. Consider whether a major passive version exists for physical classes who want to dip into it without being wind archetype.
- Shield scaling with ATK — a passive where shields generated scale with ATK rather than DEF or HP, enabling offensive characters to generate meaningful shields as a side effect of damage investment.