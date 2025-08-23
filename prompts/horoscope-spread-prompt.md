# Horoscope Spread — Brotherhood of Light Tarot

## Objective
Guide AI to interpret a structured symbolic system (Brotherhood of Light Tarot) using the **Horoscope Spread**. Focus is on reasoning, pattern recognition, and narrative output — not divination.

This prompt demonstrates how to encode a symbolic system (Brotherhood of Light Tarot) into an LLM, ensuring it doesn’t deviate into other traditions. The engineering challenge was enforcing strict correspondences, court card naming, and **the complex 12-house horoscope spread structure**, including angular, cadent, and succedent houses, plus trinity groupings.

---

## Skills Demonstrated

**Emphasize AI reasoning over tarot**  
This project uses the Brotherhood of Light Tarot purely as a formal symbolic system, allowing AI to reason through numbers, elements, archetypes, and house positions. It is a framework for pattern recognition, analogy, and narrative construction — not fortune-telling.

**(Relational Indexing) Highlight Minor Arcana numerical correspondence**  
Minor Arcana numbers correspond to Major Arcana by number, filtered through suit elements. Integrating these with the house positions and trinity groupings creates a **multi-layered reasoning challenge** for AI.

**Showcase prompt precision**  
Maintains strict adherence to symbolic rules, including spread positions, card correspondences, reversals, and house/trinity mappings — demonstrating prompt engineering discipline.

---

## Prompt

### Question
*"What surrounds my life during the next 3 months?"*

Assume the querent seeks clarity, reflection, and guidance.

---

### System Rules (Do Not Deviate)
- Use only the Brotherhood of Light Tarot system (Church of Light lessons CS06 & CS07).  
- Do not use Golden Dawn, Rider–Waite, Thoth, or any other tarot system correspondences or card titles.  
- Use official Brotherhood of Light titles: e.g., The Alchemist, The Two Paths, The Spiritualist, The Star, etc.  
- Major Arcana meanings are applied exactly as described in CS06 & CS07.  
- For Minor Arcana, interpret strictly using:  
  - Its numerical correspondence to the Major Arcana of the same number.  
  - The element of its suit (Coins = Air, Scepters = Fire, Cups = Water, Swords = Earth).  
  - Upright/reversed nuances only as described in CS06 & CS07.  
- Do not add extra narrative from other tarot systems.  
- For Court Cards, use only the Brotherhood of Light zodiac/element correspondences and personality traits.  

---

### Spread Instructions
- Draw **12 cards randomly** from the full 78-card Brotherhood of Light deck for the **Horoscope Spread**.  
- Do not favor Major Arcana; Minor Arcana and Court Cards must appear naturally according to chance.  
- Simulate shuffling the entire 78-card deck using the traditional three-pile method (cut from right to left, some cards reversed).  
- Always draw from the full deck, so Major and Minor Arcana can appear in any house position.  
- Note: when a Major Arcana card appears in any house, it highlights that area of life as particularly significant.

#### Layout order (placement)
- **Angular houses:** 1 → 10 → 7 → 4  
- **Cadent houses:** 12 → 9 → 6 → 3  
- **Succedent houses:** 11 → 8 → 5 → 2  

#### Reading order (interpretation)
- **Trinity of Life → Houses 1, 5, 9**  
- **Trinity of Wealth → Houses 2, 6, 10**  
- **Trinity of Associations → Houses 3, 7, 11**  
- **Trinity of Psychism → Houses 4, 8, 12**

Interpret each card in context of its house, using only Brotherhood of Light principles.

---

### Card Interpretation Instructions
- Use official Brotherhood of Light card titles (e.g., The Alchemist, The Two Paths, The Magus, etc).  
- Include astrological correspondences lightly and professionally.  
- Note if the card is upright or reversed, and explain the meaning in context.  
- Interpret based on symbols, numbers, imagery, and spread position, blending analytical reasoning with story-driven output.  
- Reversed cards indicate slower energy or delays, not a change in meaning.  

---

### Minor Arcana Interpretation
- Each Minor Arcana card corresponds numerically to the Major Arcanum of the same number, expressed through its suit’s element:  

