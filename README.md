# 📊 Libraries in Numbers: Public Library Usage and Funding (FY 2022)

**Libraries in Numbers** is a public data analytics project that explores how libraries serve communities through usage trends, program offerings, digital access, and funding equity.

Using real-world data from the Institute of Museum and Library Services (IMLS), this project cleans and visualizes key performance indicators (KPIs) to better understand the evolving role of libraries across the U.S.

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

