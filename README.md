# Sri Lanka Petrol Tax vs. Petrol Consumption Analysis 🇱🇰

An exploratory data science and statistical pipeline engineered to analyze the structural relationship between retail fuel tax rates and consumer automotive fuel consumption metrics. This project applies programmatic EDA (Exploratory Data Analysis) frameworks to model consumer demand behavior under varying economic conditions.

---

###  Analytics Pipeline & Architecture
This notebook builds an end-to-end data analysis framework within a Google Colab / Jupyter environment:

* **Data Ingestion (ETL):** Implements dynamic, interactive data loading scripts to parse tabular `.csv` sources safely into structured Pandas DataFrames.
* **Exploratory Data Analysis (EDA):** Evaluates correlation matrices across key economic indicators, including consumer average income, highway distribution indices, and licensed driver ratios.
* **Statistical Visualizations (Matplotlib):**
  * *Proportional Share (Pie Charts):* Displays distribution buckets for historical tax thresholds.
  * *Frequency Concentrations (Histograms):* Maps the density spread of macro factors like regional household income lines.
  * *Probabilistic Densities (Box & Violin Plots):* Computes quartile spreads and kernel density estimations (`plt.violinplot`) to trace variance in consumer consumption patterns as tax inputs shift.

---

### Technical Stack & Tools
* **Languages:** Python 3
* **Libraries:** Pandas | NumPy | Matplotlib (`pyplot`)
* **Infrastructure:** Google Colab Cloud Notebook Engine | Git Version Control

