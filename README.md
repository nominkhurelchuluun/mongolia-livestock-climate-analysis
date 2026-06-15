# Climate-Driven Livestock Mortality in Mongolia
### The Role of Summer Drought in Dzud Events

Undergraduate research conducted at Columbia University in collaboration with the 
Lamont-Doherty Earth Observatory. Investigates whether summer drought conditions 
predict winter livestock mortality (dzud) in Mongolia using 33 years of provincial 
census data and satellite-derived climate indices. Full analysis and code available 
upon publication.

## Data Sources
- **Livestock mortality**: Annual species-level census data (1992–2024) from the 
National Statistics Office of Mongolia, covering 21 aimags and 5 species (horse, 
cattle, camel, sheep, goat)
- **Temperature**: ERA5 monthly reanalysis (Hersbach et al., 2020), produced by the 
European Centre for Medium-Range Weather Forecasts, spatially joined to aimag 
boundaries via GeoJSON

## Key Findings
- Summer (June–August) drought is the only season with a statistically significant 
correlation with subsequent winter mortality (r = -0.28)
- Mortality after dry summers (6.5%) is more than double that after normal summers (3.2%)
- Severe summer drought combined with severe winter cold produces mortality rates 
nearly 9x the baseline
- National summer moisture has trended downward since 1950, with a persistent shift 
toward drought conditions after 1997

## Figures

### Total Livestock in Mongolia (1970–2024)
![Livestock trend](mongolia-livestock-climate-analysis/livestock_trend.png)
*National herd size over 54 years, showing post-socialist growth and dzud-driven 
collapses in 2001 and 2010.*

### Livestock vs. Annual Temperature (1970–2024)
![Livestock vs temperature](mongolia-livestock-climate-analysis/annual_mean_temp_vs_livestock_correlation.png)
*Long-run relationship between warming temperatures and total herd size across 
the study period.*

### Year-to-Year Changes: Livestock vs. Temperature
![Year to year changes](mongolia-livestock-climate-analysis/temp_vs_livestock.png)
*Annual changes in livestock population plotted against annual temperature changes, 
highlighting the volatility of dzud shock years.*

*Additional figures available upon request. Full analysis forthcoming with publication.*
