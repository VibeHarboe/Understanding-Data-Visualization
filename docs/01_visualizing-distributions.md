# 📊 Visualizing Distributions

**Course:** Understanding Data Visualization (DataCamp)
**Chapter:** 1 – Visualizing Distributions

---

This chapter focuses on how to recognize patterns, distributions, skewness, and variable types using visual tools such as histograms and bar charts. The following exercises combine interpretation, classification, and critical assessment of visuals based on real datasets.

---

## 📋 Exercise: Bitcoin Price Insight

### Goal

Visually identify which year between 2016 and 2020 started with the highest Bitcoin price.

### Visualization Insight

The chart shows the Bitcoin price trend from 2016 to 2020. Red dots mark the price on January 1st of each year.

**Observation:**
▶️ 2018 began with the highest Bitcoin price (\~\$14,000–\$15,000).
This demonstrates how well-designed plots can quickly reveal trends and anomalies in data that might not be obvious in raw tables or numeric summaries.

### 🖼️ Visualization Reference

**Image:** Bitcoin price trend with January 1st markers (2016–2020)
[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/4ec10c4ddb21b3544b03acd36a2fbf1df9c2a9c4/visuals/Visualizing%20Distributions/Motivating-visualization.jpg)

![Bitcoin price trend with January 1st markers (2016–2020)](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/4ec10c4ddb21b3544b03acd36a2fbf1df9c2a9c4/visuals/Visualizing%20Distributions/Motivating-visualization.jpg "Bitcoin price trend with January 1st markers (2016–2020))")

---

## 📋 Exercise: Continuous vs. Categorical Variables

To choose the correct type of plot, you must distinguish between **continuous** variables (numeric values you can calculate with) and **categorical** variables (labels or groups).

### ✅ Categorized:

**Continuous:**

* Population of towns in Canada
* Salary of employees
* Mass of squirrels

**Categorical:**

* Job title of employees
* Provinces of towns in Canada
* Was the exam passed or failed?

---

## 📋 Exercise: Interpreting Histograms

The histogram displays the distribution of average taxable income for various jobs in Australia.

* **X-axis**: Average taxable income (AUD/year)
* **Y-axis**: Number of job types in each income bracket

### ✅ Categorized Statements

**True:**

* The histogram is unimodal.
* The histogram is right-skewed.
* The most popular salary bracket is \$40k to \$60k.

**False:**

* The histogram is bimodal.
* The most popular salary bracket is \$560k to \$580k.
* The histogram is left-skewed.

🖼️ **Visualization Reference:**
[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg)

![Interpreting histograms](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg "Interpreting histograms)")

---

## 📋 Exercise: Adjusting Bin Width

This histogram shows the time of day when agoutis (rodents) were most active, based on camera trap data from Panama.

* **X-axis**: Time of day (0–24 hours)
* **Y-axis**: Count of agouti sightings

### ✅ Interpretation

* The agouti were **most active between 4 AM and 12 PM**, with a clear peak around sunrise (6:30 AM to 8:30 AM).
* There is **moderate activity between 12 PM and 8 PM**.
* The selected bin width (≈2 hours) balances noise and shape clarity.

**Correct statement:**

> The agouti had a high level of activity from 4am to 12pm, then moderate activity from 12pm to 8pm.

### 🖼️ Visualization Reference

**Image:** Agouti activity histogram by time of day
[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/056ff659cc0519ab3a06f9e8d93ae4fd5a024d69/visuals/Visualizing%20Distributions/Adjusting%20bin%20width/2%20hours_Adjusting%20bin%20width.PNG)

➡️ All visuals from this exercise are available in the `visuals/` folder:
[📁 Browse all visuals](https://github.com/VibeHarboe/Understanding-Data-Visualization/tree/056ff659cc0519ab3a06f9e8d93ae4fd5a024d69/visuals/Visualizing%20Distributions/Adjusting%20bin%20width)

![Agouti activity histogram by time of day](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/056ff659cc0519ab3a06f9e8d93ae4fd5a024d69/visuals/Visualizing%20Distributions/Adjusting%20bin%20width/2%20hours_Adjusting%20bin%20width.PNG "Agouti activity histogram by time of day)")

---

## 📋 Exercise: Interpreting Box Plots

Box plots of cigarette consumption per person in the U.S. from 1985 to 1995 show yearly distributions across 48 states. Each plot represents one year’s data, with the number of cigarette packets smoked per capita on the x-axis and years on the y-axis.

### ✅ Categorized Statements

**True:**

* The lower quartile number of packets of cigarettes smoked per capita decreased every year from 1985 to 1995.
* In 1990, three states were considered to have extreme values in the number of packets of cigarettes smoked per capita.
* The median number of packets of cigarettes smoked per capita was below 100 from 1991 onwards.

**False:**

* The inter-quartile range of the number of packets of cigarettes smoked per capita was smallest in 1992.
* The inter-quartile range of the number of packets of cigarettes smoked per capita decreased every year from 1985 to 1995.
* The upper quartile number of packets of cigarettes smoked per capita decreased every year from 1985 to 1995.

### 🖼️ Visualization Reference

**Image:** Box plots of per-capita cigarette consumption (1985–1995)
[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/ae9f68e45c58e916ac594a72ff25fe3cb955111c/visuals/Visualizing%20Distributions/boxplot%20cig%20consumption%20by%20year.jpg)

![Box plots of per-capita cigarette consumption (1985–1995))](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/ae9f68e45c58e916ac594a72ff25fe3cb955111c/visuals/Visualizing%20Distributions/boxplot%20cig%20consumption%20by%20year.jpg "Box plots of per-capita cigarette consumption (1985–1995))")

---

## 📋 Exercise: Ordering Box Plots

This visualization shows box plots of cigarette consumption per year for each U.S. state from 1985 to 1995. Each box plot contains 11 data points (one per year) and displays variation across time.

### 🔍 Sorting by variable:

* Sorting alphabetically helps locate specific states.
* Sorting by **median** helps identify states with highest/lowest typical consumption.
* Sorting by **IQR** helps identify states with greatest variation in "typical" consumption.

### ❌ False Statement (correct answer):

> North Carolina has the fourth highest median consumption.

### ✅ Correct Statements:

* The lower whisker for Alabama is completely above 100 packs/capita/year.
* New Hampshire has the third widest inter-quartile range of consumption.
* Idaho has the fourth lowest median consumption.

### 🖼️ Visualization Reference

**Image:** Cigarette consumption box plots by U.S. state (1985–1995)
[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/80aa2da4932ed96b0640c4139fd5e41c534a6dcb/visuals/Visualizing%20Distributions/Ordering%20box%20plots/Ordering%20box%20plots_us%20state.png)

➡️ All visuals from this exercise are available in the `visuals/` folder:
[📁 Browse all visuals](https://github.com/VibeHarboe/Understanding-Data-Visualization/tree/80aa2da4932ed96b0640c4139fd5e41c534a6dcb/visuals/Visualizing%20Distributions/Ordering%20box%20plots)

![Cigarette consumption box plots by U.S. state (1985–1995)](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/80aa2da4932ed96b0640c4139fd5e41c534a6dcb/visuals/Visualizing%20Distributions/Ordering%20box%20plots/Ordering%20box%20plots_us%20state.png "Cigarette consumption box plots by U.S. state (1985–1995)")

---

## 🧠 Learning Outcome

* Understand how visual encoding (position, color, scale) drives insight
* Recognize distribution patterns without relying on statistical metrics
* Use visuals to identify meaningful breakpoints, trends, and anomalies in time series data

---
