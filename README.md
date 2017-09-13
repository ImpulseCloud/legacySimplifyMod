# legacySimplifyMod
Simplifies Orteil's NeverEnding Legacy game to have only functionally important things

The overall goal is to reduce some of the mostly-unused extra (distracting) complexity and make the game have an easier-to-understand, slower, more distinct, and more linear stage-progression (baskets should always come before Granaries, etc).

First, going to remove the Muddy Water / Spoiled Food mechanic and just have water/food or no water/food. (maybe re-add much later)
Second, going to make the subFood have more obvious Tiers and show the actual attribute impacts in the tooltips (raw meat: -.03 health)

Going to re-tool the food-gathering percentages to make the tribe much more food-gathering dependent early on, and so allow the technology gains (baskets, pots) to have very obviously-impactful effects that allows major changes to tribe labor-distribution ratios.

Forum for DashNet (Cookie Clicker, Legacy, and Idle Game Maker): http://forum.dashnet.org/
- SubReddit0: https://www.reddit.com/r/LegacyTheOrteilGame/
- SubReddit1: https://www.reddit.com/r/NeverEndingLegacy/
- [This mod's Announcement thread: "Starting work on SimplifyMod"](https://www.reddit.com/r/LegacyTheOrteilGame/comments/6s44t6/starting_work_on_simplifymod_simplifying_the/)

**Original Files on http://orteil.dashnet.org/legacy/**
- [Main.js - Game Engine Code](http://orteil.dashnet.org/legacy/main.js)
- [Data.js - Default game datafile](http://orteil.dashnet.org/legacy/data.js)  ((put "view-source:" in front of the .js URL to get line numbers))

Guiding References:
- "Foragers, Farmers, and Fossil Fuels: How Humans Evolved" https://www.amazon.com/Foragers-Farmers-Fossil-Fuels-Values/dp/0691160392
- (discussion: http://www.bradford-delong.com/2017/02/reading-ian-morris-2015-foragers-farmers-and-fossil-fuels-how-human-values-evolve.html)
- "Ian Morris: How Human Values Evolve" https://www.youtube.com/watch?v=Yy2P5XkEPIs
- "Stories from the stone age First Farmers pt.1" https://www.youtube.com/watch?v=nTgIPVi1yPs
- "Stories from the stone age First Farmers pt.2" https://www.youtube.com/watch?v=Pg3LUvo1t_o
- "1177 BC: The Year Civilization Collapsed (Eric Cline, PhD)" https://www.youtube.com/watch?v=bRcu-ysocX4&t=2399s
- "A Life History of Human Foraging in 39 Societies" https://www.youtube.com/watch?v=lexk9Lf2SLI


Design Specifications: (Simplifying resources/mechanics, Tuning Ratio/Rates, Macromolecules, Leaders)
1) Simplifying Resources and Mechanics
2) Tuning Rates and Ratios
3) Macromolecules / energy
  3.1) Track Sugar, Carbohydrates, Protein. Fruit, Bread, Meat. Mind-work, slow-work, strength-work.
  3.2) Simulate KCals per person. Basal metabolism much lower, forager slightly-higher, digger/miner takes a lot.
4) Population-attribute bell-curve infographs
5) Tiered layers, explicitly indicated
 5.1) Show how agriculture (Cultivated-gathering) is Level-Up of Found-Gathering. Levels of ease of energy-gain.
  5.1.1) Agriculture effects an increase in single-tile-availability of renewable-resource? (depends on found-land)
  5.1.2) Tilling allows for increasing available 'farm'-space land-use in single-tile.
 5.2) Show how Tool-Use is Leveled-Up. 1.Hands -> 2.Found -> 3.Hand-Crafted -> 4.Tool-crafted -> 5.Forged
