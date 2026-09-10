# Seasonal Agriculture Performance Analysis

Major Project – VOIS AICTE Batch 1 (2026–2027)

M Mohammad Khaja Hussain

AICTE ID:  STU658b8975b83d61703643509

## Project Discription


I worked with a dataset of 4000 farms spread across 8 states in India, covering the three main growing seasons Kharif, Rabi and Zaid. 
First step was cleaning the data some missing rainfall and yield values, checked for duplicates), then I compared things like yield, profit, rainfall, water usage, irrigation type and crop performance between the seasons. 
The main thing I found was that Kharif season does the best overall  better yield, better profit, and farms use water more efficiently. Zaid was the weakest season, and a lot of farms in Zaid actually ended up losing money. 
Based on this, I put together a few suggestions on crop and irrigation choices that could help improve outcomes, especially in Zaid. 

## Dataset

- 4,000 records
- 8 states
- 3 seasons: Kharif, Rabi, Zaid
- 8 crops: Rice, Wheat, Maize, Cotton, Pulses, Groundnut, Chilli, Sugarcane
- Features: rainfall, temperature, humidity, soil moisture, water usage/efficiency, irrigation method, fertilizer use, yield, profit, disease/pest risk

## Tools Used

- Python
- Pandas, NumPy – cleaning and analysis
- Matplotlib, Seaborn – visualization
- Jupyter Notebook

## What's in the Notebook

1. Importing libraries and loading the dataset
2. Data cleaning (handling missing values, checking duplicates)
3. Seasonal overview – how many records per season
4. Average yield and profit by season
5. Percentage of farms operating at a loss, by season
6. Environmental conditions (rainfall, temperature) across seasons
7. Water usage and water efficiency by season
8. Effect of irrigation method on yield
9. Disease/pest risk by season
10. Most and least profitable crop–season combinations
11. Crop performance across seasons (heatmap)
12. State-wise seasonal profit comparison
13. Correlation between key factors and yield
14. Key insights, recommendations, and conclusion

## Key Findings

- **Kharif performs best overall** — highest yield, highest profit, best water efficiency, and the most rainfall of the three seasons.
- **Zaid performs the weakest** — lowest yield, a net average loss, and the highest percentage of farms running at a loss.
- **Water efficiency matters more than rainfall itself** — it has the strongest relationship with yield (correlation ≈ 0.92), well above rainfall, temperature, humidity, or fertilizer use.
- **Irrigation method makes a real difference** — Drip irrigation consistently beats Sprinkler, Flood, and Rainfed.
- **Kharif's strength comes with a trade-off** — it also has the highest disease/pest risk, likely tied to the higher rainfall and humidity.
- **Crop choice depends on season** — Sugarcane and Chilli stay profitable in every season, but Rice, Wheat, Maize, and Pulses specifically lose money in Zaid.
- **The pattern holds across states** — Kharif's advantage and Zaid's weakness aren't limited to one region.

## Recommendations

- Prioritize Kharif-season cultivation where possible.
- Reconsider crop choice for Zaid — crops like Rice, Wheat, and Maize may need to be swapped for more resilient options like Sugarcane or Chilli.
- Invest in drip irrigation, especially for farms still using Rainfed or Flood methods.
- Focus on improving water-use efficiency specifically, not just water availability.
- Strengthen pest/disease management during Kharif to protect its otherwise strong performance.

## Conclusion

Agricultural performance clearly changes across seasons — Kharif comes out ahead on yield and profit, while Zaid is consistently the weakest and riskiest. Interestingly, how efficiently water is used turns out to matter more than rainfall or temperature on their own. Combined with smarter crop selection by season and better irrigation, these findings point to some practical, data-backed ways to improve outcomes — especially for the Zaid season.

## Future Scope

- Build a model to predict yield/profit before a season starts
- Bring in live weather data instead of relying on historical averages
- Expand the dataset to more states, crops, and years
- Turn this into a simple dashboard farmers could actually use
- Add a crop-recommendation feature based on soil, irrigation, and season


