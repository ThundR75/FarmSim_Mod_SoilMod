Farming Simulator modification - SoilMod
========================================
To read more about this mod, find it on http://fs-uk.com - http://fs-uk.com/mods/search/soil%20management


Changes since SoilMod for FS2013
--------------------------------

A quick rundown of the SoilMod-FS15 changes compared to SoilMod-FS2013:

- Two foliage-layers; one for 'visibles' and one for 'non-visible' (both same width/height as fruit_density.grle)
- Soil pH increased to use 4-bits, so lower level-change between steps
- Fertilizer concept changed to Nutritions N+PK
- Nutritions N+PK (4- & 3-bits) is affected by fertilizers and crop growth
- 3 fertilizer spray-types that increase; NPK, PK or N. Manure/slurry also adds N+PK.
- Soil moisture added (3 bits), which weather will affect (high temperature or rain)
- 3 extra herbicide spray-types that adds germination prevention (lasts 4 growth-cycles)
- Crop yield during harvest, will be affected by pH level, nutrition N+PK levels, soil moisture and weeds
- Two distinct types of weed, and their patches not so square



Current effects (2.0.4-BETA)
----------------------------

*Please note that these are NOT final, and still needs tweaking!*

- Crops; at growth-stages 3-8, when cultivated/plowed adds +3 N.
- Swath/windrows; when cultivated/plowed adds +1 N.
- Manure; when cultivated adds +6 N, when plowed adds +10 N.
- Slurry; at growth-cycle adds +3 N.
- Lime; at growth-cycle increase soil pH by '3 internal-levels'.
- Fertilizer-A (NPK); at growth-cycle adds +3 N and +1 PK.
- Fertilizer-B (PK); at growth-cycle adds +3 PK.
- Fertilizer-C (N); at growth-cycle adds +5 N.
- Herbicide-A/B/C; at growth-cycle makes weeds withered and decrease soil pH by '1 internal-level'.
- Herbicide-AA/BB/CC; does the same as herbicide-A/B/C, but also adds 3 extra days of weed-germination prevention.
- Water; at growth-cycle increase soil moisture by '1 internal-level'. 
- Spray moisture (from liquid fertilizer/herbicide/slurry); at growth-cycle increase soil moisture by '1 internal-level'.

- Weather:
 - Weather temperature above 22 degrees daytime; at noon 12:00 o'clock, decrease soil moisture by '1 internal-level'. 
 - Weather when raining; at every whole hour, increase soil moisture by '1 internal-level'.

- Equipment:
 - Plowing; at growth-cycle decrease soil moisture by '1 internal-level' (except if water was sprayed after plowing.)

- Growth of crops, during growth-cycle:
 - When at stages 1-7; consumes 1 N.
 - When at stages 3 & 5; consumes 1 PK.
 - When at stages 2, 3 & 5; decrease soil moisture by '1 internal-level'.
 - When at stage 5; decrease soil pH by '1 internal-level'.
 - Fully grown weeds become withered if there is zero N in soil.
 - Weeds (if not withered) consume 1 N and soil moisture.
 - Swath/windrows/manure; decrease amount by 1.
