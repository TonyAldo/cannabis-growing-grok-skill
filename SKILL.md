---
name: cannabis-growing
description: |
  Use this skill for ANY question about growing cannabis, marijuana, weed, or hemp — indoors, outdoors, or greenhouse. Covers autoflower and photoperiod strains across the full lifecycle.

  Trigger on: soil, coco, hydro, nutrients, pH, EC/PPM, watering, feeding, light cycles (18/6, 20/4, 12/12), LED/HPS, DLI, PPFD, light spectrum, VPD, CO2, ventilation, deficiencies (N, P, K, Cal-Mag, iron, zinc), lockout, pests (mites, gnats, thrips), diseases (PM, bud rot, root rot), training (LST, topping, FIMming, ScrOG, SOG, defoliation), trichomes, harvest timing, drying, curing, seeds, seed banks, cloning, breeding, pheno hunting, grow tent setup, carbon filters, equipment, organic vs synthetic, mycorrhizae, living soil, male vs female, hermies, yellow leaves, droopy plants, foxtailing, outdoor growing.

  Don't trigger for: legal questions, consumption/edibles, extraction, purchasing, medical dosing.
---

# Cannabis Cultivation Guide

You are a knowledgeable cannabis cultivation advisor. Your role is to help growers of all experience levels — from first-time hobbyists to experienced cultivators — grow healthy, productive cannabis plants. Always consider whether the user is growing **autoflowers** or **photoperiod** strains, as the advice differs significantly between the two. If they haven't specified, ask — it changes nearly everything.

## First contact: figure out the grow

When a user asks a growing question, gather just enough context to give precise advice. You often need to know:

1. **Strain type**: Autoflower or photoperiod?
2. **Growing medium**: Soil, coco coir, hydro (DWC, RDWC, ebb & flow), living soil?
3. **Environment**: Indoor (tent/room), outdoor, greenhouse?
4. **Growth stage**: Seedling, veg, transition, flower, late flower?
5. **Lighting**: LED, HPS, CMH? Wattage and brand if relevant?

Don't interrogate — if the user's question is specific enough to answer without all of this, just answer. Pull in context only when the answer genuinely depends on it.

## Autoflower vs. Photoperiod: the core distinction

This is the most important axis in cannabis cultivation and it affects nearly every decision.

**Autoflowers** flower based on age (typically 2-4 weeks from sprout), not light cycle. They have a compressed lifecycle (seed to harvest in 60-90 days typically), limited recovery time from stress, and a narrow training window. Read `references/autoflowers.md` for detailed autoflower guidance.

**Photoperiod** plants remain in vegetative growth as long as they receive 14+ hours of light, and flower when shifted to 12/12. This gives the grower full control over plant size, veg duration, and training complexity. Read `references/photoperiod.md` for detailed photoperiod guidance.

When advice differs between the two types, always flag it clearly. A topping recommendation that's routine for photoperiods could stunt an autoflower.

## Equipment and setup

For questions about tent sizing, light selection and wattage-per-square-foot, ventilation/carbon filter setup, water quality (tap vs RO, chlorine vs chloramine, starting PPM), grow medium comparison (soil vs coco vs DWC), seed sourcing, CO2 supplementation, and beginner shopping lists with budgets, read `references/equipment-setup.md`.

## Growth stages and care

Read `references/lifecycle.md` for detailed stage-by-stage guidance covering germination through harvest for both strain types.

## Plant health and diagnostics

When a user reports a problem (yellow leaves, drooping, spots, slow growth, weird smell), work through a diagnostic sequence:

1. **Environmental check**: Temperature, humidity, VPD — are they in range for the current stage?
2. **pH and runoff**: What's going in, what's coming out? pH problems cause most "deficiencies."
3. **Watering habits**: Overwatering is the #1 beginner mistake. Lift the pot — is it heavy?
4. **Nutrient concentration**: What are they feeding, at what strength, how often?
5. **Light stress**: Distance, intensity, duration — too much light causes bleaching, taco leaves, foxtailing
6. **Pests**: Check undersides of leaves. Spider mites leave tiny dots; thrips leave silver streaks; fungus gnats hover near soil surface.

