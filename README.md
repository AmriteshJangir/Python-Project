# Python-Project
# 🌍 Landslide Data Analysis & Visualization

This project performs a detailed exploratory data analysis (EDA) on a landslide dataset using Python, `pandas`, `matplotlib`, and `seaborn`. The goal is to uncover meaningful patterns, trends, and outliers related to landslide occurrences, helping researchers or decision-makers understand environmental and human factors.
--
## 📊 Key Features
- Correlation heatmap of all numerical features
- Monthly frequency of landslides
- Environmental condition distributions:
  - Precipitation
  - Temperature
  - Slope Angle
- Population density vs. Landslide category
- Types of landslides
- Top 10 locations with most landslides
- Landslides by day of the week
- Landslides by hour of the day
- Outlier detection using IQR for:
  - Fatalities
  - Injuries
  - Economic loss

> ✅ All visualizations display automatically in sequence with fallback (dummy) data generated for missing columns.

---

## 🧠 Technologies Used

- Python 3.x
- pandas
- seaborn
- matplotlib
- numpy
---
## 🗂 Dataset

The dataset used is expected to be a CSV file with a minimum column named:
- `event_date` (used to extract month, hour, day)

Optional (but auto-filled if missing):
- `precipitation`
- `temperature`
- `slope_angle`
- `population_density`
- `landslide_category`
- `landslide_type`
- `location`
- `fatalities`, `injuries`, `economic_loss`
---
## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/landslide-eda.git
   cd landslide-eda
