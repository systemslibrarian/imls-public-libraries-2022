# 📊 Libraries in Numbers

**IMLS-based insights into library usage, funding, and access.**

This public data analytics project explores how libraries serve communities through usage trends, program offerings, digital access, and more.

Using real-world data from the Institute of Museum and Library Services (IMLS), this project visualizes key performance indicators and provides actionable insights into the evolving role of libraries.

---

## 📓 Notebooks

This project explores how public libraries serve communities using data from the Institute of Museum and Library Services (IMLS).

Each notebook:
- Loads and prepares public library survey data (FY 2022)
- Visualizes usage, access, and funding trends across U.S. states
- Highlights key insights on equity, digital access, and community reach

📘 See the [Notebook Index](#-notebook-index) below for details on each analysis.

---

## 📘 Notebook Index

### `public_library_data_fy2022.ipynb`
- Loads the **FY 2022 IMLS Administrative Entity (AE)** dataset
- Cleans the raw data by replacing negative values with nulls
- Renames and selects relevant fields for analysis
- 📊 Visualizes:
  - Top 15 states by library visits per 1,000 residents
  - Choropleth: Library visits per 1,000 people by state
  - Choropleth: Library funding per capita by state
- Saves a cleaned CSV file for use in dashboards

---

### `public_library_digital_access_fy2022.ipynb`
- Loads the full **raw AE dataset** to access digital access metrics
- 🖥 Visualizes access per capita across the U.S.:
  - Choropleth: E-book collections per 1,000 people
  - Choropleth: Electronic circulation per 1,000 people
- Caps extreme outliers to improve readability
- Highlights gaps in digital equity

---

## 📂 How to Use

You can open any of these notebooks in:
- [Google Colab](https://colab.research.google.com/) (recommended)
- JupyterLab or Jupyter Notebook locally

Each notebook includes markdown documentation and outputs inline.

---

## 🧾 Source

All data comes from the IMLS Public Libraries Survey:  
🔗 https://imls.gov/research-evaluation/data-collection/public-libraries-survey
