# Unemployment Unplugged

🔗 **Final Report Project by Myra Arif and Britney Zhu**

**Unemployment Unplugged** is a data analysis project that explores how **COVID-19 impacted state-level unemployment** rates across the United States as each state reported its first confirmed case.

This project was created as part of a data-driven research course. It originally intended to explore anxiety and depression trends during the early pandemic but pivoted to unemployment due to data availability constraints.

---

## 🔎 Project Summary

As COVID-19 spread across the United States in early 2020, the national unemployment rate surged to historic highs. While the broader trend was well-documented, fewer studies had explored how the **timing of a state’s first COVID-19 case** correlated with **changes in unemployment at the state level**.

**Research Question**  
> How did unemployment behavior shift in individual U.S. states following the emergence of COVID-19?

---

## 📊 Dataset & Methods

**Data Sources**
- State-level unemployment rates (Oct 2019 – Dec 2020)
- U.S. Census population estimates for 2019 and 2020
- Date of first confirmed COVID-19 case per state

**Why use the number of unemployed people instead of percentages?**
- Percentages alone don't account for large differences in population between states.
- For clarity, we converted unemployment rates into **estimated unemployed counts**.

**Phases of Analysis**
We segmented the timeline into three phases for each state:
- **Phase 1 (Before COVID)** — 3 months prior to first case
- **Phase 1 (After COVID)** — 3 months after first case
- **Phase 2 (6 Months Later)** — Months 6–8 after first case

We averaged unemployment counts across these periods to detect shifts in trends.

---

## 🧠 My Role

I (Myra Arif) was responsible for:
- Writing Python scripts to clean, transform, and analyze the data
- Calculating total unemployed individuals per state using population × unemployment rate
- Creating a function to dynamically extract relevant months per phase
- Computing phase averages and formatting the final dataset for analysis

**Britney Zhu** was responsible for:
- Choosing the most compelling results for presentation
- Designing all visuals and charts
- Structuring the final report and presentation slide deck

---

## 📌 Key Findings

- 📈 Unemployment increased significantly in every state after the first COVID-19 case
- 📊 The severity of the increase varied based on the state’s population and timing
- 🧾 By Phase 2, many states began to stabilize, though rates remained higher than before COVID

---

## ⚠️ Limitations

- Some Phase 1 “before” periods had incomplete data due to missing 2019 months
- Population estimates (not actual census counts) were used
- State-level unemployment was influenced by unique local COVID responses

---

## 🛠 Technologies Used

- Python 3
- Pandas
- NumPy
- (Visualization by Britney): Matplotlib & Seaborn



