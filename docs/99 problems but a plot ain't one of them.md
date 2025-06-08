# 📊 99 Problems But a Plot Ain't One

**Course:** Understanding Data Visualization (DataCamp)
**Chapter:** 4 – 99 Problems But a Plot Ain't One

---

This chapter focuses on recognizing and avoiding **common mistakes in data visualization**. You’ll learn how to improve the readability, accuracy, and effectiveness of your plots by avoiding misleading design choices and choosing appropriate visual forms for your data.

---

## 🧠 Key Concepts

* **Chartjunk**
  Avoid unnecessary decorations, 3D effects, and clutter that distract from the message.

* **Mismatched Axes & Scales**
  Ensure axes reflect appropriate starting points and scale units.

* **Choosing the Right Plot Type**
  Match the chart to your variable types and analysis goals.

* **Color Misuse**
  Use perceptually accurate palettes that do not mislead or obscure information.

* **Overplotting & Misleading Aggregation**
  Be cautious of binning, stacking, or summarizing that can distort the interpretation.

---

## 📋 Exercise: Pie Plots

**Pie plots** convert bar data into circular segments but are harder for humans to interpret due to the difficulty in perceiving angles compared to lengths. This exercise uses alcohol consumption data from the Health Survey for England. Each age group is shown as a pie chart and a bar chart for better comparison.

### ✅ Correct Interpretation

> All age groups had at least 50% of people drinking up to 14 units per week.

### 🖼️ Visualization Reference

[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg)

![Pie vs Bar Plot – Alcohol Consumption](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg "Pie vs Bar Plot – Alcohol Consumption)")

---

## 🌬️ Exercise: Rose Plots

**Rose plots** (polar histograms) are useful when visualizing circular data such as compass directions. The exercise presents wind direction data recorded every 10 minutes over an eight-month period using a meteorological mast. Knowing predominant wind directions is crucial for both weather modeling and optimizing wind turbine placement.

### ✅ Correct Interpretation
> **The predominant wind directions were N and SW.**

### 🖼️ Visualization Reference

[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg)

![Rose plots – Wind direction](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg "Rose plots – Wind direction)")

---

## 📉 Exercise: Bar Plot Axes

**Bar plots** are a powerful tool for visualizing categorical data. However, not including zero on the y-axis can mislead viewers, because we naturally compare bar lengths to interpret magnitude. In this exercise, you're comparing two versions of a stacked bar plot about asthma prevalence across age groups. Including zero provides a clearer and more honest representation.

### ✅ Correct Interpretation
> The percentage of asthmatics is less than 15% for every age group.

### 🖼️ Visualization Reference

[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg)

![Bar Plot Axes](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg "Bar Plot Axes)")

---

## 📉 Exercise: Dual Axes

Using **dual y-axes** is a widely discouraged practice in data visualization. While it might seem like a handy way to show two variables with different scales on the same plot, it introduces a major risk: you can manipulate the visual appearance to imply misleading correlations.

**This exercise displays the stock prices of Microsoft (MSFT) and Amazon (AMZN) from 2017–2020. Prices are adjusted for splits and dividends, but not scaled relative to each other. Sliders allow you to adjust the vertical position (+) and steepness (*) of the AMZN line.

### ✅ Correct Interpretation
> You can't make a conclusion about the correlation of MSFT and AMZN from this plot.

### 🖼️ Visualization Reference
Dual Axes – MSFT vs. AMZN

[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg)

![Dual Axes – MSFT vs. AMZN](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg "Dual Axes – MSFT vs. AMZN)")

---

## 💥 Exercise: Chartjunk

**Chartjunk** refers to all unnecessary or distracting elements in a visualization that do not improve the viewer’s understanding of the data. In fact, they often obscure insight and clarity.

This exercise revisits the scatter plot of critically acclaimed hip-hop songs over time (from Chapter 2), but now it's overloaded with stylistic noise—gold backgrounds, dollar signs, thick grid lines, and more.

### ✅ Correct Interpretation
> All visual elements — chunky grid lines, dollar symbols, bold/italic labels, and gold backgrounds—are considered chartjunk.

### 🖼️ Visualization Reference
Chartjunk – Hip-Hop Song Timeline

[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg)

![Chartjunk – Hip-Hop Song Timeline](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/69fede89eb1265976ba758ea365746a13915545f/visuals/Visualizing%20Distributions/Interpreting%20histograms.jpg "Chartjunk – Hip-Hop Song Timeline)")

---



---

🧰 All relevant visuals will be stored in the `visuals/` folder and linked per exercise.
