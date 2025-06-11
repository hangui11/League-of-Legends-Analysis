# League of Legends Champion Analysis (R)
>note Final Project of Multivariate Analysis in MDS
This project analyzes detailed information on **167 League of Legends champions** using advanced statistical techniques in **R**. The main objective is to determine the **best champion for each role** — Top, Jungle, Mid, Bottom, and Support — based on their base and growth statistics.

---

## 🎮 About the Game

League of Legends is a globally renowned **PvP (Player vs Player)** game, structured around 5 key in-game roles:

* **Top**
* **Jungle**
* **Mid**
* **Bottom (ADC)**
* **Support**

Each champion is typically suited for one or more of these roles, with unique mechanics and attributes that define their performance and scaling across the game.

---

## 📊 Dataset Overview

* **Champions**: 167
* **Attributes**:

  * Initial statistics (e.g., health, attack damage, armor, speed)
  * Growth per level (e.g., health growth, attack growth)
  * Assigned roles

This dataset enables rich multivariate statistical exploration.

---

## 🎯 Project Objective

The goal is to identify **champions with the best performance in each role** using data-driven insights. The analysis leverages both **quantitative measures** and **dimensionality reduction techniques**.

---

## 🧪 Analytical Methods (in R)

The analysis was conducted entirely in **R**, using the following statistical methods:

* 📌 **Exploratory Data Analysis (EDA)**: Summary statistics, boxplots, histograms
* 📈 **Principal Component Analysis (PCA)**: To reduce dimensionality and interpret structure
* 🗺️ **Multidimensional Scaling (MDS)**: To visualize similarities between champions
* 🔢 **Multiple Correspondence Analysis (MCA)**: To explore categorical associations
* 🧬 **Cluster Analysis**: To group similar champions
* 🧠 **Discriminant Analysis**: To classify champions based on role or cluster

All methods were used to uncover patterns in champion behavior and performance, especially across roles.

---

## 📦 Tools & Technologies

* **R**

  * `ggplot2`, `FactoMineR`, `factoextra`, `cluster`, `MASS`, `dplyr`, `tidyverse`

---

## 📁 Project Structure

```
/League-of-Legends-Analysis
│
├── Lol_champions.csv       # Dataset file
├── Project.rmd             # R markdown for analysis
├── Project.pdf/            # PDF summary
└── README.md               # This file
```
