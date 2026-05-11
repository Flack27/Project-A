Technical reference for how memory fragments are generated per character. This governs the AI content pipeline, not the player-facing system. For the player-facing design see [[Memory Fragments]]

---

## Input Tags

Every character is assigned a set of tags at summon that serve as generation inputs across all fragments. These are internal values, never shown to the player.

**Archetype tag** — broad life context. Examples: farmer, soldier, noble, scholar, craftsman, criminal, wanderer, clergy. Derived from a weighted roll influenced by race and appearance. Not a hard mapping — a young character rolls from a pool that includes soldier's apprentice, noble's child, street kid and others, not just farmer's son.

**Appearance and age tag** — young, middle aged, old, combined with broad appearance reads. Influences how the archetype tag is expressed. A young scholar reads differently to an old one. Feeds into archetype tag weighting rather than operating independently.

**Personality tag** — one flat trait either already unlocked or rolled at summon as a seed. Shapes the voice and self-presentation of fragment 1. A calm farmer and a reckless farmer describe themselves completely differently. This tag is always present even if the trait never unlocks — it exists as a generation input only.

---

## Fragment 1 — Self Impression

**Inputs:** archetype tag, appearance and age tag, personality tag

No event tag. No trait link roll. Fragment 1 is always a self-description in the character's own voice — who they are, how they carry themselves. The personality tag shapes the voice. The archetype and age provide context.

Fragment 1 never carries an explicit trait tag in the UI. The personality signal is present in the text for players who read carefully but is never labelled.

---

## Fragments 2 and 3 — Memories

**Inputs:** archetype tag, appearance and age tag, event tag, trait link roll

**Event tag** — rolled independently from the archetype tag. Examples: loss, discovery, conflict, peace, failure, connection, departure. The combination of archetype and event is what produces variety. A soldier with a loss event and a farmer with a loss event produce completely different fragments despite sharing an emotional beat. The matrix of combinations keeps repetition low across a large roster.

**Trait link roll** — determines whether this fragment has a mechanical trait connection. Should fire less than half the time so fragments without trait links are common and expected. If the roll succeeds, two further rolls happen:

- Which trait is linked — drawn from a pool compatible with the archetype and event tag combination
- Link strength — one of three states:
    - Unlock — trait unlocks immediately on fragment reveal
    - Strong seed — significant momentum toward the trait, likely to surface through normal activity
    - Weak seed — small nudge to aptitude ceiling, may never visibly manifest

Link strength is never shown to the player. If a trait link exists a small trait tag appears on the fragment card showing the trait name and either "unlocked" or "seeded" — strong and weak seeds are not distinguished in the UI.

---

## Fragment 4 — Reflection

**Inputs:** archetype tag, faction alignment, moral tone of player choices

Generated at 6 star. Takes the character's established archetype as grounding and shapes the reflection toward who they became under the player's influence. Faction alignment and the broad moral tone of player choices — pragmatic or sympathetic Architect, which faction branch was taken — are the primary variables.

Same character, different conclusion depending on the world built around them. Full definition depends on the faction and story systems. See [[Story]] and Loose Threads.

No trait link roll for fragment 4.

---

## Edge Cases

A character can have three fragments and zero trait links. This is not an error — it means the trait link roll failed on fragments 2 and 3, or weak seeds haven't surfaced. Feels natural rather than broken.

A character can have a trait fully unlocked with no fragment link. Traits develop through activity regardless of fragment generation. The fragment system is one input into trait development, not the only one.