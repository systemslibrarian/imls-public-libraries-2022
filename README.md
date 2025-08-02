# 📊 IMLS Public Libraries — FY 2022 Insights

**Data-driven insights from the IMLS FY 2022 Public Libraries Survey.**

This public data analytics project explores how libraries serve communities through usage trends, digital access, and public program engagement.

Using data from the Institute of Museum and Library Services (IMLS), we visualize key performance indicators and highlight equity gaps across U.S. states.

---

## 📓 Notebooks

Each notebook loads FY 2022 IMLS public library data and generates per-capita comparisons across the U.S.

📘 See the Notebook Index below for topic areas and insights.

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

### `public_library_programs_fy2022.ipynb`
- Loads the **raw FY 2022 AE dataset**
- 📅 Visualizes public program output and engagement:
  - Choropleth: Attendance per 1,000 people by state
  - Scatter plot: Programs per capita vs. attendance per capita
- Highlights relationships between service output and community engagement

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
