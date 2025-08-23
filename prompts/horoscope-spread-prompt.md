# Horoscope Spread — Brotherhood of Light Tarot

## Objective
Guide an LLM to interpret a **structured symbolic system** (Brotherhood of Light Tarot) using a **12-house Horoscope Spread**. The focus is on **reasoning, pattern recognition, and narrative coherence** — not divination.

This prompt demonstrates how to encode a symbolic framework and keep the model **strictly within one system**. The engineering challenge expands beyond compact spreads by enforcing **house semantics**, **placement vs. reading order**, **cross-house synthesis (trinities)**, and **relational indexing** across 12 positions.

---

## Why This Prompt Is Technically Challenging
- **Scale & Memory:** 12 interdependent positions stress long-context consistency.
- **Dual Orders:** Distinguishes **layout order (placement)** from **reading order (trinities)** — easy for models to confuse.
- **Relational Indexing:** Minor numbers must map to the **Major of the same number**, then be **filtered by suit element**.
- **Leak Prevention:** Strictly locks to Brotherhood of Light titles, correspondences, and semantics.
- **Local vs. Global Coherence:** Each house has a local meaning; trinities and repeating motifs must form a global narrative.
- **Deterministic Procedure Simulation:** Shuffling, reversals, and house assignment must be executed without bias.

---

## Skills Demonstrated
- **Emphasize AI reasoning over tarot:** Uses the Brotherhood of Light purely as a **formal symbolic system** (numbers, elements, archetypes) for pattern recognition, analogy, and narrative construction — not fortune-telling.  
- **(Relational Indexing) Minor ↔ Major mapping:** **Minor Arcana numbers correspond to the Major Arcana of the same number**, filtered through suit elements.  
- **Prompt precision:** Enforces strict card titles, correspondences, reversals behavior, and house semantics.  
- **Cross-structure synthesis:** Interprets **trinities** (1-5-9, 2-6-10, 3-7-11, 4-8-12) for higher-order themes.  

---

## Prompt

### Question
> “What surrounds my life during the next 3 months?”  
> *(Replace with your question as needed.)*

Assume the querent seeks **clarity, reflection, and guidance**.

---

## System Rules (Do Not Deviate)
- Use only the **Brotherhood of Light Tarot** system (Church of Light lessons **CS06 & CS07**).
- **Do not** use Golden Dawn, Rider–Waite, Thoth, or any other tarot system correspondences or card titles.
- Use **official Brotherhood of Light** titles: e.g., *The Alchemist, The Two Paths, The Spiritualist, The Star,* etc.
- Apply **Major Arcana** meanings **exactly** as in CS06 & CS07.
- Interpret **Minor Arcana** strictly via:
  - **Numerical correspondence** to the **Major of the same number**, then  
  - **Suit element** filter.  
- Court Cards: follow **Brotherhood of Light** zodiac/element correspondences and personality traits **only**.

---

## Spread Instructions

### Layout Order (Placement)
Draw **12 cards** from the full 78-card deck. Simulate shuffling using the traditional **three-pile** method, with **reversals** appearing naturally.

Place cards in houses in this order:
- **Angular houses:** 1 → 10 → 7 → 4  
- **Cadent houses:** 12 → 9 → 6 → 3  
- **Succedent houses:** 11 → 8 → 5 → 2

> **Note:** When a **Major** appears in any house, that life area is **especially significant**.

### Reading Order (Interpretation via Trinities)
Interpret in this sequence:
- **Trinity of Life** → Houses **1, 5, 9**
- **Trinity of Wealth** → Houses **2, 6, 10**
- **Trinity of Associations** → Houses **3, 7, 11**
- **Trinity of Psychism** → Houses **4, 8, 12**

---

## Card Interpretation Instructions
- Use **official Brotherhood of Light** card titles.
- Include **astrological correspondences** lightly and professionally.
- Note **upright/reversed** and explain in context of the **house**.
- Interpret using **symbols, numbers, imagery,** and **position**; blend analytical reasoning with a **coherent narrative**.
- **Reversed** = **slowed/delayed** expression (not an opposite meaning).
- **Minor Arcana rule:**  
  1) Map the **number** to the **Major of the same number**,  
  2) Filter by **suit element**,  
  3) Apply **upright/reversed** nuances.

---

## Minor Arcana Interpretation (Elements)
- **Coins → Air** → ideas, work, money  
- **Scepters → Fire** → career, ambition, action  
- **Cups → Water** → emotions, relationships  
- **Swords → Earth** → struggle, protection, decision-making

---

## Major Arcana Reference

