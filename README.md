

# Hotel Booking Demand – Data Visualization Project

This repository contains the complete data-visualization workflow and analysis for the **Hotel Booking Demand Dataset**, combining records from a resort hotel (H1) and a city hotel (H2).
The project focuses on **descriptive analytics**, exploring booking patterns, cancellations, seasonality, customer types, market segmentation, and more.

The analysis is implemented in the Jupyter Notebook **Final code.ipynb**, supported by the project’s **proposal** and **final report**.

---

## 📊 Project Overview

The dataset consists of:

* **119,390 total bookings**
* **31 attributes** describing each reservation
* **Two hotels:**

  * **H1** – Resort hotel (40,060 observations)
  * **H2** – City hotel (79,330 observations)
* Booking dates: **July 2015 → August 2017**
* Includes both **arrived** and **canceled** bookings
* All personal identifiers removed (real business dataset)

The project focuses on understanding booking behavior through **descriptive data visualization**, helping hotel stakeholders improve:

* Demand forecasting
* Cancellation mitigation
* Revenue strategies
* Customer segmentation
* Seasonal planning

---

## 📚 Key Questions Answered

We designed and implemented visualizations to answer the following:

1. **Which months have the highest Average Daily Rate (ADR)?**
2. **Which seasons have the most bookings and cancellations?**
3. **Which months have the highest checkout frequency?**
4. **Market segmentation distribution**
5. **Meal plan distribution (BB, HB, FB, SC)**
6. **Cancellation behavior by customer type & deposit type (stacked bar)**
7. **Comparison between Europeans vs. Non-Europeans**
8. **Cancellation rate by region and country (sunburst)**
9. **Impact of season on country-level cancellations**
10. **Number of adults by company (Tree map)**
11. **Customer type vs. number of adults & children (Tree map)**
12. **Countries with the highest bookings & cancellations (Tree map)**
13. **Word cloud of countries of origin**

---

## 📈 Visualization Techniques Used

We utilized several visualization idioms:

* **Pie Charts**
* **Bar Charts & Stacked Bars**
* **Line Charts**
* **Tree Maps**
* **Icicle Plot**
* **Sunburst Chart**
* **Interactive Pie Charts (Plotly)**
* **Word Cloud**

Libraries used include:

* `pandas`
* `plotly.express`
* `plotly.graph_objects`
* `matplotlib`
* `wordcloud`
* `numpy`

---

## 📁 Repository Structure

```
├── Final code.ipynb        # Main data visualization notebook
├── Final_Report.pdf        # Full final report
├── Intial_Proposal.pdf     # Initial project proposal
└── README.md               # Project documentation (this file)
```

---

## ⚙️ Quick Start

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/hotel-booking-visualization.git
cd hotel-booking-visualization
```

### 2️⃣ Install Requirements

If using a `requirements.txt`:

```bash
pip install -r requirements.txt
```

If not, install dependencies manually:

```bash
pip install pandas numpy plotly matplotlib wordcloud
```

### 3️⃣ Run the Notebook

```bash
jupyter notebook "Final code.ipynb"
```

Follow the cells to:

* Load and clean the dataset
* Explore business terminology (ADR, market segments, customer type, etc.)
* Generate all visualizations with explanations
* Interpret results for real business insights

---

## 🚀 How to Use the Notebook Quickly

If you only want to run the visualizations immediately:

1. Open **Final code.ipynb**
2. Run all cells (`Kernel → Restart & Run All`)
3. Scroll through the generated charts
4. Reference insights explained in the final report

---

## 🧠 Insights Gained (Summary)

* **August** has the highest ADR and checkout rates.
* **Summer** receives the most bookings.
* **Winter** suffers the highest cancellation rate.
* **Transient customers** cancel the most and often leave *no deposit*.
* **Europe** provides the largest customer base.
* **Portugal** has the highest cancellation rates inside the EU.
* **Most guests choose “BB” (Bed & Breakfast)** meal type.
* Children percentages vary significantly by season and month.

These insights can guide **pricing**, **marketing**, **seasonal planning**, and **deposit policies**.

---

## 🤝 Team Members

* **Rajab** — Q1, Q3, Q4
* **Diaa** — Q6, Q7, Q13
* **Yusuf** — Q2, Q10, Q11, Q12
* **Ziad** — Q5, Q8, Q9

---

