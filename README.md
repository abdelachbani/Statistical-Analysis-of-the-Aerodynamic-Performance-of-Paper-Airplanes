
# Statistical Analysis of the Aerodynamic Performance of Paper Airplanes
### An Experimental Study Using Statgraphics Centurion

**Authors:** Abdelkarim Achbani Abid, Daniel Muñoz Ortega  

> [!NOTE]
> This summary is written in English, but the full research paper is in **Spanish**. All information presented here is a very short summary of the provided research documents.

---

## Abstract

This study presents a comprehensive statistical analysis of paper airplane flight performance based on 108 launches conducted under a full factorial experimental design. The primary objective was to identify the optimal experimental conditions to maximize the average distance traveled. The analysis began with descriptive statistics, which revealed a positive skew in the raw distance data. To meet the normality assumptions required for subsequent analyses, a fourth-root transformation was applied to the distance variable.

Both Analysis of Variance (ANOVA) and multiple regression methods were employed. The ANOVA revealed that the most critical factors influencing flight distance were the **airplane model** and **paper thickness**. Furthermore, a significant interaction was found between the launching arm and the student performing the launch. The regression analysis confirmed these findings and provided a predictive model identifying quadratic effects for paper thickness, launch height, and wing area as most relevant.

The study concludes that the optimal strategy to maximize flight distance involves using the most aerodynamic design (Model A) with heavy paper, launched from the greatest available height. The results from both ANOVA and regression analyses were highly consistent, providing robust support for the conclusions.

---

## Experimental Design

The experiment was structured as a full factorial design considering five factors with multiple levels, resulting in a total of 108 unique launches.

| Factor              | Levels                                                 |
| ------------------- | ------------------------------------------------------ |
| **Airplane Model** | 3 Levels: A (Dardo), B (The Basic), C (Lock Bottom)    |
| **Paper Thickness** | 3 Levels: 80 g/m², 185 g/m², 300 g/m² (cardstock)       |
| **Launching Arm** | 2 Levels: Right, Left                                  |
| **Launch Height** | 3 Levels: Sitting, Standing, On a chair                |
| **Launcher** | 2 Levels: Student 1, Student 2                         |

---

## Methodology

The core of this work is a rigorous statistical analysis to understand the factors affecting paper airplane flight distance. The key methods include:

* **Descriptive Statistics:** Initial analysis of the data's distribution, shape, and central tendency. It was noted that the distribution had a positive skew.
* **Data Transformation:** To correct for the lack of normality in the original data, a **fourth-root transformation (`Distancia^1/4`)** was applied to the response variable. This successfully normalized the residuals for the analysis.
* **Analysis of Variance (ANOVA):** A multi-factor ANOVA was performed to identify which factors and interactions had a statistically significant effect on flight distance.
* **Multiple Linear Regression:** A regression model was developed to predict flight distance and quantify the contribution of each significant variable.
* **Model Validation:** The study includes a thorough validation of the statistical models, checking for normality of residuals and homogeneity of variances (homoscedasticity).

---

## Key Findings & Optimal Conditions

The analysis successfully identified the factors that maximize flight distance.

### Significant Factors:
* The **airplane model** and **paper thickness** were the most significant main effects.
* The launching arm by itself was not significant, but the **interaction between the launching arm and the specific launcher** was highly significant. This implies that the optimal launching arm depends on the individual's technique.

### Optimal Conditions for Maximum Flight Distance:
Based on the final ANOVA and regression models, the ideal conditions are:

* **Model:** Model A (Dardo)
* **Paper Thickness:** 300 g/m² (the heaviest paper)
* **Launch Height:** On a chair (the highest position)
* **Launch Technique:** Left arm, when performed by "Alumno 2" (due to the significant interaction effect)

---

## Structure of the Report

The full paper is divided into three parts in the same pdf file, so you'll find the cover 3 times in the document, and separated indexes for each part, with page numbers restarting for each one.

* **First Part:** Contains the introduction, a detailed description of the dataset, initial descriptive statistics, and an analysis of the data's underlying distribution.
* **Second Part:** Presents the in-depth Analysis of Variance (ANOVA), including the study of simple and interaction effects, hypothesis testing, and the validation of the model's assumptions.
* **Third Part:** Details the multiple linear regression analysis, compares the results of the ANOVA and regression models, determines the optimal operating conditions, and provides a final summary and conclusion.
