# 🎨 The Color and the Shape

**Course:** Understanding Data Visualization (DataCamp)
**Chapter:** 3 – The Color and the Shape

---

This chapter explores the use of **color**, **shape**, and **grouping** to reveal or emphasize patterns in data visualizations. You’ll learn how aesthetic attributes can encode information and how perceptual best practices enhance interpretability.

---

## 🧠 Key Concepts

* **Color as Encoding**
  Use color to distinguish between categories or represent intensity.

* **Shape to Differentiate Categories**
  Shapes help when color isn't enough or for accessibility.

* **Legibility and Accessibility**
  Avoid misleading palettes; consider colorblind-friendly schemes.

* **Grouping & Faceting**
  Break complex plots into more interpretable subplots using facets (e.g., small multiples).

* **Clarity Over Decoration**
  Ensure that added visuals or style enhance—not distract from—the message.

---

## 📋 Exercise: Another Dimension for Scatter Plots

To distinguish points in a scatter plot based on a third variable, you can use **color**, **shape**, **transparency**, or **panels (faceting)**. This exercise explores the trade-offs in each method, using house price data from Los Angeles County.

### ✅ Correct Interpretation

> Using different shapes provides the best way to distinguish points from each city, but makes it harder to see if there is a single trend across the whole dataset.

### 🖼️ Visualization Reference

[📷 Dimension for Scatter Plots](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/b486e2b2c7099f715fce94181b9a1f44ef4061dc/visuals/The%20color%20and%20the%20shape/Another%20dimension%20for%20scatter%20plots_shape.png)

![Another Dimension for Scatter Plots](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/b486e2b2c7099f715fce94181b9a1f44ef4061dc/visuals/The%20color%20and%20the%20shape/Another%20dimension%20for%20scatter%20plots_shape.png "Another Dimension for Scatter Plots)")

---

## 📋 Exercise: Another Dimension for Line Plots

Line plots can be modified in several ways to distinguish between multiple categories, such as using color, linetype, transparency, or small multiples. This exercise explores how to differentiate five tech companies—Facebook, Apple, Amazon, Microsoft, and Google (FAAMG)—in a time-series stock price plot.

### ✅ Correct Interpretation

> All five companies began 2020 with a higher price than they had halfway through 2019.

### 🖼️ Visualization Reference

[📷 View dropdown and line aesthetics](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/The%20Color%20and%20the%20Shape/2.%20FAAMG%20Line%20Plot%20Dropdown.png)

---

## 📋 Exercise: Eye-Catching Colors

This scatter plot shows the speed of two rodent species (agouti and paca) by time of day, with two versions of the visualization using different color perception strategies. One version uses a perceptually uniform palette, while the other does not—making some data points appear more prominent.

### ✅ Correct Interpretation

> To ensure that all data points are equally perceivable, choose a qualitative, sequential, or diverging scale in hue-chroma-luminance colorspace.

### 🖼️ Visualization References

* [📷 With perceptually uniform colors](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/The%20Color%20and%20the%20Shape/3.%20Equal%20Perception%20Color%20Palette.png)
* [📷 Without perceptually uniform colors](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/The%20Color%20and%20the%20Shape/3.%20Unequal%20Perception%20Color%20Palette.png)

---

## 📋 Exercise: Choosing the Right Color Scale

This exercise demonstrates how different types of color scales—**qualitative**, **sequential**, and **diverging**—are appropriate depending on the structure of the data. Here, student responses to survey questions about math anxiety are shown with answers ranging from "Strongly Disagree" to "Strongly Agree." Since there is a natural midpoint ("Neutral"), a diverging color scale is most appropriate to show deviation from that central value.

### ✅ Correct Interpretation

> Diverging

### 🖼️ Visualization Reference

[📷 View color scale dropdown](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/The%20Color%20and%20the%20Shape/4.%20Color%20Scale%20Dropdown.png)

---

## 📋 Exercise: Highlighting Data

In certain cases, we may want to emphasize specific data points for analytical or storytelling purposes. In this exercise, a dataset of the greatest hip-hop songs of all time is visualized, and songs by The Notorious B.I.G. and 2Pac are highlighted using size, transparency, and chroma.

The technique used allows these two artists to visually stand out against all others.

### ✅ Correct Interpretation

> The Notorious B.I.G. has 9 and 2Pac has 8.

---

## 📋 Exercise: Interpreting Pair Plots

Pair plots are a powerful tool for summarizing multivariate datasets. They simultaneously show distributions of individual variables (on the diagonal) and relationships between pairs (in off-diagonal panels). In this exercise, the Panamanian camera trap dataset includes five animal species—agouti, brocket, coati, paca, and peccary—analyzed for time of day and speed.

### ✅ Correct Interpretation

**True:**

* There are more than 250 sightings of peccary in the dataset.
* Most animals were travelling at less than 1 m/s when caught on camera.
* Paca is the only nocturnal animal in the dataset.

**False:**

* The animal with the fastest 75th percentile speed on camera was an agouti.
* All species were caught on camera most often around dawn (6am) and dusk (6pm).
* There is a strong negative correlation between time of sighting and speed of the animal.

### 🖼️ Visualization References

* ![Pair Plot – Animal Activity](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/The%20Color%20and%20the%20Shape/pairs-animal-activity-new1.png)
* ![Answer Categories](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/The%20Color%20and%20the%20Shape/pairs-animal-activity-new2.png)

---

## 📋 Exercise: Interpreting Correlation Heatmaps

Correlation heatmaps display the pairwise relationships between numeric variables using color intensity. This exercise uses a dataset from a survey on scotch whisky consumption to identify patterns among drinkers of different brands.

### ✅ Correct Interpretation

**True:**

* People who drank Glenfiddich were also likely to drink Glenlivet.
* People who drank The Singleton were unlikely to drink Chivas Regal.
* There was no correlation between drinkers of Clan Macgregor and drinkers of Chivas Regal.

**False:**

* People who drank Knockando were unlikely to drink Macallan.
* There was no correlation between drinkers of Johnnie Walker Red Label and drinkers of Johnnie Walker Black Label.
* People who drank Glenlivet were also likely to drink J & B.

### 🖼️ Visualization References

* ![Correlation Heatmap](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/The%20Color%20and%20the%20Shape/Interpreting%20correlation%20heatmaps_1.png)
* ![Answer Categories](https://github.com/VibeHarboe/Understanding-Data-Visualization/blob/main/visuals/The%20Color%20and%20the%20Shape/Interpreting%20correlation%20heatmaps_2.png)

---

## 🌟 Learning Outcome

* Understand how color and shape communicate categorical variables.
* Apply grouping techniques like faceting for clarity.
* Make aesthetic choices that support clarity, accessibility, and insight.

➡️ All relevant visuals will be stored in the `visuals/` folder and linked per exercise.

