
# Customer Purchase Behavior Analysis

## 📌 Introduction

This project analyzes **online customer behavior during November and December**, the busiest shopping months. It provides actionable insights for **Product Managers** and stakeholders, focusing on:

* **Customer Segmentation** → Distinguishing between returning vs. new customers.
* **KPI Tracking** → Purchase rates, session behaviors, and correlations across page types.
* **Campaign Impact Analysis** → Estimating likelihood of achieving sales targets after boosting conversion rates.
* **Data-Driven Decisions** → Using statistical models to guide marketing and product strategy.

The goal is to equip Product Managers with insights that directly inform **conversion optimization, customer engagement strategies, and ROI forecasting**.

---

## 📑 Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [PM-Oriented Features](#pm-oriented-features)
4. [Dependencies](#dependencies)
5. [Configuration](#configuration)
6. [Examples](#examples)
7. [Troubleshooting](#troubleshooting)
8. [Contributors](#contributors)
9. [License](#license)

---

## ⚙️ Installation

Clone the repository and install required dependencies:

```bash
git clone https://github.com/your-username/customer-behavior-analysis.git
cd customer-behavior-analysis
pip install -r requirements.txt
```

---

## 🚀 Usage

Run the analysis script:

```bash
python analysis.py
```

Outputs include:

```python
purchase_rates = {
    "Returning_Customer": 0.254,
    "New_Customer": 0.276
}

top_correlation = {
    "pair": ("x_duration", "y_duration"),
    "correlation": 0.345
}

prob_at_least_100_sales = 0.872
```

---

## 🎯 PM-Oriented Features

* **Customer Insights**: Identify purchase behavior differences between *returning* and *new customers*.
* **Behavioral Correlations**: Discover which user actions drive engagement and conversion (e.g., time on product pages vs. cart).
* **Campaign Simulation**: Forecast the likelihood of hitting sales targets under new marketing strategies.
* **Data Storytelling**: Convert statistical outputs into insights suitable for executive reporting.
* **Decision Support**: Provide evidence-based recommendations for prioritizing campaigns and UX improvements.

---

## 📦 Dependencies

* Python 3.8+
* pandas
* numpy
* matplotlib
* scipy

---

## 🔧 Configuration

Update `config.yaml` to:

* Define dataset paths.
* Adjust boost percentages for campaigns.
* Enable or disable visualizations (useful for PM dashboards).

---

## 📊 Examples

Example analysis results:

```python
purchase_rates = {"Returning_Customer": 0.254, "New_Customer": 0.276}
top_correlation = {"pair": ("Product_Page_Duration", "Cart_Duration"), "correlation": 0.345}
prob_at_least_100_sales = 0.872
```


---

## 🛠 Troubleshooting

* **Dataset missing** → Confirm correct path in `config.yaml`.
* **Charts not visible** → Enable visualization and confirm `matplotlib` is installed.
* **Unexpected results** → Double-check campaign boost assumptions.

