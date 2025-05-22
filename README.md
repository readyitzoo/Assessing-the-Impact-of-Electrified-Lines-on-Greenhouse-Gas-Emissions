# 🚄 Sustainable Development of Railway Transport

This repository contains the code, data, and analysis supporting the research article:

**"Assessing the Impact of Electrified Lines on Greenhouse Gas Emissions in the EU"**

The study explores how railway electrification correlates with greenhouse gas (GHG) emission trends across European countries using official Eurostat data and statistical modeling.

---

## 📌 Objectives

- Investigate the relationship between the length of electrified railway lines and net GHG emissions per capita.
- Perform correlation and regression analysis for each EU member state.
- Identify top-performing and underperforming countries in terms of electrification impact.
- Provide policy recommendations based on empirical evidence.

---

## 📊 Dataset

- **Electrified Railway Lines:** Kilometers of electrified tracks (2012–2021) per EU country  
  *Source:* [Eurostat Railway Transport Dataset (2023a)](https://ec.europa.eu/eurostat/databrowser/view/RAIL_IF_ELECTRI__custom_7181972)

- **GHG Emissions:** Greenhouse gas emissions per capita in tonnes (2012–2021)  
  *Source:* [Eurostat SDG 13.10 Dataset (2023b)](https://ec.europa.eu/eurostat/databrowser/view/SDG_13_10)

---

## 🧪 Methodology

- **Ex-post quantitative analysis** using Python
- Metrics calculated:
  - Pearson's r and r² (coefficient of determination)
  - Statistical significance at 95% confidence level
  - Regression equations for each country
- Best/worst countries identified and analyzed through plots and comparisons

---

## 🔍 Key Findings

- **Top performers** in electrification growth: Estonia, Greece, and Denmark
- **Top performers** in GHG reduction: Luxembourg, Estonia, and Finland
- **Romania:** Modest electrification progress (0.37%) but moderate GHG decline (-7.69%)
- **Regression Results:** Mixed significance across countries; some showed strong negative correlations, suggesting that increasing electrification is associated with reduced emissions

---

## 🧰 Tools Used

- Python 3
- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Visualization
- `scipy.stats`, `sklearn.linear_model` – Statistical analysis and regression

---

## 👩‍🔬 Authors

- Code - [Mihai Dilirici](mailto:mihai.dilirici@s.unibuc.ro)

---

## 📜 License

This work is provided for educational and non-commercial research purposes. Attribution required if reused in academic or professional contexts.

---

## 📖 Citation

If you use this work, please cite the associated article (once published) or credit the GitHub repository in your work.


