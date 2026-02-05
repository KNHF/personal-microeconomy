## 🧠 Personal Micro-Economy & Risk Engine

### Modelling Daily Behaviour as a Stochastic System Using Python

---

## 📌 Project Overview

This project models daily life as a dynamic system where time, energy, money, and focus are treated as constrained resources.
Instead of building a simple tracking dashboard, the project focuses on:

* structured data collection
* mathematical metric construction
* time-series analysis
* behavioural variability and risk
* simulation-based scenario analysis

The goal is to demonstrate a reproducible analytical workflow similar to real-world data science and quantitative research environments.

---

## 🎯 Objectives

* Develop strong Python and numerical computing skills
* Apply mathematical thinking to behavioural data
* Build a reproducible analytical pipeline from scratch
* Analyse patterns, uncertainty, and variability over time
* Practise structured project development using Git & GitHub

---

## 📊 Data Description

Daily observations are recorded in a structured CSV file.

Variables include:

* sleep_hours — hours of sleep
* study_hours — daily study time
* gym — binary indicator (1 = yes, 0 = no)
* spend_total — daily spending
* focus_score — subjective productivity rating (1–10)
* stress_score — subjective stress rating (1–10)
* notes — contextual information

Each row represents one day of observations.

---

## 🧮 Methodology

### 1. Data Collection

Daily structured logging creates a time-indexed dataset:

[
x_t = [sleep_t, study_t, gym_t, spend_t, focus_t, stress_t]
]

---

### 2. Exploratory Analysis

* time-series visualisation
* rolling statistics
* distribution analysis
* correlation exploration

---

### 3. Metric Construction

Custom metrics are defined using mathematical formulations, such as productivity or energy proxies.

---

### 4. Risk & Variability Analysis

* rolling variance
* behavioural volatility
* downside performance
* distribution comparison

---

### 5. Scenario Simulation

Using NumPy-based simulations to explore “what-if” behavioural changes.

Examples:

* increased sleep
* reduced spending
* altered study schedules

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Lab
* Git & GitHub

---

## 📁 Repository Structure

```
data/
  raw/
notebooks/
src/
outputs/
README.md
```

---

## 🚀 Skills Demonstrated

* Data pipeline design
* Exploratory data analysis
* Mathematical modelling
* Time-series analysis
* Simulation and scenario modelling
* Version control and reproducibility

---

## 📌 Project Status

Active development with daily data collection and incremental improvements.

---

## 📈 Future Improvements

* predictive modelling
* optimisation experiments
* automated reporting
* modular analysis scripts