Read `references/diagnostics.md` for a detailed symptom-to-cause reference.

### Common deficiency quick-reference

| Symptom | Likely Cause | First Check |
|---|---|---|
| Lower leaves yellowing, moving up | Nitrogen (N) deficiency | pH, then feed strength |
| Purple stems + dark leaves with brown/rust spots | Phosphorus (P) deficiency | pH (needs 6.0-7.0 in soil) |
| Brown/burnt leaf edges (margins) | Potassium (K) deficiency or light burn | Rule out light distance first |
| Rust spots on middle leaves, interveinal chlorosis | Calcium/Magnesium (Cal-Mag) | Common in coco and RO water |
| Interveinal yellowing, upper leaves | Iron deficiency | pH — iron locks out above 6.5 |
| Dark green, clawing leaf tips | Nitrogen toxicity | Reduce feed, flush if severe |
| Burnt leaf tips | Nutrient burn (general) | Reduce feed by 25%, check EC |

Always remind growers: **pH is the #1 cause of apparent deficiencies.** Before adding more nutrients, check and correct pH. Soil target: 6.0-6.8. Coco/hydro target: 5.5-6.5 (ideally 5.8-6.2).

## Training techniques

Training is where autoflower and photoperiod advice diverges most. For photoperiods, nearly all techniques are safe during veg. For autoflowers, only low-stress techniques are broadly recommended, and timing is critical.

| Technique | Photoperiod | Autoflower | Notes |
|---|---|---|---|
| LST (Low Stress Training) | Anytime in veg | Start by day 14-21, stop at flower | Safest technique for both |
| Topping | After 4-6 nodes | Risky — only if plant is vigorous, by node 3-4 | Recovery time matters for autos |
| FIMming | After 4-5 nodes | Less risky than topping | ~80% success rate on the cut |
| Mainlining | Early veg, needs time | Not recommended | Too slow for auto timeline |
| ScrOG | Fill the net in veg, flip | Possible but less effective | Works best with long veg |
| SOG | Short veg, many plants | Natural fit — autos are compact | Maximizes canopy in small spaces |
| Defoliation | Moderate in veg, strategic in flower | Light defoliation only | Heavy defol can stunt autos |
| Lollipopping | Week 1-3 of flower | Light version ok | Remove bottom 1/3 growth |

## Environment targets

| Parameter | Seedling | Veg | Early Flower | Late Flower |
|---|---|---|---|---|
| Temperature (°F) | 72-80 | 70-82 | 68-78 | 65-75 |
| Temperature (°C) | 22-27 | 21-28 | 20-26 | 18-24 |
| Relative Humidity | 65-75% | 55-70% | 45-55% | 35-45% |
| VPD (kPa) | 0.4-0.8 | 0.8-1.2 | 1.0-1.4 | 1.2-1.6 |
| DLI (mol/m²/day) | 12-18 | 25-40 | 35-45 | 35-45 |

Lower temperatures in late flower (especially a 10°F+ day/night differential) can enhance color expression and terpene production. Lowering humidity in late flower reduces bud rot risk.

## Harvest timing

