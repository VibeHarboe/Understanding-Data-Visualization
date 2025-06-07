# 📊 Visualizing Two Variables

**Course:** Understanding Data Visualization (DataCamp)
**Chapter:** 2 – Visualizing Two Variables

---

This chapter explores how to visualize relationships between two variables. The goal is to identify trends, correlations, and patterns that might be hidden in tabular data. Visualization techniques vary depending on whether the variables are **continuous** or **categorical**.

---

## 🧠 Key Concepts

* **Continuous vs. Categorical Variables**
  Determines the appropriate plot type.
* **Scatter Plots**
  Ideal for showing the relationship between two continuous variables.
* **Line Plots**
  Reveal trends over time.
* **Bar Plots**
  Compare metrics across categories.
* **Box Plots**
  Summarize distributions within categories.
* **Dot Plots**
  Highlight subtle differences across categories.

---

## 📋 Exercise: Interpreting Scatter Plots

This scatter plot displays the relationship between average life expectancy and average years of schooling by country. A linear regression trend line is included to show the general relationship.

### ✅ Categorized Statements

**True:**

* Every country with an average life expectancy of less than 60 years has an average length of schooling less than 7 years.
* There is a positive correlation between the life expectancy and the length of schooling.
* As the average length of schooling increases, so does the average life expectancy.

**False:**

* No countries have an average length of schooling less than 6 years and a life expectancy above 75 years.
* A longer average schooling always implies greater life expectancy.
* There is a negative correlation between the two variables.

### 🖼️ Visualization Reference

[📷 View scatter plot](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/195e1fc298cbe7a8d230e2e21b403803b76b42ae/visuals/Visualizing%20Two%20Variables/scatter-who-life-exp-vs-school.jpg)

➡️ All timeslot-specific visuals from this exercise are available in the `visuals/` folder:
[📁 Browse all visuals](https://github.com/VibeHarboe/Understanding-Data-Visualization/tree/f0174fb9dc2290277661f3e39f9544c995cb85d1/visuals/Visualizing%20Two%20Variables)

![Interpreting Scatter Plots](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/195e1fc298cbe7a8d230e2e21b403803b76b42ae/visuals/Visualizing%20Two%20Variables/scatter-who-life-exp-vs-school.jpg "Interpreting Scatter Plots)")

---

## 📋 Exercise: Trends with Scatter Plots

This scatter plot compares life expectancy with Gross National Income (GNI) per capita. The x-axis is presented in both **linear** and **logarithmic** scales to illustrate how scaling impacts interpretation.

### ✅ Interpretation

> Life expectancy increases linearly with the logarithm of GNI when GNI is between \$1k and \$50k.

### 🖼️ Visualization References

* [📷 Linear Scale](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/2.%20GNI%20vs%20Life%20Expectancy%20Linear.png)
* [📷 Logarithmic Scale](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/2.%20GNI%20vs%20Life%20Expectancy%20Logarithmic.png)

---

## 📋 Exercise: Interpreting Line Plots

This line plot shows the adoption of four household technologies (automobiles, refrigerators, stoves, and vacuums) in the U.S. from 1930 to 1970. The x-axis represents time, and the y-axis shows the percentage of households using each technology. Each colored line represents one technology.

### ✅ Categorized Statements

**True:**

* In 1945, two out of the four technologies had lower adoption than in 1940.
* In 1930, adoption of automobiles was greater than 50%.
* After 1940, adoption of refrigerators was always higher than adoption of stoves.

**False:**

* After 1940, adoption of automobiles was always higher than adoption of vacuums.
* In 1940, adoption of stoves was greater than adoption of automobiles.
* It took longer for refrigerators to go from 50% adoption to 75% adoption than it took vacuums.

### 🖼️ Visualization Reference

[📷 View line plot](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/3.%20Technology%20Adoption%20Lineplot.png)

---

## 📋 Exercise: Logarithmic Scales for Line Plots

This line plot shows cumulative confirmed COVID-19 cases across six countries from early 2020. The plot uses a logarithmic scale to allow comparisons across countries with widely varying case counts.

### ✅ Correct Interpretation

> On Feb 17, Germany had more cumulative confirmed cases of COVID-19 than France.

### 🖼️ Visualization Reference

[📷 View COVID-19 log-scale line plot](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/4.%20COVID%20Log%20Scale%20Lineplot.png)

---

## 📋 Exercise: Interpreting Bar Plots

This bar plot shows the number of famous athletes in ESPN’s Top 100 list across different countries and sports. By switching views (country, sport, or combined), we can explore category dominance.

### ✅ Correct Interpretation

> Soccer players from the USA had more famous athletes than any other country/sport combination.

### 🖼️ Visualization References

* [📷 Country/Sport Combination](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/5.%20Barplot_Country_Sport.png)
* [📷 Country Only](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/5.%20Barplot_Country.png)
* [📷 Sport Only](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/5.%20Barplot_Sport.png)

---

## 📋 Exercise: Interpreting Stacked Bar Plots

This stacked bar plot shows the percentage of people aged 65+ in England needing assistance with 0, 1, or 2+ daily living activities. Results are separated by gender and age group. Each bar adds up to 100%, enabling easy comparison of dependency levels across subgroups.

### ✅ Correct Interpretation

> The group with the largest percentage of people needing no assistance was men aged 70–74.

### 🖼️ Visualization Reference

[📷 View stacked bar plot](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/6.%20Assistance%20Needs%20Stacked%20Barplot.png)

---

## 📋 Exercise: Interpreting Dot Plots

This dot plot visualizes social media followers (Facebook, Instagram, Twitter) for athletes in ESPN’s 2017 Top 100 list. The data is grouped by sport and sorted alphabetically within each sport. Logarithmic scaling on the x-axis enables clearer comparison across several orders of magnitude.

### ❌ False Statement

> Soccer: Cristiano Ronaldo has more Twitter followers than Marcelo Vieira.

### 🖼️ Visualization Reference

[📷 View dot plot](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/7.%20Athlete%20Social%20Media%20Dotplot.png)

---

## 📋 Exercise: Sorting Dot Plots

This dot plot presents the Big Mac Index as of January 2020: the price of a Big Mac in USD for different countries. It includes both actual price and GDP-adjusted price. The GDP adjustment reflects how affordable a Big Mac is relative to income levels in each country.

By sorting rows by either actual price or adjusted price, different insights can be drawn. Countries with extremely high GDP-adjusted prices appear to have Big Macs that are disproportionately expensive for their residents.

### ✅ Correct Interpretation

> Two countries have Big Macs that cost over 100 USD after adjusting for GDP.

### 🖼️ Visualization References

* [📷 Sorted by Country](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/8.%20Big%20Mac%20Index%20Dotplot_Country.jpg)
* [📷 Sorted by Adjusted Price](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/8.%20Big%20Mac%20Index%20Dotplot_GDP_Adjusted.jpg)
* [📷 Sorted by Actual Price](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/Visualizing%20Two%20Variables/8.%20Big%20Mac%20Index%20Dotplot_Actual.jpg)

---

## 🎯 Learning Outcome

* Recognize when to use scatter plots, box plots, or line charts for two-variable analysis.
* Understand the influence of scale (linear vs. log) on perceived trends.
* Evaluate correlation and causality using visuals.

➡️ All screenshots are stored in the `visuals/` folder, organized by exercise:
[🔗 View visuals folder](https://github.com/VibeHarboe/Understanding-Data-Visualization/tree/main/visuals)
