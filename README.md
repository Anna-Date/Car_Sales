# Car-Sales
Kleiner umfassender Datensatz mit 50.000 Fahrzeugangeboten mit technischen Spezifikationen und Kilometerstand

## Project Overview
Dieses Projekt analysiert Wiederverkaufspreise von Autos, um die wichtigsten Faktoren zu identifizieren, die den Wiederverkaufswert beeinflussen. Ziel ist es, datengestützte Erkenntnisse für **bessere Kauf- und Verkaufsentscheidungen** auf dem Gebrauchtwagenmarkt zu liefern.  

Die Analyse umfasst **Datenbereinigung, Feature Engineering, explorative Datenanalyse (EDA), Korrelationsanalyse** und optional **Preisprognosen mittels linearer Regression**. Die Ergebnisse werden in Python und Power BI visualisiert.

---

## Dataset
The dataset contains **7 columns**:

| Column | Description |
|--------|-------------|
| Manufacturer | Car brand (e.g., BMW, Ford) |
| Model | Car model name |
| Engine Size | Engine capacity in liters |
| Fuel Type | Petrol, Diesel, Electric, Hybrid |
| Year of Manufacture | Year the car was built |
| Mileage | Total kilometers driven |
| Price | Final sale price in € |

> Der Datensatz ist bereits bereinigt und strukturiert und eignet sich für Analysen und Modellierungen.

---

## Tools Used
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn) – für Analysis und Modelierung  
- **Jupyter Notebook** – interactive exploration & coding  
- **Power BI** – optional dashboard for business visualization  

---

##  Key Steps
1. **Exploratory Data Analysis (EDA)**
   - Price distribution
   - Price vs Mileage
   - Average Price by Fuel Type

2. **Correlation Analysis**
    - Identifizierte stärkste Faktoren, die den Preis beeinflussen (Kilometerstand, Alter des Fahrzeugs, Engine size)
   - Sekundäre Faktoren: Hersteller, Model

3. **Optional Price Prediction**
   - Linear regression to estimate price
   - Feature importance explains which factors matter most

4. **Business Insights & Recommendations**
* Mileage und Alter haben einen starken negativen Einfluss auf den Preis.
  - Jeder zusätzliche Kilometer reduziert den Preis um ca. 0,038 €;
  - Jedes zusätzliche Jahr senkt den Preis um ca. 989 €;
  - größere Motoren erhöhen den Preis (Jede zusätzliche Einheit Motorgröße erhöht den Preis um ca. 8.934 €)
  * Analyse zeigt, dass Diselhrzeuge am wertstabilsten sind;
  * Die höhere Preise erzielen Porsche, BMW, Toyota;
  * Größere Engine Sizes haben höhere Preise;
  * Optimales Alter für den Wiederverkauf:
    - Sweet Spot: 3–5 Jahre alt;
    - Warnung!: Nach 6–7 Jahren → Preis sinkt deutlich, jedes zusätzliche Jahr kostet mehrere tausend Euro;

---

## Key Insights Visualizations

* Price Distribution
* Price vs Mileage
* Average Price by Fuel Type


---

##  Dashboard (Power BI)

---

## ✅ Conclusion
This project demonstrates the ability to:
- Extract actionable insights from limited datasets
- Identify business-relevant price drivers
- Communicate findings clearly via **visualizations** and **dashboards**
- Apply basic predictive modeling to support decision-making  

**Use Case:** Helps car dealers, resellers, and buyers make **data-driven purchasing decisions**.



