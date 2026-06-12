# Olist E-Commerce Analytics

## Project Overview

This project analyzes transactional and customer-level data from Olist, one of Brazil’s largest e-commerce marketplaces. The objective was to generate business insights through data visualization, recommendation systems, and market basket analysis.

The project combines Business Analytics and Machine Learning techniques to support data-driven decision-making in an e-commerce environment.

---

## Business Problem

E-commerce companies generate large volumes of customer and transaction data but often struggle to transform that information into actionable business insights.

This project aimed to:

* Improve product recommendations.
* Identify purchasing patterns.
* Support cross-selling opportunities.
* Create interactive dashboards for business users.
* Extract strategic insights from customer behavior.

---

## Dataset

The project uses the Olist Brazilian E-Commerce Dataset, containing information about:

* Customers
* Orders
* Products
* Reviews
* Product Categories

---

## Project Components

### Recommendation System

Implemented Collaborative Filtering techniques:

* User-User Filtering
* Item-Item Filtering
* Cosine Similarity

The objective was to generate personalized product recommendations based on customer purchasing behavior.

---

### Market Basket Analysis

Association Rule Mining was performed using:

* Apriori Algorithm
* FP-Growth Algorithm

The analysis identified frequently purchased product combinations and revealed cross-selling opportunities.

Examples of strong associations included:

* Watches & Gifts ↔ Audio Products
* Stationery ↔ Luggage Accessories
* Bed Bath Table ↔ Home Comfort

---

### Interactive Dashboard

An interactive dashboard was developed using Plotly.

Visualizations included:

* Top Product Categories
* Monthly Order Volume
* Price Distribution
* Orders by Brazilian State
* Customer Review Analysis

The dashboard was designed to support business decision-making through visual storytelling.

---

## Key Business Insights

The analysis demonstrated how recommendation systems and association rules can:

* Increase average basket size.
* Improve customer engagement.
* Support targeted marketing campaigns.
* Enhance product discovery.

Geographic and review analysis also highlighted opportunities for operational and marketing improvements.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Plotly
* Scikit-Learn
* MLxtend
* Jupyter Notebook

---

## Repository Structure

```text
├── notebook.ipynb
├── datasets/
├── report.pdf
└── README.md
```

---

## Author

Felipe Costa

Data Analytics Graduate | Python | SQL | Machine Learning | Data Visualization

Dataset: Olist Brazilian E-Commerce Dataset
