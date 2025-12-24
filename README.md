# **BMW Worldwide Sales Dashboard**

*Interactive Business Intelligence Dashboard – Power BI*

---

## **Project Overview**

This repository hosts a **fully interactive Power BI dashboard** analyzing BMW worldwide sales data from 2010 to 2024. The dashboard provides a comprehensive view of global sales trends, top-performing models, regional performance, fuel and transmission preferences, vehicle color popularity, and other key market insights.

It is designed to help users **quickly explore patterns, identify high- and low-performing segments, and gain actionable insights** through interactive visuals, KPIs, and filters.

---

## **Dataset**

* **Source:** Kaggle – BMW Worldwide Sales Records (2010–2024)
* **Size:** 50,000+ records
* **Key Features:** Model, Year, Region, Color, Fuel_Type, Transmission, Engine_Size_L, Mileage_KM, Price_USD, Sales_Volume

> All dataset files used in the dashboard are included in the `data/` folder.

---

## **Dashboard Features**

* **KPI Cards:** Total Sales, Total Revenue, Average Price, Average Mileage
* **Sales Trend Analysis:** Yearly sales and revenue trends
* **Regional Analysis:** Sales performance by region on a map
* **Top Models:** Top 10 models by sales volume
* **Sales Classification:** High vs Low sales overview using treemaps
* **Fuel & Transmission Analysis:** Distribution across fuel types and transmission
* **Color Popularity:** Donut chart showing vehicle color distribution
* **Advanced Visuals:** Scatter charts, Pareto analysis, heatmaps, decomposition tree
* **Interactive Filters:** Slicers by Year, Region, Model, Fuel_Type, and Transmission
* **Dynamic Insights:** Trend arrows, conditional formatting, and drillthrough capability

---

## **How to Use**

1. Clone or download this repository.

```bash
git clone https://github.com/yourusername/BMW-Sales-BI-Dashboard.git
```

2. Open `BMW_Sales_Dashboard.pbix` in **Power BI Desktop**.
3. Explore KPIs, charts, maps, and slicers to analyze global BMW sales patterns.

---

## **Repository Structure**

```text
BMW-Sales-BI-Dashboard/
│
├─ README.md
├─ data/
│   └─ bmw_worldwide_sales.csv
└─ dashboard/
    └─ BMW_Sales_Dashboard.pbix
```

---

## **Acknowledgement**

The dataset is sourced from **Kaggle**, and the dashboard design is based on my academic work for **INFO 523 – Data Mining and Discovery** at the **University of Arizona**. Full project documentation and interactive analysis are available at:

* GitHub Pages: [https://INFO523-Fall25-101-201.github.io/final-project-min-set-khant-solo/](https://INFO523-Fall25-101-201.github.io/final-project-min-set-khant-solo/)
* Quarto Publication: [https://minsetkhant.quarto.pub/info-523--bmw-price-prediction](https://minsetkhant.quarto.pub/info-523--bmw-price-prediction)

---

## **Technologies & Tools**

* **Power BI:** DAX, KPI cards, interactive charts, maps, and advanced visuals
* **Data Preparation:** Microsoft Excel / Python (optional preprocessing)

---

