# BigBasket Product Analysis

Exploratory Data Analysis of BigBasket's Product Catalogue Using **Python, Pandas, NumPy, Matplotlib and Seaborn**. The repo also includes Foundational Notebooks That Build Up The Techniques Used In The Analysis.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)

## Objective

Understand The BigBasket Product Catalogue By Exploring Pricing, Categories, Brands And Ratings And Present The Findings Through Clear Visualizations.

## Dataset

`data/BigBasket_Products.csv`

- **Size:** 27,555 products x 10 columns
- **Columns:** `index`, `product`, `category`, `sub_category`, `brand`, `sale_price`, `market_price`, `type`, `rating`, `description`
- **Coverage:** 11 Categories, 90 Sub-Categories, 426 Product Types And 2,313 Brands
- **Data quality:** 8,626 Products (31.3%) Have No Rating and 115 Have No Description. No Row Has a Sale Price Higher Than Its Market Price.

## Key Insights

- **Beauty & Hygiene Is The Largest Category** with 7,867 products (28.6% of the Catalogue). The Top 3 categories (Beauty & Hygiene, Gourmet & World Food, Kitchen/Garden/Pets) Make Up 58.6% of All Products.
- **55.3% of Products Are Sold At a Discount.** Among Discounted Items The Average discount is 21.4%, And Across The Whole Catalogue It Is 11.8%.
- **Discounts Vary a Lot By Category.** Kitchen, Garden & Pets (22.2%) And Fruits & Vegetables (21.2%) Have The Highest Average Discounts, While Baby Care (5.9%) And Snacks & Branded Foods (6.6%) Have The Lowest.
- **Prices Are Right-Skewed.** The Average Sale Price Is Rs. 322.5 But The Median Is Only Rs. 190, Because a Few Premium Items Go up to Rs. 12,500.
- **Ratings Are Generally High.** The average rating is 3.94 And 65.3% Of Rated Products Have 4.0 Or Above.
- **Price And Rating Are Almost Unrelated** (Correlation -0.08), So a Higher Price Does Not Mean a Better Rating. Budget products (Under Rs. 100) Even Average a Higher rating (4.03) Than Premium Products of Rs. 1000 and Above (3.75).
- **Fresho is The Most Common Brand** (638 products), Followed By BB Royal (539) And BB Home (428).

## Visualizations

### Products by category
![Products by category](images/products_by_category.png)

### Average discount by category
![Average discount by category](images/discount_by_category.png)

### Sale price distribution
![Sale price distribution](images/price_distribution.png)

## Notebooks

| # | Notebook | Purpose |
|---|----------|---------|
| 1 | [NumPy Basics](notebooks/01_numpy_basics.ipynb) | Arrays, Indexing, Filtering, Statistics, And NumPy On the BigBasket Data |
| 2 | [Pandas Data Analysis](notebooks/02_pandas_data_analysis.ipynb) | Data Cleaning, Filtering, Grouping And EDA On BigBasket Data |
| 3 | [Matplotlib Visualization](notebooks/03_matplotlib_visualization.ipynb) | Line, Bar, Histogram, Box And Scatter Plots |
| 4 | [Seaborn Visualization](notebooks/04_seaborn_visualization.ipynb) | Distribution And Relationship Plots |

## Getting Started

```bash
git clone https://github.com/ABHAYMARWADE2004/Bigbasket-Product-Analysis.git
cd Bigbasket-Product-Analysis

python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

pip install -r requirements.txt
jupyter notebook
```

Open the notebooks from the `notebooks/` folder. They find the dataset in `data/` automatically.

## Project Structure

```
Bigbasket-Product-Analysis/
├── data/
│   └── BigBasket_Products.csv
├── images/
│   ├── products_by_category.png
│   ├── discount_by_category.png
│   └── price_distribution.png
├── notebooks/
│   ├── 01_numpy_basics.ipynb
│   ├── 02_pandas_data_analysis.ipynb
│   ├── 03_matplotlib_visualization.ipynb
│   └── 04_seaborn_visualization.ipynb
├── requirements.txt
└── README.md
```

## Tech Stack

Python · Jupyter Notebook · NumPy · Pandas · Matplotlib · Seaborn

## Skills Demonstrated

Data Cleaning · Exploratory Data Analysis (EDA) · Data Manipulation · Data Visualization 

## Author

**Abhay Marwade**

Aspiring Data Analyst

[GitHub](https://github.com/ABHAYMARWADE2004)
