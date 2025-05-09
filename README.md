# 🌍 Earthquake Data Analysis

This project explores a dataset of global earthquake events, analyzing and visualizing their magnitude, depth, and locations. It includes geospatial mapping and exploratory data analysis (EDA) using Python libraries like `pandas`, `matplotlib`, `folium`, and `geopandas`.

---

## 📁 Project Structure
earthquakes_2025/
├── data/
│   └── processed/
│       └── cleaned_earthquakes.csv      # Cleaned and filtered seismic dataset
│   └── raw/
│       └── earthquakes.csv              # Original seismic dataset
├── notebooks/
│   └── earthquake_analysis.ipynb        # Jupyter Notebook with all analysis and visuals
├── reports/
│   ├── img
│       └── earthquake_magnitude_histogram.png  # Histogram of magnitudes
│       └── top_locations_earthquakes.png    # Bar chart of most affected locations
│   └── earthquake_map_final.html        # Interactive Folium map
├── src/
│   └── preprocessing.py                 # Optional reusable data cleaning functions
├── requirements.txt                     # Python dependencies
└── README.md                            # Project documentation

---

## ⚙️ Technologies Used

- Python
- Pandas
- Matplotlib
- Folium
- GeoPandas
- Jupyter Notebook

---

## 🔍 Key Features

- **Data Preprocessing**: Handling missing data and filtering for valid magnitudes and coordinates.
- **Interactive Mapping**: Color-coded circle markers by magnitude on a zoomable world map.
- **EDA & Visualization**:
  - Histogram of earthquake magnitudes.
  - Depth vs. magnitude scatter plot.
  - Top 10 most affected locations by frequency.
- **Insights**:
  - Most earthquakes have low magnitude (0–3).
  - Shallow earthquakes are more common.
  - Seismic activity clusters around tectonic boundaries.

---

## 📊 Summary of Findings

- The dataset is rich in **minor earthquakes**, especially in tectonically active zones.
- There is **no strong correlation** between depth and magnitude.
- Interactive visuals help identify seismic **hotspots** effectively.
- Labels like "locations" are extracted from the `place` column and may refer to regions, cities, or general areas — not standardized country names.

---

## 📌 Future Improvements

- Add time-based visualizations (e.g., earthquake trends by year).
- Normalize location data using geocoding APIs.
- Perform clustering analysis to identify high-risk zones.
- Create a dashboard version of the project.

---

## ✅ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/patriciajaquez/earthquakes_2025.git

2.	Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Open the notebook:
   ```bash
   jupyter notebook notebooks/earthquake_analysis.ipynb

---

## 🧑‍💻 Author

This project is part of my portfolio as a Data Analyst in training. It demonstrates skills in:
  - Python data manipulation
  - Data cleaning and wrangling
  - Geospatial data analysis
  - Visualization and storytelling with data