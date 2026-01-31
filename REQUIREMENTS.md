# Coffee Personality Quiz - Requirements

## Overview
A shareable quiz that matches users to their coffee personality based on lifestyle preferences.

---

## Personality Types & Coffee Pairings

| Personality | Coffee Match | Vibe |
|-------------|--------------|------|
| Bold Adventurer | Double Espresso | High energy, spontaneous, loves intensity |
| Cozy Classic | Medium Roast Drip | Comfort-seeking, reliable, appreciates simplicity |
| Night Owl | Red Eye | Late-night energy, creative, burns the midnight oil |
| Artisan Snob | Pour-Over, Single Origin | Refined taste, detail-oriented, quality over quantity |

---

## Results Display
- Show **all personality percentages** (not just the top match)
- Primary result highlighted with coffee pairing
- Secondary percentages shown below

---

## Visual Design: Warm & Cozy (Style 4)

**Colors:**
- Background: `#fef7ed` → `#fef3e2` gradient
- Card: `#fffbf5`
- Accent: `#d4a574`, `#c9956c`
- Text: `#5d4037` (headings), `#6d4c41` (body)
- Meta text: `#b8860b`

**Typography:**
- Headings: Lora (serif), 600 weight
- Body: Source Sans Pro, 400/600 weight

**Layout:**
- Card: 24px border-radius, soft shadow
- Options: 16px border-radius, 2px border
- Padding: Generous whitespace

**Interactions:**
- Hover: Border color change, subtle lift (-1px translateY)
- Transitions: 0.2s ease

---

## Features
- [x] Emoji icons next to answer options
- [ ] Coffee images on results (skip for now)
- [x] Progress indicator
- [x] Shareable results

---

## Quiz Questions

### Q1: What's your ideal weekend morning?
- ☀️ Sleeping in until noon → Night Owl
- 🥾 Early hike or workout → Bold Adventurer
- 🛋️ Cozy breakfast at home → Cozy Classic
- 🥐 Trying a new brunch spot → Artisan Snob

### Q2: Pick your perfect evening:
- 🎉 Out with friends until late → Bold Adventurer
- 📺 Movie marathon on the couch → Cozy Classic
- 💻 Deep dive into a passion project → Night Owl
- 🍷 Intimate dinner with great conversation → Artisan Snob

### Q3: Your phone battery dies. How do you feel?
- 😤 Frustrated - I need to stay connected → Night Owl
- 😌 Relieved - forced digital detox → Cozy Classic
- 🤷 Whatever - I'll figure it out → Bold Adventurer
- 📱 I always have a backup charger → Artisan Snob

### Q4: What's your travel style?
- 🎒 Spontaneous backpacking → Bold Adventurer
- 🏡 Cozy cabin getaway → Cozy Classic
- 🌃 City exploration, day and night → Night Owl
- ✈️ Curated boutique experiences → Artisan Snob

### Q5: How do you approach a new recipe?
- 🔥 Wing it and add extra spice → Bold Adventurer
- 📖 Follow Grandma's classic recipe → Cozy Classic
- 🌙 Cooking at midnight hits different → Night Owl
- ⚖️ Precise measurements, quality ingredients → Artisan Snob

### Q6: Pick a superpower:
- ⚡ Unlimited energy → Bold Adventurer
- 🛡️ Create a comfort bubble anywhere → Cozy Classic
- 🦉 Perfect night vision → Night Owl
- 🎯 Instantly master any skill → Artisan Snob

---

## Scoring Logic
- Each answer adds +1 to its mapped personality
- Final result = personality with highest score
- Ties broken by question order (earlier questions weighted slightly higher)
- All percentages calculated and displayed

---

*Requirements locked: January 31, 2026*
