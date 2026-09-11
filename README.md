# 📚 Amazon Top 100 Bestselling Books Analysis Dashboard

## 📌 Executive Summary

This project provides an end-to-end market analysis of the **Amazon Top 100 Bestselling Books** and verified reader reviews. Built using **Microsoft Excel**, this interactive dashboard aggregates key commercial metrics, author dominance, pricing tiers, and reader sentiment to reveal the underlying trends driving top-performing publications.

---

## 📊 Key Market Metrics

* **Total Bestsellers Analyzed:** 100 Books
* **Total Reviews Evaluated:** 921 Verified Reader Reviews
* **Average Book Price:** $12.71
* **Average Customer Rating:** 4.69 / 5.00
* **Top Featured Author:** Sarah J. Maas (5 titles in Top 100)

---

## 💡 Key Business Insights

* **Price Tier Breakdown:** **50%** of bestsellers fall into the **Moderate** price tier ($10–$25), **45%** belong to **Budget** (<$10), and **5%** command **Premium** pricing (box sets >$25).
* **Rating Stability:** Reader satisfaction remains high across all tiers, maintaining an average rating of **4.69 / 5.00** regardless of price.
* **Author Dominance:** **Sarah J. Maas** leads total catalog representation with 5 separate listings in the Top 100, followed by **Adam Wallace** (3 listings) and **Rebecca Yarros** (2 listings).
* **High-Value Items:** Boxed sets account for the highest individual price points, led by *A Court of Thorns and Roses* ($48.77) and *Harry Potter* ($45.22).

---

## 🛠️ Data Pipeline & Workbook Architecture

### Data Cleaning & Transformation

* Processed and cleaned raw book metadata, publication dates, standard ASIN numbers, and price data across 100 books and 921 user reviews.
* Applied conditional grouping to establish automated price categories (**Budget**, **Moderate**, **Premium**).
* Created custom **Pivot Tables** and **Pivot Charts** paired with interactive **Slicers** for dynamic filtering across author, genre, and price tiers.

### Workbook Sheet Breakdown

| Sheet Name | Description |
| --- | --- |
| **`Books_Cleaned2`** | Cleaned main dataset containing 100 bestsellers, price tiers, rankings, and authors. |
| **`Books_Reviews_Merged1`** | Combined dataset containing 921 verified reader reviews and review scores. |
| **`Pivot Tables`** | Backend aggregations calculating price tier averages, genre volume, and author rankings. |
| **`Overview` / Visual Tabs** | Interactive front-end visual dashboard with custom KPI cards and slicers. |

---

## 📂 Repository Structure

```text
├── Data Diva Team (final).xlsx   # Master Excel Workbook (Data + Pivots + Dashboard)
├── Screenshots/                  # High-resolution captures of the Excel dashboard
│   ├── Overview.png
│   └── Price_Rating_Analysis.png
└── README.md                     # Documentation

```

---

## 👥 Project Team — *Data Divas*

* **Aya Ayman**
* **Banan Magdy**
* **Habiba Walid**
* **Mennatullah Hussien**
* **Mirna Elghonimy**
