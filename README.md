<p align="center">
  <sub>DATA EXPLORATION · VISUAL COMMUNICATION · R PROGRAMMING</sub>
</p>

<h1 align="center">Hourly Weather Analysis</h1>

<p align="center">
  <em>Turning hourly observations into visual questions worth exploring.</em>
</p>

<p align="center">
  Academic data-analysis project
  <br>
  R / Statistical Graphics / Exploratory Analysis
</p>

<p align="center">
  <a href="#exploring-the-data"><strong>Explore the visualizations ↓</strong></a>
  &nbsp; · &nbsp;
  <a href="#inside-the-repository">Browse the analysis</a>
  &nbsp; · &nbsp;
  <a href="https://www.sandesh.design/">My portfolio ↗</a>
</p>

<br>

## Different questions need different views.

Hourly weather records contain several dimensions of information: temperature, humidity, pressure, wind, and visibility.

This academic project explores that information through R visualizations, including comparisons between JFK and LaGuardia airport observations.

The work uses different chart forms to examine distributions, relationships, and changes over time. These are exploratory views of recorded data—not evidence of a validated forecasting system.

<br>

## Exploring the data

### 01 / Relationships
**How do two measurements vary together?**

A scatterplot places dew point and humidity in the same view, making their observed relationship available for inspection.

![Scatterplot comparing dew point and humidity](https://github.com/SandeshKey/Hourly-Weather-Analysis-with-R-Programming/assets/98152515/b34db60f-fce6-442f-b7c7-6264e7ba957b)

**Reading the view:** look for the shape, spread, and concentration of observations. An association does not, by itself, establish causation.

---

### 02 / Distributions
**What does the range of observations look like?**

A histogram groups humidity observations into intervals, providing a view of how frequently different values occur.

![Histogram showing the distribution of humidity observations](https://github.com/SandeshKey/Hourly-Weather-Analysis-with-R-Programming/assets/98152515/8f66488f-97e1-4db4-bb8c-2c85bfa12ec4)

**Reading the view:** consider the bin widths and frequency scale alongside the overall shape. Different bin choices can change the apparent pattern.

---

### 03 / Change over time
**How do monthly temperature patterns compare?**

A line chart presents average temperature by month for JFK and LaGuardia, bringing the two series into a shared temporal view.

![Line chart comparing monthly average temperatures at JFK and LaGuardia](https://github.com/SandeshKey/Hourly-Weather-Analysis-with-R-Programming/assets/98152515/c9cb00f7-81b7-49db-9297-5c88f5231d51)

**Reading the view:** monthly averages summarize the observations. They do not show the full variation within each month.

---

### 04 / Comparisons
**How do summaries differ across locations and months?**

A bar chart compares monthly dew-point summaries for the two airports.

![Bar chart comparing monthly dew-point summaries at JFK and LaGuardia](https://github.com/SandeshKey/Hourly-Weather-Analysis-with-R-Programming/assets/98152515/5ed769aa-9fcd-44eb-b4d3-67209da0cb34)

**Reading the view:** check the grouping, units, and axis baseline before comparing values.

<br>

## The visual communication perspective

This project complements my interface work through a related concern: making information easier to examine.

**Choose a view that fits the question.**  
Relationships, distributions, and temporal patterns require different visual structures.

**Keep aggregation visible.**  
A monthly average and an individual hourly observation represent different levels of detail.

**Separate observation from interpretation.**  
A chart can reveal a pattern worth investigating without proving an explanation or supporting a prediction.

These principles provide a useful lens for reviewing the analysis and improving future visualizations.

<br>

## Inside the repository

| File | Purpose |
| :--- | :--- |
| [`Weather_Analysis_R.R`](Weather_Analysis_R.R) | R analysis script |
| [`Hourly Weather Data.csv`](Hourly%20Weather%20Data.csv) | Dataset included with the project |
| [`Hourly Weather Analysis.Rproj`](Hourly%20Weather%20Analysis.Rproj) | RStudio project file |

The original analysis also includes views of pressure, visibility, wind direction, and additional weather-variable comparisons.

<br>

<details>
<summary><strong>Additional visualizations</strong></summary>

<br>

### Monthly pressure

![Line chart comparing monthly average pressure at the two airports](https://github.com/SandeshKey/Hourly-Weather-Analysis-with-R-Programming/assets/98152515/7c49c232-5e3b-4757-a25d-2e16b6e09a8c)

### Airport visibility

![Time-series visualization of airport visibility at JFK and LaGuardia](https://github.com/SandeshKey/Hourly-Weather-Analysis-with-R-Programming/assets/98152515/dbea2a48-6a0e-4ff2-aec0-50c397afc37f)

### Wind direction

![Polar bar chart showing the distribution of wind direction](https://github.com/SandeshKey/Hourly-Weather-Analysis-with-R-Programming/assets/98152515/e6d548b3-544f-4f6f-9f33-4e513e4e2bc9)

These images are retained from the original project. Consult the analysis script and dataset when examining their calculations and interpretation.

</details>

<br>

<details>
<summary><strong>Reproducing the analysis</strong></summary>

<br>

Suggested inspection sequence:

1. Open `Hourly Weather Analysis.Rproj` in RStudio.
2. Review `Weather_Analysis_R.R` before executing it.
3. Identify and install the packages used by the script.
4. Check that dataset paths resolve to your local copy.
5. Inspect column names, units, missing values, and data types.
6. Run the analysis in sections and compare the outputs with the documented figures.

Start from a clean R session rather than relying on a previously saved workspace.

**Current verification status:** the analysis has not yet been rerun in a clean environment for this documentation update. Package compatibility and reproducibility remain to be checked.

</details>

<br>

<details>
<summary><strong>Scope & interpretation</strong></summary>

<br>

This is an academic exploratory-analysis project.

The visualizations should be interpreted in the context of their source data, transformations, aggregation choices, and missing-value handling.

The repository is not presented as a validated weather-forecasting model, a causal study, or evidence of operational aviation outcomes.

Before reusing the dataset, verify its original provenance, variable definitions, and usage terms.

</details>

<br>

---

<p align="center">
  <strong>Part of Sandesh Subedi’s analytical and design practice.</strong>
</p>

<p align="center">
  <a href="https://www.sandesh.design/">Portfolio</a>
  &nbsp; · &nbsp;
  <a href="https://www.linkedin.com/in/sandeshxd/">LinkedIn</a>
  &nbsp; · &nbsp;
  <a href="mailto:subedi.38@wright.edu">Get in touch</a>
</p>
