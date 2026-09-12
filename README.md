# Basketball-Momentum-Analysis
Analyse of the 2024 Olympic basketball final using R and localScore.
# Basketball Momentum Analysis: Olympic Games 2024 Final (France vs. USA)

This repository contains the statistical analysis and data science project developed during my research internship at the **Institut de Mathématiques de Toulouse (IMT)** in January 2025. 

The project investigates the concept of **"momentum"** in basketball by analyzing possession duration, scoring dynamics, and game flow during the men's basketball final of the Paris 2024 Olympic Games.

## Project Overview
* **Context:** Research internship at IMT.
* **Match Analyzed:** Men's Olympic Final – France vs. USA.
* **Key Objective:** Quantify possession duration, identify critical turning points (specifically the second quarter), and apply the `localScore` statistical package to detect momentum shifts.

## Tech Stack & Libraries
* **Language:** R
* **Data Manipulation & Analysis:** `dplyr`, `readxl`, `localScore`
* **Data Visualization:** `ggplot2`, `cowplot`

## Key Findings & Insights
1. **Possession Dynamics:** The American team's strategy relied heavily on shorter, highly repetitive, and efficient offensive possessions compared to the French team.
2. **The Turning Point:** Statistical breakdown of the quarters highlights the **2nd quarter (Q2)** as the critical inflection point where the US established a lead that France could not recover from.
3. **Statistical Modeling:** Utilization of the `localScore` algorithm and Lindley processes to model score evolution and detect momentum breaks throughout the match.

## Repository Structure
```text
├── data/                  # Raw and processed datasets (anonymized/subset)
├── outputs/               # Generated plots and exported figures
├── src/                   # R scripts and RMarkdown reports (`AnalyseJO2024.Rmd`)
└── README.md


