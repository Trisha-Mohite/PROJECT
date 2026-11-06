# PROJECT
AI/ML


## Two Project Directions Under Consideration

### 1. Subway Crowd Truth — Auditing & Improving Google Maps Crowding Predictions for NYC Subway
**Core question:** *How accurate are Google Maps' "Popular Times" crowding predictions for NYC subway stations, and can we build a better predictor using MTA turnstile ground truth?*

**Data sources:**
- MTA turnstile entries/exits (4-hr intervals, 469 stations, 2017–present) — Kaggle `eddeng/nyc-subway-traffic-data-20172021`, `princehobby/metropolitan-transportation-authority-mta-datasets`
- NOAA weather (hourly, per station area)
- NYC events calendar (Yankees/Mets games, concerts, holidays)
- Google Popular Times (scraped for audit; no public API)


### 2. BeanThere — Personal Coffee Recommender for NYC Specialty Beans
**Core question:** *Can a system learn your flavor preferences from a few ratings and recommend beans available today at NYC roasters?*

**Data sources:**
- Coffee Quality Institute (CQI) cupping database — 1,300+ beans with flavor notes, scores, origin, process — Kaggle `volpatto/coffee-quality-database-from-cqi`
- Coffee shop sales transactions — Kaggle `yiwaichang/coffee-shop-sales`
- Custom scraped inventory from 10–15 NYC roasters (Devoción, Sey, Joe, Irving Farm, etc.)

###NYC Tap Water Quality Decoder

**Core question:** *NYC water is "world-class" at the reservoir — but what's actually coming out of my tap given my building's pipes, age, and today's treatment conditions?*

**Data sources:**
- DEP Lead & Copper Rule sampling (building-level lead/copper results) — NYC Open Data 9w9y-8y5q
- DEP Drinking Water Quality Reports (zone-level TTHM, HAA5, turbidity, pH, blend ratios) — NYC DEP Reports
- 311 Water Quality Complaints (brown water, taste, odor, illness clusters) — NYC Open Data erm2-nwe9
- PLUTO + Building Footprints (year built, renovation permits, pipe material proxy, height) — NYC Planning
- DEP Harbor Survey (source water TOC, algae, turbidity driving treatment changes) — NYC Open Data 5u3k-3v9q
