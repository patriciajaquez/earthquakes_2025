# 🌍 Earthquake Data Analysis

This project explores a dataset of global earthquake events, analyzing and visualizing their magnitude, depth, and locations. It includes geospatial mapping and exploratory data analysis (EDA) using Python libraries like `pandas`, `matplotlib`, `folium`, and `geopandas`.

---

## 📁 Project Structure

- `earthquakes.csv`: Source dataset with global seismic data
- `earthquake_map_final.html`: Interactive HTML map generated using Folium
- `earthquake_magnitude_histogram.png`: Histogram of earthquake magnitudes
- `top_locations_earthquakes.png`: Bar chart showing most affected regions
- Jupyter Notebook: Contains full code, visualizations, and insights

---

## ⚙️ Technologies Used

- python
- pandas
- matplotlib
- folium
- geopandas
- Jupyter Notebook

---

## 🔍 Key Features

- **Data Preprocessing**: Handling missing data and filtering for valid magnitude and coordinates
- **Interactive Mapping**: Color-coded circle markers by magnitude on a zoomable world map
- **EDA & Visualization**:
  - Histogram of earthquake magnitudes
  - Depth vs. magnitude scatter plot
  - Top 10 most affected locations by frequency
- **Insights**:
  - Most earthquakes have low magnitude (0–3)
  - Shallow earthquakes are more common
  - Seismic activity clusters around tectonic boundaries

---

## 📊 Summary of Findings

- The dataset is rich in **minor earthquakes**, especially in tectonically active zones.
- There is **no strong correlation** between depth and magnitude.
- Interactive visuals help identify seismic **hotspots** effectively.
- Labels like "locations" are extracted from the `place` column and may refer to regions, cities, or general areas — not standardized country names.

---

## 📌 Future Improvements

- Add time-based visualizations (e.g., earthquake trends by year)
- Normalize location data using geocoding APIs
- Perform clustering analysis to identify high-risk zones
- Create a dashboard version of the project

---

## 🧑‍💻 Author

This project is part of my portfolio as a Data Analyst in training. It demonstrates skills in:
- Python data manipulation
- Data cleaning and wrangling
- Geospatial data analysis
- Visualization and storytelling with data