| Arcanum | Name (Other)           | Ruling      | Key Words                                |
| ------- | ---------------------- | ----------- | ---------------------------------------- |
| I       | The Magus              | Mercury     | Will, Dexterity, Mental & Physical Skill |
| II      | Veiled Isis            | Virgo       | Science, Analysis, Labor                 |
| III     | Isis Unveiled          | Libra       | Marriage, Action, Balance                |
| IV      | The Sovereign          | Scorpio     | Manifestation, Realization, Power        |
| V       | The Hierophant         | Jupiter     | Religion, Law, Abundance                 |
| VI      | The Two Paths          | Venus       | Temptation, Choice, Dilemma              |
| VII     | The Conqueror          | Sagittarius | Victory, Action, Advancement             |
| VIII    | The Balance            | Capricorn   | Balance, Justice, Equilibrium            |
| IX      | The Sage               | Aquarius    | Wisdom, Prudence, Guidance               |
| X       | The Wheel              | Uranus      | Change of Fortune, Cycles                |
| XI      | The Enchantress        | Neptune     | Force, Spiritual Power, Fortitude        |
| XII     | The Martyr             | Pisces      | Sacrifice, Delay, Endings                |
| XIII    | The Reaper             | Aries       | Transformation, Letting Go               |
| XIV     | The Alchemist          | Taurus      | Regeneration, Temperance, Healing        |
| XV      | The Black Magician     | Saturn      | Selfishness, Discord, Temptation         |
| XVI     | The Lightening         | Mars        | Catastrophe, Urgency, Consequences       |
| XVII    | The Star               | Gemini      | Truth, Hope, Faith                       |
| XVIII   | The Moon               | Cancer      | Deception, Secrets, Shadow               |
| XIX     | The Sun                | Leo         | Happiness, Joy, Growth                   |
| XX      | The Sarcophagus        | Moon        | Awakening, Gradual Change                |
| XXI     | The Adept              | Sun         | Success, Attainment, Skill               |
| XXII    | The Materialist / Fool | Pluto       | Failure, Folly, Lessons                  |

---

## Minor Arcana Reference (Suits)

| Suit              | Element / Season | Key Words                      |
| ----------------- | ---------------- | ------------------------------ |
| Coins (Pentacles) | Air / Spring     | Money, Work, Ideas             |
| Scepters (Wands)  | Fire / Summer    | Ambition, Career, Action       |
| Cups              | Water / Fall     | Emotions, Relationships        |
| Swords            | Earth / Winter   | Struggle, Hardship, Protection |

---

## Court Cards Reference

| Type  | Zodiac / Element                                                                              | Key Traits                                     |
| ----- | --------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| King  | Aries / Fire (Scepters), Taurus / Earth (Swords), Gemini / Air (Coins), Cancer / Water (Cups) | Leaders, pioneers, assertive, action-oriented  |
| Queen | Leo / Fire, Virgo / Earth, Libra / Air, Scorpio / Water                                       | Reaction, focused on others, nurturing, social |
| Youth | Sagittarius / Fire, Capricorn / Earth, Aquarius / Air, Pisces / Water                         | Mutable, adaptable, influenced by environment  |

---

## Horsemen Reference

| Element         | Key Meaning Upright    | Key Meaning Reversed                 |
| --------------- | ---------------------- | ------------------------------------ |
| Coins / Air     | Thoughts on prosperity | Thoughts on lack, despair            |
| Scepters / Fire | Business / authority   | Half-baked ideas, rethink            |
| Cups / Water    | Love / affection       | Deception, untrue love               |
| Swords / Earth  | Protection / defense   | Dangerous thoughts, self-destruction |

---

## Recording the Draw (Template)
Use this table to capture the draw **exactly** as placed by layout order:

| House | Domain (short)    | Card Drawn (Title) | Upright/Reversed | Notes (Maj/Minor mapping, suit filter) |
|------:|-------------------|--------------------|------------------|----------------------------------------|
| 1     | Identity          |                    |                  |                                        |
| 10    | Career/Public     |                    |                  |                                        |
| 7     | Partnerships      |                    |                  |                                        |
| 4     | Home/Foundation   |                    |                  |                                        |
| 12    | Inner/Unseen      |                    |                  |                                        |
| 9     | Beliefs/Long View |                    |                  |                                        |
| 6     | Health/Systems    |                    |                  |                                        |
| 3     | Learning/Comms    |                    |                  |                                        |
| 11    | Community/Allies  |                    |                  |                                        |
| 8     | Shared Resources  |                    |                  |                                        |
| 5     | Creativity/Heart  |                    |                  |                                        |
| 2     | Resources         |                    |                  |                                        |

