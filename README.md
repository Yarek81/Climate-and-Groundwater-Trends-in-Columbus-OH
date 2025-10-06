# 💧 Climate and Groundwater Trends — Columbus, Ohio

## 🌎 Project Overview

This project explores **the relationship between climate patterns and groundwater levels** in **Columbus, Ohio**, using time-series data analysis and visualization techniques in Python.
The goal is to understand how **precipitation, temperature, and seasonal variation** influence **groundwater availability**, with potential implications for sustainability and water management.

---

## 🧠 Motivation

Natural resources, which are essential for supporting both human and ecological systems, are acutely vulnerable to climate change, particularly fluctuations in temperature and precipitation. 
These changes directly impact the stability, distribution, and abundance of critical resources.
This project investigates:

* Long-term **climate trends** in Columbus, OH
* **Correlations** between precipitation and groundwater depth
* **Seasonal and annual variability** in water availability

By visualizing these trends, we can better interpret environmental data and support **evidence-based resource planning**.

---

## 🧰 Tools & Libraries

The analysis was performed in a **Jupyter Notebook** using the following Python libraries:

| Purpose                                     | Library                                     |
| ------------------------------------------- | ------------------------------------------- |
| Data manipulation                           | `pandas`, `numpy`                           |
| Statistical analysis                        | `scipy`, `statsmodels`                      |
| Visualization                               | `matplotlib`, `seaborn`, `plotly`           |
| Geospatial or time analysis (if applicable) | `datetime`                                  |

---

## 📂 Dataset Description

The dataset integrates climate and hydrological data from sources such as:

* **NOAA Climate Data Online (CDO)** — for local precipitation and temperature
* **USGS Groundwater Data Portal** — for water table measurements
* **Local monitoring stations** — where available

| Column Name         | Description                              |
| ------------------- | ---------------------------------------- |
| `date`              | Observation date                         |
| `precipitation`     | Daily or monthly rainfall (mm or inches) |
| `temperature_avg`   | Average temperature (°F or °C)           |
| `groundwater_level` | Water table depth (ft below surface)     |
| `season`            | Categorical label for warm/cold months   |
| `year`              | Extracted year for temporal grouping     |

---

## 📊 Analysis & Visualizations

The notebook includes:

* 📈 **Trend analysis** — long-term temperature and rainfall patterns
* 💧 **Groundwater level analysis** — fluctuation patterns across seasons
* 🔗 **Correlation plots** — relationships between rainfall and groundwater levels
* 🧮 **Statistical summaries** — identifying significant seasonal differences

## ⚙️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/Climate_And_Groundwater_Trends_Columbus_OH.git
   cd Climate_And_Groundwater_Trends_Columbus_OH
   ```

2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate    # macOS/Linux
   venv\Scripts\activate       # Windows
   ```

3. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch the Jupyter notebook:

   ```bash
   jupyter notebook Climate_And_Groundwater_Trends_Columbus_OH.ipynb
   ```

---

## 🧩 Results

* Precipitation and temperature trends show **observable seasonal cycles**.
* Groundwater levels demonstrate **delayed but correlated responses** to precipitation events.
* Preliminary analysis suggests **warming trends** could impact groundwater recharge rates in the future.

## 👤 Author

**Yarek (Iaroslav Grushetskyi)**
Master’s candidate in Data Science, University of Colorado Boulder
This project is an academic assignment and focuses on environmental analytics and data visualization for real-world insights.
