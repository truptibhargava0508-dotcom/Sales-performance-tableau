# Sales-performance-tableau
Interactive Tableau dashboard analysing climate pressure, human vulnerability and policy effectiveness across 193 countries (1990–2025), using weighted composite indices built from open Kaggle data.
# Climate Pressure, Impact and Policy Effectiveness

An interactive Tableau dashboard that analyses how climate pressure, human vulnerability and climate policy compare across 193 countries from 1990 to 2025.

**Author:** Trupti Bhargava, B.Tech Information Technology, MPSTME, NMIMS, Mumbai

## Objective
To turn a large, multi-indicator climate dataset into a clear, comparable view of which countries face the most climate pressure, who is most vulnerable to its effects, and whether policy effort matches environmental outcomes.

## Data
- **Source:** Kaggle dataset *global_climate_impact_1990_2025*, used under its published licence.
- **Size:** 6,948 records, 94 indicators, 193 countries, 6 continents, 1990–2025.
- **Themes:** emissions, energy, temperature, forests, water, agriculture, extreme events, health, economy and climate policy.

## Data preparation
- Converted numeric fields that were stored as text.
- Handled missing values (about 1% of cells).
- Validated fields before analysis.

## Method
- **Climate Pressure Index:** a weighted composite of six min–max normalised indicators: CO₂ per capita (25%), fossil-energy share (20%), temperature anomaly (20%), heatwave days (15%), drought index (10%) and deforestation rate (10%). Countries are graded Low, Moderate, High or Very High.
- **Human Climate Vulnerability Index:** the average of five normalised measures: displaced persons, heat-related deaths, food insecurity, respiratory disease and climate damage cost.
- **Carbon intensity:** CO₂ emissions divided by GDP. Countries are placed in quadrants using the median GDP and median carbon intensity.
- **Policy gap:** climate policy score compared with the Environmental Performance Index [correlation r = ___].

## Dashboard views
1. **Climate Pressure Index:** country ranking with a Top-N control and a global-average reference line.
2. **Economic Carbon Efficiency:** GDP against carbon intensity, split into four quadrants.
3. **Human Vulnerability Ranking:** world map of vulnerability by country.
4. **Policy Effectiveness and Sustainability Gap:** policy score against environmental performance.

Filters: year, country and continent.

## Key findings
- [Finding 1, from your dashboard]
- [Finding 2]
- [Finding 3]

## Repository contents
| File | Description |
|---|---|
| `VA_Project_F042F043F044.twbx` | Tableau packaged workbook |
| `data/` | Cleaned dataset (CSV) |
| `screenshots/` | Images of the dashboard |

## How to open
1. Install Tableau Desktop or Tableau Public (free).
2. Open the `.twbx` file, or view the live dashboard through the link above.

## Limitations
- The index weights are chosen by the author, not derived statistically.
- Normalisation uses the full 1990–2025 range, so scores are relative to this dataset.
- Missing values reduce coverage for some countries and years.

## Licence and acknowledgements
Data is from Kaggle under its original licence. This project was created for academic purposes.