| Suit | Element / Season | Key Words |
|------|-----------------|-----------|
| Coins (Pentacles) | Air / Spring | Money, Work, Ideas |
| Scepters (Wands)  | Fire / Summer | Ambition, Career, Action |
| Cups | Water / Fall | Emotions, Relationships |
| Swords | Earth / Winter | Struggle, Protection, Decision-making |

Interpret the card using the number’s Major Arcana meaning filtered through the suit, then apply upright/reversed nuances.

---

### Major Arcana Reference

| Arcanum | Name (Other) | Ruling | Key Words |
|---------|--------------|--------|-----------|
| I | The Magus | Mercury | Will, Dexterity, Mental & Physical Skill |
| II | Veiled Isis | Virgo | Science, Analysis, Labor |
| III | Isis Unveiled | Libra | Marriage, Action, Balance |
| IV | The Sovereign | Scorpio | Manifestation, Realization, Power |
| V | The Hierophant | Jupiter | Religion, Law, Abundance |
| VI | The Two Paths | Venus | Temptation, Choice, Dilemma |
| VII | The Conqueror | Sagittarius | Victory, Action, Advancement |
| VIII | The Balance | Capricorn | Balance, Justice, Equilibrium |
| IX | The Sage | Aquarius | Wisdom, Prudence, Guidance |
| X | The Wheel | Uranus | Change of Fortune, Cycles |
| XI | The Enchantress | Neptune | Force, Spiritual Power, Fortitude |
| XII | The Martyr | Pisces | Sacrifice, Delay, Endings |
| XIII | The Reaper | Aries | Transformation, Letting Go |
| XIV | The Alchemist | Taurus | Regeneration, Temperance, Healing |
| XV | The Black Magician | Saturn | Selfishness, Discord, Temptation |
| XVI | The Lightening | Mars | Catastrophe, Urgency, Consequences |
| XVII | The Star | Gemini | Truth, Hope, Faith |
| XVIII | The Moon | Cancer | Deception, Secrets, Shadow |
| XIX | The Sun | Leo | Happiness, Joy, Growth |
| XX | The Sarcophagus | Moon | Awakening, Gradual Change |
| XXI | The Adept | Sun | Success, Attainment, Skill |
| XXII | The Materialist / Fool | Pluto | Failure, Folly, Lessons |

---

### Court Cards Reference

| Type | Zodiac / Element | Key Traits |
|------|-----------------|-----------|
| King  | Aries / Fire (Scepters), Taurus / Earth (Swords), Gemini / Air (Coins), Cancer / Water (Cups) | Leaders, pioneers, assertive, action-oriented |
| Queen | Leo / Fire, Virgo / Earth, Libra / Air, Scorpio / Water | Reaction, focused on others, nurturing, social |
| Youth | Sagittarius / Fire, Capricorn / Earth, Aquarius / Air, Pisces / Water | Mutable, adaptable, influenced by environment |

---

### Horsemen Reference

| Element | Key Meaning Upright | Key Meaning Reversed |
|---------|------------------|--------------------|
| Coins / Air | Thoughts on prosperity | Thoughts on lack, despair |
| Scepters / Fire | Business / authority | Half-baked ideas, rethink |
| Cups / Water | Love / affection | Deception, untrue love |
| Swords / Earth | Protection / defense | Dangerous thoughts, self-destruction |

---

### Summary Guidelines
- Provide a clear conclusion: deeper message, possible outcomes, helpful approach.  
- Tone: professional yet engaging — emphasizes narrative reasoning and structured analysis.  
- Provide professional, story-driven reasoning strictly within Brotherhood of Light teachings.  
- Summary and guidance must be consistent with CS06 & CS07 only.  
- Do not import any interpretations, imagery, or meanings from other tarot systems.  

---

### Professional Commentary
This prompt demonstrates:  
- **Structured instruction-following:** precise steps for simulating shuffle, layout, and interpretation of a 12-card Horoscope Spread.  
- **Contextual reasoning:** AI integrates symbolic, numerical, and philosophical references across houses and trinity groupings.  
- **Pattern recognition:** AI identifies connections across symbols, positions, trinity groupings, and narrative.  
- **Story-driven output:** translates abstract symbols into coherent, human-relatable explanations.  
- **Portfolio relevance:** showcases ability to design complex, multi-layered AI prompts — highly relevant for AI education, prompt engineering, and content refinement roles.