---

## Interpretation (Trinities) – Template

### Trinity of Life → Houses 1, 5, 9
- **House 1:** *(card, orientation)* — brief interpretation.  
- **House 5:** *(card, orientation)* — brief interpretation.  
- **House 9:** *(card, orientation)* — brief interpretation.  
**Synthesis:** How identity, creative core, and worldview reinforce/challenge each other.

### Trinity of Wealth → Houses 2, 6, 10
- **House 2:** …  
- **House 6:** …  
- **House 10:** …  
**Synthesis:** Resources, operations, and public role.

### Trinity of Associations → Houses 3, 7, 11
- **House 3:** …  
- **House 7:** …  
- **House 11:** …  
**Synthesis:** Communication patterns, partnerships, and networks.

### Trinity of Psychism → Houses 4, 8, 12
- **House 4:** …  
- **House 8:** …  
- **House 12:** …  
**Synthesis:** Foundations, transformation, and inner life.

---

## Summary Guidelines
- Provide a **clear conclusion**: deeper message, likely trajectories, and **actionable approach**.  
- **Tone:** professional yet engaging; emphasize **structured analysis + narrative reasoning**.  
- Remain **strictly within Brotherhood of Light** teachings (**CS06 & CS07**).  
- **Do not** import imagery/meanings from other systems.

---

## Professional Commentary
This prompt demonstrates:
- **Structured instruction-following:** precise shuffle simulation, house placement, and interpretation order.  
- **Contextual reasoning:** integrates numbers, elements, archetypes, and house roles.  
- **Pattern recognition:** identifies cross-house motifs and synthesizes within **trinities**.  
- **Story-driven output:** translates abstract symbols into a coherent, user-relevant narrative.  
- **Portfolio relevance:** showcases **multi-layered, leak-resistant prompt engineering** at scale.

---

## Example Output (Simulated)
> **Note:** Replace with your actual run for the portfolio.

**Trinity of Life (1, 5, 9)**  
- **House 1 — The Magus (upright, Mercury):** Personal will and skill are foregrounded; initiative is decisive.  
- **House 5 — Five of Scepters (rev):** (Maps to **V The Hierophant**; Fire filter) Creative drive meets process constraints; refine structure before launch.  
- **House 9 — The Star (upright, Gemini):** Emerging clarity in long-range vision; truth-seeking aligns beliefs with practice.  
**Synthesis:** Identity powered by skill, creativity disciplined by method, worldview clarified by inquiry.

**Trinity of Wealth (2, 6, 10)**  
- **House 2 — Two of Coins (upright):** (Maps to **II Veiled Isis**; Air filter) Analytical budgeting; optimize inputs and workflows.  
- **House 6 — The Balance (upright, Capricorn):** Fair systems and routines stabilize health and output.  
- **House 10 — The Lightening (rev, Mars):** Structural change in public role unfolds slowly; controlled renovation over rupture.  
**Synthesis:** Careful analysis + just processes buffer a managed career transition.

**Trinity of Associations (3, 7, 11)**  
- **House 3 — Youth of Coins (upright, Aquarius/Air):** Learning mindset; information-rich exchanges.  
- **House 7 — The Sun (upright, Leo):** Partnerships are warm, visible, mutually empowering.  
- **House 11 — Ten of Cups (upright):** (Maps to **X The Wheel**; Water filter) Community support cycles in; emotional momentum grows.  
**Synthesis:** Bright alliances + supportive networks amplify communication efforts.

**Trinity of Psychism (4, 8, 12)**  
- **House 4 — The Sage (upright, Aquarius):** Home base shaped by prudence and wisdom.  
- **House 8 — Eight of Swords (rev):** (Maps to **VIII The Balance**; Earth filter) Gradual release from rigid constraints; grounded re-equilibration.  
- **House 12 — The Alchemist (upright, Taurus):** Quiet regeneration; inner healing strengthens outer resolve.  
**Synthesis:** Deep stabilization enables sustainable transformation.

**Conclusion:** A quarter marked by **skilled initiative**, **process discipline**, and **supportive alliances**, while **career structures** are carefully refactored rather than abruptly replaced.

---

## Optional Visual Mapping (Anchor Orientation)
- **East / Ascendant** → **House 1** (left)  
- **West / Descendant** → **House 7** (right)  
- **MC / Midheaven** → **House 10** (top)  
- **IC / Nadir** → **House 4** (bottom)  
Proceed **counterclockwise** around the wheel: 1 → 2 → 3 → 4 → … → 12 → back to 1.

*(Use the Recording table above to keep the diagram and text perfectly in sync.)*
