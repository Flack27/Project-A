Combat is the atomic unit of the game. Everything — tower floors, dungeons, expeditions, PvP — is built around this single fight structure. This document defines what happens inside one fight, nothing about how fights are arranged into content.

---

#### Party Structure

Four characters per party. One designated as leader, providing a passive party wide buff determined by their leader trait. The leader slot is a real trade off — one character's combat contribution is partially redirected into a team buff, which may or may not be worth it depending on composition and content.

No roles are enforced. The default safe composition is tank, healer, DPS and flex but nothing prevents running three DPS and a buffer, or two tanks and two supports. The game never tells the player their composition is wrong.

---

#### Turn Order

Turn order is determined by SPD. Every character and enemy has an action bar that fills based on their SPD stat — when it hits the threshold they act and it resets. Higher SPD means the bar fills faster and resets lower, so fast characters act more frequently and can lap slow ones. SPD is the most consequential stat in combat because even small differences compound over a full fight.

Turn order is displayed as a portrait queue at the top of the screen showing the next 8-10 characters in sequence. It updates in real time as SPD buffs, debuffs and bar manipulation effects land. What the player sees is always accurate to the current state of the fight.

Bar manipulation exists as a skill effect — certain skills push an ally's bar forward or pull an enemy's bar back, actively contesting turn order mid fight. This adds a layer of tactical depth without changing the underlying SPD system. Fast teams act more but skilled players can disrupt that advantage through deliberate bar manipulation.

---

#### Skills

Every character has four skills plus a basic attack.

**Basic attack** — always available, no cooldown. Weak damage but has a small tweakable bonus effect depending on the character — a chance to apply a dot, a minor debuff, a small self buff. Generates the character's personal resource. Never a wasted action.

**S2** — player chosen from the weapon technique tree. Medium cooldown. Broad use cases and synergy potential. This is the primary expression of player customisation in combat — two characters of the same archetype can play differently here based on weapon choices.

**S3** — archetype locked. Medium to long cooldown. Directly expresses the character's combat role. A warrior's S3 hits differently to a support's S3 not just in numbers but in what it does and when you want to use it.

**S4** — archetype locked, drawn from the same pool as S3. Medium to long cooldown. Complements S3 rather than duplicating it — the two archetype skills are designed as a kit, each situationally better than the other depending on what the fight demands.

Skills are not a power ladder from weakest to strongest. They are situational tools. Which skill is correct depends on what is happening in the fight — enemy count, HP thresholds, debuff states, turn order position. A well trained character in auto battle reads these conditions and responds. A poorly trained one uses whatever is off cooldown.

---

#### Character Resource

Every character generates a personal resource through basic attacks and certain skill effects. The resource is character specific and does not transfer between party members. Its exact function is defined per character or archetype — for some it enhances a skill's effect when spent, for others it triggers a passive threshold. The resource adds a rhythm of generation and expenditure on top of cooldown management without replacing it.

This system is defined in more detail once archetypes are fully designed.

---

#### Targeting

Players choose targets manually in manual mode — single target skills require selecting an enemy or ally, AoE skills hit all enemies or all allies automatically. In auto battle the AI selects targets based on the character's training, traits and team composition awareness. A well trained character prioritises intelligently. A poorly trained one targets randomly or suboptimally.

---

#### Boss Telegraphing

Bosses can telegraph incoming actions. A charge up state visible one or two turns before a powerful attack lands, giving the player a window to respond — buff DEF, use a shield skill, reposition a vulnerable character. Not every boss attack is telegraphed, only the ones significant enough to warrant a response. In auto battle a well trained team reads telegraphs and responds appropriately.

---

#### Win and Loss Conditions

**Win** — all enemies in the current wave are defeated. In multi wave content this repeats until all waves are cleared. Win conditions specific to content type — defense modes, survival floors — are defined in the tower and dungeon documents.

**Loss** — full party wipe. All four characters are incapacitated. Individual character death during combat is possible and consequential but does not end the fight as long as one character remains standing. Characters who die mid combat have consequences defined in the progression document.

Retreating from combat is possible before a wipe. Consequences for retreat versus wipe are defined per content type in the relevant documents.

---

#### Auto Battle & Manual Play

Combat supports both full manual play and full auto battle with no content locked behind either. Auto battle intelligence scales with character training — a character who has fought extensively with their party plays smarter than one dropped into a random team. Manual play rewards moment to moment decision making, skill timing and target selection. Both are valid paths through all content.

The gap between optimal manual play and well trained auto battle should be meaningful but not punishing — a player who never touches manual should still be able to clear content with a well invested team. Manual play is an edge, not a requirement.