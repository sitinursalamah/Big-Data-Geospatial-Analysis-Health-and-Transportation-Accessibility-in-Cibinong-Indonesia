# 🗺️ Big Data Geospatial Analysis: Health and Transportation Accessibility in Cibinong, Indonesia

This project explores spatial accessibility to healthcare facilities in Cibinong, West Java, Indonesia using geospatial data from **OpenStreetMap (OSM)** and analysis tools such as **OSMNX**, **NetworkX**, and **GeoPandas**.

## 🎯 Objective

To assess healthcare accessibility and transportation network efficiency in Cibinong through a data-driven geospatial analysis, supporting infrastructure planning and policy decision-making.

## 🧩 Case Study

- **Location**: Cibinong District, Bogor Regency, West Java, Indonesia
- **Focus**: Road networks and spatial distribution of healthcare facilities (hospitals and clinics)

---

## 🛠️ Tools & Technologies

- **Python**
- **Google Colaboratory**
- Libraries:
  - `osmnx` – OpenStreetMap data extraction and routing
  - `networkx` – Graph analysis
  - `geopandas` – Spatial data handling
  - `folium` – Interactive mapping
  - `matplotlib`, `seaborn` – Visualization

---

## 🔧 Methodology

1. **Data Retrieval** using OSMNX
2. **Network Construction** of roads
3. **Centrality Analysis**: degree, betweenness, closeness
4. **Healthcare Facility Mapping**
5. **Accessibility Classification** by shortest path distance
6. **Heatmap Visualization**

---

## 📊 Key Results

### Road Network Characteristics
- **Nodes**: 9,076
- **Edges**: 21,666
- **Total Network Length**: ~1,284 km
- **Avg. Connectivity**: 4.77
- **Circuity**: 1.07 (indicating efficient routing)

### Centrality Insights
- **Top Degree Node**: Indicates key local hubs
- **Top Betweenness Node**: Critical traffic bottlenecks
- **Top Closeness Node**: Best overall access

### Healthcare Facilities
| Type      | Count | %    |
|-----------|-------|------|
| Hospitals | 7     | 77.8 |
| Clinics   | 2     | 22.2 |
| **Total** | 9     | 100  |

### Accessibility Classification
- **Excellent (< 1 km)**: 15.4%
- **Moderate (1–3 km)**: 41.7%
- **Poor (> 3 km)**: 42.9%

---

## 🌡️ Heatmap Interpretation

- **Dark Green**: Excellent access (e.g., Cirimekar, Ciriung)
- **Yellow to Orange**: Moderate access (e.g., Sukahati)
- **Red**: Poor access – southern and border areas

---

## 📌 Recommendations

- Prioritize infrastructure development in poorly served areas
- Improve healthcare service distribution in southern/western subdistricts
- Use findings to support **evidence-based urban planning**

---

## 💡 Highlights

- Integrated **open geospatial data** and **network science** techniques
- Demonstrated real-world application for **urban planning and health accessibility**
- Fully reproducible in **Google Colab**

---

