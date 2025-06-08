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

[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/c8b8d64ea51a309826fc98cf263d17ff68b05da9/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/Pie%20plots.png)

![Pie vs Bar Plot – Alcohol Consumption](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/c8b8d64ea51a309826fc98cf263d17ff68b05da9/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/small/Pie%20plots_smalll.jpg "Pie vs Bar Plot – Alcohol Consumption)")

---

## 🌬️ Exercise: Rose Plots

**Rose plots** (polar histograms) are useful when visualizing circular data such as compass directions. The exercise presents wind direction data recorded every 10 minutes over an eight-month period using a meteorological mast. Knowing predominant wind directions is crucial for both weather modeling and optimizing wind turbine placement.

### ✅ Correct Interpretation
> **The predominant wind directions were N and SW.**

### 🖼️ Visualization Reference

[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/6c1bd129bd7d14d0073808ccc95ce7797909ccf5/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/Rose-plots.png)

![Rose plots – Wind direction](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/6c1bd129bd7d14d0073808ccc95ce7797909ccf5/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/small/Rose-plots_small.png "Rose plots – Wind direction)")

---

## 📉 Exercise: Bar Plot Axes

**Bar plots** are a powerful tool for visualizing categorical data. However, not including zero on the y-axis can mislead viewers, because we naturally compare bar lengths to interpret magnitude. In this exercise, you're comparing two versions of a stacked bar plot about asthma prevalence across age groups. Including zero provides a clearer and more honest representation.

### ✅ Correct Interpretation
> The percentage of asthmatics is less than 15% for every age group.

### 🖼️ Visualization Reference

[📷 Exclude Zero On Y-Axis](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/3ed3ba2540a1943add8e85982a3d5d0ceadd6d86/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/exclude%20zero%20on%20y-axis..png)

![Exclude Zero On Y-Axis](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/3ed3ba2540a1943add8e85982a3d5d0ceadd6d86/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/exclude%20zero%20on%20y-axis..png "Exclude Zero On Y-Axis)")

[📷 Include Zero On Y-Axis](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/3ed3ba2540a1943add8e85982a3d5d0ceadd6d86/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/Include%20zero%20on%20y-axis..png)

![Include Zero On Y-Axis](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/3ed3ba2540a1943add8e85982a3d5d0ceadd6d86/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/Include%20zero%20on%20y-axis..png "Include Zero On Y-Axis)")

---

## 📉 Exercise: Dual Axes

Using **dual y-axes** is a widely discouraged practice in data visualization. While it might seem like a handy way to show two variables with different scales on the same plot, it introduces a major risk: you can manipulate the visual appearance to imply misleading correlations.

**This exercise displays the stock prices of Microsoft (MSFT) and Amazon (AMZN) from 2017–2020. Prices are adjusted for splits and dividends, but not scaled relative to each other. Sliders allow you to adjust the vertical position (+) and steepness (*) of the AMZN line.

### ✅ Correct Interpretation
> You can't make a conclusion about the correlation of MSFT and AMZN from this plot.

### 🖼️ Visualization Reference
Dual Axes – MSFT vs. AMZN

[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/0ddfae49a40b0a1223845d249d514ed25e9028f3/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/Dual%20axes.png)

![Dual Axes – MSFT vs. AMZN](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/0ddfae49a40b0a1223845d249d514ed25e9028f3/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/Dual%20axes.png "Dual Axes – MSFT vs. AMZN)")

---

## 💥 Exercise: Chartjunk

**Chartjunk** refers to all unnecessary or distracting elements in a visualization that do not improve the viewer’s understanding of the data. In fact, they often obscure insight and clarity.

This exercise revisits the scatter plot of critically acclaimed hip-hop songs over time (from Chapter 2), but now it's overloaded with stylistic noise—gold backgrounds, dollar signs, thick grid lines, and more.

### ✅ Correct Interpretation
> All visual elements — chunky grid lines, dollar symbols, bold/italic labels, and gold backgrounds—are considered chartjunk.

### 🖼️ Visualization Reference
Chartjunk – Hip-Hop Song Timeline

[📷 View on GitHub](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/3ed3ba2540a1943add8e85982a3d5d0ceadd6d86/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/Chartjunk_scatter-hiphop-bling-new.png)

![Chartjunk – Hip-Hop Song Timeline](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/3ed3ba2540a1943add8e85982a3d5d0ceadd6d86/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/Chartjunk_scatter-hiphop-bling-new.png "Chartjunk – Hip-Hop Song Timeline)")

---

## 🏛️ Exercise: Multiple Plots – German Bundesrat Coalition Analysis

To understand **complex datasets**, it's often necessary to present multiple visualizations that work together as a dashboard. This exercise explores political coalitions in the German Bundesrat (Federal Council) using a collection of map and bar plots.

*Each of the three subplots in the dashboard offers a distinct lens:*
* **Map plot by party:** Shows which party holds seats in which German states.
* **Bar plot by party:** Breaks down the number of seats each party holds based on their coalition role (primary, secondary, or tertiary).
* **Bar plot by coalition:** Shows the total seats held by combinations of parties forming coalitions.

*Transparency in the bar plot encodes party influence:*
* **Primary party:** Fully opaque
* **Secondary party:** Semi-transparent
* **Tertiary party:** Very transparent

### ✅ Correct Interpretation
> The SPD have more seats as the tertiary party in a coalition than any other party.

### 🖼️ Visualization References

[📷 Bar plot by coalition](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/3ed3ba2540a1943add8e85982a3d5d0ceadd6d86/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/bar_coalition.png)

[📷 Bar plot by party](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/3ed3ba2540a1943add8e85982a3d5d0ceadd6d86/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/bar_plot_per_party.png)

[📷 Map plot by party](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/3ed3ba2540a1943add8e85982a3d5d0ceadd6d86/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/map_plot_per_party.png)

![Multiple Plots](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/be0d01688ab6d40894fe9c5fd358d6c4d141f1b7/visuals/99%20Problems%20But%20a%20Plot%20Ain't%20One/Multiple%20Plots.png "Multiple Plots)")

---

➡️ All screenshots are stored in the `visuals/` folder, organized by exercise:
[🔗 View visuals folder](https://github.com/VibeHarboe/Understanding-Data-Visualization/tree/0de94805beccf07c115c5180be3355206ca0c99d/visuals)
