# PROJECT
AI/ML


## Few Project Directions Under Consideration

###1. Predicting NYC Subway Station Crowding Using Ridership, Weather, and Events

Core research question:

Can we predict how crowded an NYC subway station will be at a given time using historical passenger entry/exit data, weather conditions, train frequency, and nearby events?

**Data sources:**
1. MTA ridership data – how many people enter and exit each station.

2. MTA train service data – how frequently trains arrive and whether there are delays or disruptions.

3. Weather data – rain, snow, temperature, humidity, etc.

4. Events data – concerts, sports games, festivals, holidays, etc

5. Station information – location, subway lines, borough, and station characteristics.


### 2. BeanThere — Personal Coffee Recommender for NYC Specialty Beans
**Core question:** *Can a system learn your flavor preferences from a few ratings and recommend beans available today at NYC roasters?*

**Data sources:**
- Coffee Quality Institute (CQI) cupping database — 1,300+ beans with flavor notes, scores, origin, process — Kaggle `volpatto/coffee-quality-database-from-cqi`
- Coffee shop sales transactions — Kaggle `yiwaichang/coffee-shop-sales`
- Custom scraped inventory from 10–15 NYC roasters (Devoción, Sey, Joe, Irving Farm, etc.)

### 3. NYC Tap Water Quality Decoder

**Core question:** *NYC water is "world-class" at the reservoir — but what's actually coming out of my tap given my building's pipes, age, and today's treatment conditions?*

**Data sources:**
- DEP Lead & Copper Rule sampling (building-level lead/copper results) — NYC Open Data 9w9y-8y5q
- DEP Drinking Water Quality Reports (zone-level TTHM, HAA5, turbidity, pH, blend ratios) — NYC DEP Reports
- 311 Water Quality Complaints (brown water, taste, odor, illness clusters) — NYC Open Data erm2-nwe9
- PLUTO + Building Footprints (year built, renovation permits, pipe material proxy, height) — NYC Planning
- DEP Harbor Survey (source water TOC, algae, turbidity driving treatment changes) — NYC Open Data 5u3k-3v9q
