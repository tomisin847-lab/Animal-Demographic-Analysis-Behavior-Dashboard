# Animal-Demographic-Analysis & Behavior Analysis (Excel)


## Project Overview
This project transforms a highly inconsistent, raw dataset into a professional, interactive dashboard analyzing animal demographics across Central and Eastern Europe. The analysis focuses on three pillars: data integrity, physical benchmarking, and seasonal visibility trends.

The goal is to provide actionable insights into wildlife activity patterns and physical characteristics that can be used for environmental monitoring or demographic research.

## Research Objectives & Key Questions
- Which animal species is most frequently observed in the studied regions?

- How does population visibility fluctuate as the season transitions into summer?

-What are the typical physical benchmarks (weight and length) for each species?

-Which geographic regions serve as the primary hotspots for wildlife sightings?

---

## Dataset
The dataset contains animal observation records including:

- Animal Type: Species name

- Country: Geographic location

- Weight (kg): Physical mass

- Body Length (cm): Physical size

- Gender: Male, Female

- Observation Date: Date of sighting

The raw data was provided in a semi-colon delimited format and was extremely "dirty," requiring extensive cleaning to ensure scientific accuracy.

---

## Data Cleaning Process
The following steps were performed in Excel:

1.Text-to-Columns Transformation: Parsed semi-colon delimited strings into structured columns.

2. Standardization: Used "Find and Replace" to merge duplicate categories caused by typos, such as "European bison™", "European bisson", and "European buster" into one unified "European Bison".

3. Corrected Spelling Errors: Fixed entries like "red squirel" and "lynx?".

4. Geographic Normalization: Standardized country codes (e.g., "PL" to "Poland").

5. Handled Missing Values: Cleaned null entries in weight and length to ensure accurate averages for benchmarking.

6.Date Grouping: Created helper columns for months to enable seasonal trend analysis.

---

## Analysis Steps
1. Created a master summary table to aggregate sightings by species, country, and month.

2. Calculated:

- Total Sightings per species

- Average Weight (kg) and Average Body Length (cm) per species

- Gender Split per animal type

- Segmented population data into geographic shares to identify regional dominance.

- Built multiple Pivot Tables to power visualizations for seasonal trends and physical benchmarks.

## Visualizations
The following charts were created to build the interactive dashboard:

- Treemap: Geographic distribution showing population share by country.

- Line Chart: Monthly sighting trends showing seasonal activity.

- Clustered Column Chart: Typical physical benchmarks (kg vs. cm).

 - Horizontal Bar Chart: Most observed species rankings.

- Column Chart: Gender breakdown within each species.

  An interactive dashboard was created to summarize insights.

  ---


## Key Findings & Insights
- Total Scale: The study recorded a total of 825 animal sightings.

- Species Dominance: The Red Squirrel is the most frequently observed animal, accounting for 413 observations (roughly 50% of the total demographic).

- Physical Measurement: The European Bison is a massive physical outlier, averaging 588 kg and 244 cm, while the Red Squirrel and Hedgehog average less than 1 kg in weight.

-Regional Hotspots: Poland (192) and Germany (178) are the strongest regions for sightings, accounting for nearly half of the total observations.

## Tools Used
- Microsoft Excel (Data Cleaning, PivotTables, Dashboarding)

- Text-to-Columns & Find/Replace (Data Engineering)

- Interactive Slicers (Dynamic Filtering)

- Advanced Charting (Treemaps, Clustered Columns, Line Trends)

Author
Name: Adeyemi Tomisin Precious
Role: Data Analyst

