
# 📊 Caste-Based Crime Analysis Dashboard (2001–2013)

This project is an **interactive data dashboard** built using **Streamlit** and **Plotly** for analyzing caste-related crimes in India from 2001 to 2013. It visualizes patterns of crimes against **Scheduled Castes (SC)** and **Scheduled Tribes (ST)** across Indian states and districts.

---

## 📁 Project Structure

```
├── main.py                  # Streamlit application code for dashboard interface
├── preprocessor.py          # Helper functions for plotting and data filtering
├── cleaned_data.csv         # Preprocessed crime data (user must provide)
├── logo.jpg                 # Logo image shown on the sidebar
└── README.md                # Project documentation (you are here)
```

---

## 🚀 Features

- 📍 **Map Visualization** of total crimes by state.
- 📊 **State & District-Level Analysis** using bar charts and pie charts.
- 📈 **Year-wise Crime Trends** to observe time series data.
- 📂 **Crime Type Filtering** for detailed investigation.
- 📑 **Expandable Explanations** and links to legal resources.
- 🧭 **Custom Layout** for user-friendly navigation.

---

## 🛠️ Installation & Running

### ✅ Prerequisites

- Python 3.7+
- Required packages:

```bash
pip install streamlit pandas plotly
```

### ▶️ Run the App

Ensure you have `cleaned_data.csv` and `logo.jpg` in the root directory.

```bash
streamlit run main.py
```

Then, open the Streamlit-provided local URL in your browser.

---

## 📌 About the Dashboard

> "This dashboard presents an analysis of caste-related crimes in India, focusing on data from 2001 to 2013. It offers insights into how crimes against SCs and STs were distributed across regions during this period. Despite legal protections such as the SC/ST Act of 1989, caste-based violence has remained prevalent. This tool helps highlight the historical context and ongoing challenges for these marginalized communities."

---

## 🔍 Filters Available

- 📅 **Year Range** (2001–2013)
- 🌐 **State/UT & District Selection**
- 🔎 **Crime Type Selection** (e.g., Murder, Rape, Assault)

---

## 📚 Legal Context

The project references protections under the **SC/ST (Prevention of Atrocities) Act**, **Protection of Civil Rights (PCR) Act**, and other related laws. You can learn more from the [official document](https://ncsk.nic.in/sites/default/files/PoA%20Act%20as%20amended-Nov2017.pdf).

---

## 📈 Visualizations Provided

- State-wise Crime Heatmap (Mapbox)
- Bar Graphs for Top States & Districts
- Pie Charts for Crime Types
- Line Graphs for Yearly Trends

---

## ✅ Future Enhancements

- Add support for crimes against STs and Women
- Deploy the dashboard using Streamlit Cloud or Heroku
- Integrate real-time data via government APIs

---

## 🤝 Acknowledgments

- [Streamlit](https://streamlit.io/)
- [Plotly Express](https://plotly.com/python/plotly-express/)
- [Government of India Open Data Portal](https://data.gov.in/)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