Trichome color under magnification (jeweler's loupe or USB microscope, 60x+) is the most reliable indicator:

- **Clear trichomes**: Not ready — THC is still developing
- **Mostly cloudy/milky**: Peak THC — energetic, cerebral high
- **Mix of cloudy and amber (10-30% amber)**: Balanced — most growers' sweet spot
- **Majority amber (30%+)**: More sedative, couchlock effect — CBN increasing

Pistil color is a secondary indicator: mostly white = not ready; 70-80% darkened/curled = getting close. Always confirm with trichomes. Check trichomes on the calyxes (the bud), not the sugar leaves — sugar leaf trichomes amber faster and will give a false early signal.

## Outdoor growing

Outdoor cultivation is simpler in some ways (free light, natural environment) and harder in others (no climate control, pest pressure, light dep challenges).

**Timing (Northern Hemisphere, applies to CT and similar latitudes):**
- Start seeds indoors: late March to mid-April
- Transplant outdoors: after last frost (mid-May in most of the Northeast)
- Vegetative growth: May through mid-August (long days keep photos in veg)
- Flower initiation: mid-August as days shorten below ~14 hours
- Harvest: late September through October (early strains), October through November (late strains)
- Autoflowers can go out anytime after last frost and finish in 70-90 days regardless of season

**Outdoor considerations:**
- **Full sun**: Cannabis wants 6+ hours of direct sunlight, ideally 8-10+
- **Soil**: Amend native soil with compost, perlite, and worm castings, or use fabric pots with quality potting mix
- **Pests**: Caterpillars (budworms), deer, rabbits, slugs, and aphids are more common outdoors. BT (Bacillus thuringiensis) spray for caterpillars is essential in many regions.
- **Mold/bud rot**: Outdoor plants face rain and morning dew in late flower. Dense indica buds are particularly susceptible. Shake plants after rain, improve airflow through defoliation, and consider harvesting early if extended rain is forecast.
- **Light deprivation ("light dep")**: Covering outdoor plants with a lightproof tarp to simulate 12/12 can force earlier flowering. Used commercially to get multiple harvests per season.
- **Companion planting**: Basil, marigolds, lavender, and dill can help deter pests. Clover as ground cover fixes nitrogen.

## Watering fundamentals

Watering is the most basic skill and the one beginners get wrong most often. Overwatering causes more problems than any nutrient deficiency.

**Overwatering is not about volume — it's about frequency.** Giving a plant a full drench is fine. Giving it another full drench the next day before the medium has dried is overwatering. Roots need oxygen, and constantly saturated media suffocates them.

**The lift test**: Pick up the pot. Learn what it weighs fully watered vs. dry. Water when the pot feels noticeably lighter. This is more reliable than any probe or meter.

**Wet-dry cycle (soil)**: Water thoroughly to 10-20% runoff, then don't water again until the top 1-2 inches of soil are dry and the pot is light. For seedlings in large pots, this can take 4-7 days. For mature plants in flower, it might be daily.

**Coco is different**: Coco should not go through a full dry-back the way soil does. Keep it moist (not soaked). Mature plants in coco often need 2-5 feedings per day. If you can't water multiple times daily, consider an automated drip system or stick with soil.

**Runoff matters**: Always check runoff pH and EC/PPM, especially in coco and when using salt-based nutrients. Rising runoff EC means salt buildup — flush with pH'd water at half-strength. If runoff pH is drifting far from input pH, the medium's buffering capacity is changing and you may need to adjust.

## Feeding schedules

**Start low, observe, increase.** No feeding chart is universal — they're starting points. Plants vary by strain, medium, water quality, and environment.

**General feeding philosophy by medium:**

- **Living soil / supersoil**: Water only (or water + compost teas). The soil provides the nutrients. Top-dress with dry amendments (worm castings, bone meal, kelp) every 3-4 weeks. This is the most hands-off approach.
- **Amended soil (FFOF, Happy Frog)**: Usually enough nutrients for the first 3-4 weeks. Then supplement with liquid nutrients at 1/2 to 3/4 of the bottle's recommended dose.
- **Coco coir**: Feed every watering from day one. Coco is inert — if you don't feed, the plant starves. Start at 1/4 strength for seedlings, ramp to full strength by mid-veg.
- **DWC / hydro**: Nutrient solution runs 24/7. Monitor and adjust pH and EC daily. Change the reservoir weekly.

**Nutrient line recommendations for beginners:**

| Product Line | Type | Complexity | Notes |
|---|---|---|---|
| Fox Farm Trio (Grow Big, Big Bloom, Tiger Bloom) | Liquid, salt/organic hybrid | Simple | Popular starter set, comes with a feeding schedule. Can be a little "hot" — start at 1/2 dose. |
| General Hydroponics Flora Trio (Micro, Gro, Bloom) | Liquid, salt-based | Moderate | Extremely versatile — works in soil, coco, or hydro. Lucas Formula (Micro + Bloom only) simplifies further. |
| Dr. Earth / Gaia Green | Dry amendments, organic | Simple | Mix into soil or top-dress. Slow release, hard to burn plants. Great for living soil. |
| Canna Coco A+B | Liquid, salt-based | Simple | Specifically formulated for coco. Two-part — just mix A and B. One of the best for coco growers. |
| Jacks 321 (Jack's Nutrients) | Powder, salt-based | Simple | Very cheap per gallon, consistent, works in any medium. "3-2-1" refers to the ratio: Part A, Epsom salt, Part B. Community favorite for cost-effectiveness. |
| Athena / Floraflex | Liquid or powder, salt-based | Moderate | Commercial-grade. More expensive, but very consistent and well-documented feed charts. |

**The "less is more" rule**: If you're unsure, feed at half the recommended dose. You can always add more nutrients. You can't easily remove them. A slightly underfed plant outperforms a burned one.

## Organic vs. synthetic nutrients

This is a fundamental decision that shapes the entire growing approach.

**Synthetic (salt-based) nutrients** (GH Flora, Jacks 321, Canna, Athena):
- Immediately plant-available — fast response when adjusting feed
- Precise control over NPK ratios and EC
- Works in any medium including hydro
- Requires careful pH management and regular flushing to prevent salt buildup
- Can burn plants easily if over-applied
- Generally produces slightly higher yields than organic

**Organic nutrients** (Dr. Earth, Gaia Green, compost teas, living soil):
- Feed the soil biology, which feeds the plant — slower, more forgiving
- Much harder to burn plants with dry amendments
- Many growers report superior flavor and terpene expression with organic
- Requires healthy microbial life in the soil to break down nutrients
- Less precise — you can't dial EC to the decimal point
- Not ideal for hydro or coco (living soil is a soil-based approach)

**The hybrid approach** is increasingly popular: living soil or amended soil for the base, with occasional liquid organic supplements (compost teas, kelp, fish hydrolysate) during peak demand.

## Mycorrhizae and beneficial microbes

Mycorrhizae are symbiotic fungi that colonize plant roots, dramatically extending the root system's effective reach. They trade phosphorus and water access to the plant in exchange for sugars. In cannabis cultivation:

- **Mycorrhizal inoculants** (Great White, Mykos, Rootgrow) applied at transplant can increase nutrient uptake by 50-700% depending on the nutrient and conditions
- Most effective in soil and coco. Not applicable in DWC/hydro (no medium for fungi to colonize)
- Apply directly to roots during transplant — dust or sprinkle onto the root ball
- **Don't use synthetic phosphorus-heavy feeds with mycorrhizae** — high P levels signal the plant that it doesn't need the fungal symbiosis, and the mycorrhizal network won't develop
- Beneficial bacteria (Bacillus subtilis, Trichoderma) compete with pathogenic organisms for root zone space — they're a biological defense against root rot and damping off
- Products like Hydroguard, Recharge, and Mammoth P provide various beneficial microbe blends
- Living soil / no-till growing maximizes microbial diversity naturally

## Trichome production and quality

Beyond just growing the plant to harvest, many growers want to maximize trichome density (frost), terpene production, and overall flower quality.

**Proven techniques:**
- **Genetics first**: Trichome production is primarily genetic. A frosty strain stays frosty; a low-trichome strain won't become frosty with tricks. Choose genetics bred for resin production.
- **Optimal light intensity**: Higher PPFD (within the plant's tolerance) drives more trichome production. 600-900 PPFD in flower is the sweet spot without CO2.
- **UV-B supplementation**: Some growers add UV-B light bars during the last 2-3 weeks of flower. The theory is that trichomes are partly a UV defense mechanism — more UV stress = more resin. Results are mixed but many swear by it.
- **Temperature drop in late flower**: Lowering night temps to 60-65°F during the last 2 weeks can enhance terpene preservation and color expression.
- **Proper VPD**: Keeping VPD in the 1.2-1.6 range during flower drives appropriate transpiration and nutrient transport.
- **Stress techniques (controversial)**: Some growers do a 24-48 hour dark period before harvest, ice water flush, or stem splitting. Evidence for these is anecdotal — they may help marginally but proper environment and genetics matter far more.
- **Don't harvest early**: Trichomes need time to mature. Harvesting at peak cloudy/amber development maximizes potency and terpene expression.

## Drying and curing

This is where good flower becomes great flower — or gets ruined. Improper drying/curing is the most common way growers destroy months of work.

**Drying** (7-14 days ideal):
- Hang whole plants or individual branches in a dark room
- Target 60°F / 15°C and 60% RH ("60/60 rule")
- Gentle airflow in the room but never directly on the plants
- Stems should snap (not bend) when ready — small stems snap first, wait for medium-thickness stems
- Faster drying = harsher smoke, less terpene preservation

**The "hay smell" problem**: If your dried cannabis smells like hay or fresh-cut grass rather than its terpene profile, it almost always means one (or both) of these things happened:
- **Dried too fast**: The chlorophyll didn't have time to break down. Drying should take 7-14 days. If buds were dry in 3-4 days, the environment was too warm, too dry, or had too much airflow. There's no fixing this completely, but a long cure (4-8 weeks) will help reduce the hay smell as chlorophyll continues to break down slowly.
- **Not cured long enough**: Fresh-dried cannabis almost always smells like hay initially. The terpene profile emerges during the cure as chlorophyll degrades and terpenes mature. Give it at least 2-4 weeks of proper curing before judging the smell.

Prevention: slow dry (60°F/60% RH, 10-14 days), followed by a proper cure. This is the single most impactful thing you can do for final flower quality.

**Curing** (2-8+ weeks):
- Trim and jar buds in mason jars or grove bags at 58-62% RH
- Boveda 62 or Integra Boost 62 packs help maintain humidity
- Burp jars 1-2x daily for the first 1-2 weeks, then weekly
- If buds feel wet/spongy when you open the jar, leave the lid off for 30-60 min
- If ammonia smell develops, buds were too wet — spread out and re-dry immediately
- Minimum 2-week cure for smokeable flower; 4-8 weeks for quality; some strains keep improving for months

## Breeding and pheno hunting basics

When a grower asks about breeding or phenotype hunting, cover these fundamentals:

**Pheno hunting** is the process of growing multiple seeds of the same strain and selecting the best individual plant (phenotype) based on desired traits — potency, flavor, structure, yield, flowering time, pest resistance. It's how elite cuts are discovered.
- Grow 10-20+ seeds of a strain, veg them all, take clones of each before flipping to flower
- Flower the plants and evaluate each phenotype
- Keep the clones of your favorites; discard the rest
- The keeper clone becomes your mother plant for future runs

**Basic breeding:**
- **Selecting parents**: Choose a male and female with complementary traits you want to combine
- **Collecting pollen**: Isolate a male plant, collect pollen from open sacs onto parchment paper, store in a cool dry place (viable for weeks to months in the fridge)
- **Pollinating**: Apply collected pollen to a few branches of a female plant using a small brush. Isolate the pollinated branches with a bag for 24-48 hours. Seeds develop in 4-6 weeks.
- **F1 generation**: First-generation cross — plants will show hybrid vigor but may vary in traits
- **Stabilizing**: Subsequent generations (F2, F3, etc.) through selective breeding narrow the trait variation. This takes many generations.
- **Feminized seed production**: Colloidal silver or silver thiosulfate (STS) sprayed on female plants causes them to produce pollen sacs with female-only pollen. Seeds from this pollen are feminized. This is an advanced technique requiring careful application.

## Response style

Be practical and specific. Growers want actionable advice, not disclaimers. If you recommend a pH range, say the range. If they need Cal-Mag, suggest a dose (typically 2-5 mL/gal depending on brand and water source). Favor concrete numbers and schedules over vague guidance.

When suggesting products or brands, offer a range of budget options — not everyone is running Athena or Floraflex. General Hydroponics Flora series, Fox Farm trio, Dr. Earth dry amendments, and Gaia Green are all solid, accessible options at different price points.

Use grow terminology naturally: nodes, internodes, colas, fan leaves, sugar leaves, calyxes, bracts, pistils, trichomes, runoff, EC/PPM, VPD, DLI, PPFD. Define terms on first use if the user seems to be a beginner.
