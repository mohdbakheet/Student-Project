# 📦 Repository: Student-Project `sir-covid-fitting`

## 📁 Project Title:

**Modeling and Fitting the SIR Epidemic Model to COVID-19 Case Data**

---

## 📚 Overview

This repository provides a simple and educational implementation of the **SIR compartmental model**, fitted to real or synthetic COVID-19 case data using Python. It is designed as a small student project to demonstrate how mathematical models are used to simulate and interpret epidemic dynamics.

---

## 🧠 Objectives

* Understand the basic structure of the SIR model
* Fit model parameters to real cumulative case data
* Visualize disease spread and estimate the basic reproduction number $R_0$
* Explore intervention effects such as vaccination or isolation

---

## 📂 Folder Structure

```bash
sir-covid-fitting/
├── data/
│   └── covid_data.csv
├── images/
│   └── fitted_plot.png           # generated after running
├── notebooks/
│   └── SIR_Model_Fitting.ipynb  # 💡 Interactive notebook
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📦 Files Explained

### `data/covid_data.csv`

Synthetic or real COVID-19 cumulative case data for a small population:

```csv
day,cases
0,1
1,3
2,7
3,15
4,30
5,50
6,80
7,120
8,170
9,230
10,290
11,360
12,420
13,480
14,540
15,600
```

---

### `notebooks/SIR_Model_Fitting.ipynb`

A Jupyter notebook that:

* Loads the data
* Defines the SIR model
* Fits model parameters to the data
* Plots the results

---

### `requirements.txt`

Dependencies to install via:

```bash
pip install -r requirements.txt
```

```txt
numpy
pandas
scipy
matplotlib
notebook
```

---

## 📘 README.md (suggested contents)

````markdown
# 🧪 SIR COVID-19 Model Fitting

This project simulates the spread of an epidemic using the SIR model and fits it to actual or synthetic COVID-19 cumulative case data.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/sir-covid-fitting.git
cd sir-covid-fitting
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the notebook

```bash
jupyter notebook notebooks/SIR_Model_Fitting.ipynb
```

## 📈 Output

The notebook generates a plot comparing the observed case data and the fitted SIR curve. It also estimates the basic reproduction number $R_0 = \beta/\gamma$.

## 🧩 Try This

* Modify `covid_data.csv` with real data
* Change population size `N`
* Try different fitting intervals (e.g., before and after interventions)
* Add vaccination or policy effect terms

## 📚 References

* [SIR Model – Wikipedia](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SIR_model)
* [Johns Hopkins COVID-19 Data](https://github.com/CSSEGISandData/COVID-19)

## 📄 License

MIT License

```
