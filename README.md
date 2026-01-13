# Weather Analytics Dashboard — Power BI

An interactive **Power BI Weather Analytics Dashboard** built using real-time and forecast data from **WeatherAPI**.  
This project focuses on **API-based data ingestion**, **data transformation using Power Query**, and **modern dashboard design** with theme customization.

---

## What this dashboard does

This dashboard provides a **comprehensive weather overview** for selected cities, combining **current conditions**, **forecast trends**, **air quality metrics**, and **environmental indicators** into a single interactive view.

It answers questions like:

- What is the current temperature and weather condition for a city?
- How will the temperature change over the next few days?
- What are the sunrise and sunset timings?
- How clean is the air today (AQI)?
- What are the levels of major air pollutants?
- What is the probability of rain on upcoming days?
- How does the dashboard look across different color themes?

---

## Key insights & visuals

- City-wise current temperature and weather condition
- Multi-day temperature forecast trend
- Sunrise and sunset timings
- Humidity, wind speed, visibility, pressure, UV index & precipitation
- Air Quality Index (AQI) with qualitative status
- Pollutant breakdown:
  - PM2.5
  - PM10
  - CO
  - NO₂
  - SO₂
  - O₃
- Day-wise chances of rain
- Theme customization:
  - Blue theme
  - Orange theme
  - Gradient theme (default)

---

## How the interactivity works

- **City selector** allows switching between available cities.
- All visuals dynamically update based on the selected city.
- Forecast charts respond to city and date context.
- Theme buttons allow instant switching between color schemes.

---

## How I built this project

- **Data source:** Weather data fetched using **WeatherAPI (Free Tier)**.
- **API constraints:** Due to free-tier limitations, data was fetched for **limited cities**.
- **Data cleaning & preparation:** Done entirely in **Power Query**, including:
  - JSON parsing
  - Column normalization
  - Unit standardization
  - Date & time formatting
- **Visualization:** Clean, insight-focused visuals built in **Power BI**.
- **Design approach:** Dark UI with soft gradients and balanced spacing.

---

## Repository structure
├── Icons
│ ├── Air pressure.png # Air pressure icon
│ ├── Humidity.png # Humidity icon
│ ├── placeholder.png # Placeholder icon
│ ├── Precipitation.png # Precipitation icon
│ ├── Sunrise.png # Sunrise icon
│ ├── Sunset.png # Sunset icon
│ ├── UV_index.png # UV index icon
│ ├── Visibility.png # Visibility icon
│ └── Wind_speed.png # Wind speed icon
│
├── Dashboard snapshot.png # Screenshot of the final Power BI dashboard
├── Desktop 3.pbix # Main Power BI report file
└── README.md # Project documentation


---

## How to use the dashboard

1. Download and open the `.pbix` file in **Power BI Desktop**.
2. The report contains saved Power Query steps and a data snapshot.
3. To refresh or extend the forecast:
   - Open **Power Query Editor**
   - Go to the **Source** step
   - Replace the existing **WeatherAPI key** with a new valid key
   - Click **Close & Apply**
4. Refresh the report to load updated weather data.
5. Use city selectors and theme buttons to explore insights.

---

## Notes & limitations

- Uses **WeatherAPI Free Tier**
- Free API key is **valid only until 20 January**
- After that, forecast data will be **limited to fewer days**
- To restore full multi-day forecast, update the API key in Power Query
- Data is for **learning and demonstration purposes**
- Weather values may vary slightly from official sources

---

## Why I made this

This project helped me improve my skills in:

- Working with REST APIs in Power BI
- Advanced Power Query transformations
- Handling API limitations
- Dashboard storytelling & UX design
- Visualizing environmental and AQI data

---

## Demo

▶️ 

---
## Contact

If you’d like to share feedback, ideas, or collaborate:

- LinkedIn: **Ashutosh Kumar Jalan**  
  https://www.linkedin.com/in/ashutoshjalan-/
