# BigBasket Product Analysis

Exploratory Data Analysis Of BigBasket's Product Catalogue Using **Python, Pandas, NumPy, Matplotlib and Seaborn**. The Repo Also Includes Foundational Notebooks That Build Up The Techniques Used In The Analysis.

## Objective

Understand The BigBasket Product Catalogue By Exploring Pricing, Categories, Brands and Ratings, And Present The Findings Through Clear Visualizations.

## Dataset

`data/BigBasket_Products.csv`

- **Rows / Columns:** [add from `df.shape`]
- **Key columns:** [e.g. product, category, brand, sale price, market price, rating]

## Key Insights

## Dataset

`data/BigBasket_Products.csv`

- **Size:** 27,555 products × 10 columns
- **Columns:** `index`, `product`, `category`, `sub_category`, `brand`, `sale_price`, `market_price`, `type`, `rating`, `description`
- **Coverage:** 11 categories, 90 sub-categories, 426 product types and 2,313 brands
- **Data quality:** 8,626 products (31.3%) have no rating, and 115 have no description. No row has a sale price higher than its market price.

## Key Insights

- **Beauty & Hygiene is the largest category** with 7,867 products (28.6% of the catalogue). The top 3 categories (Beauty & Hygiene, Gourmet & World Food, Kitchen/Garden/Pets) make up 58.6% of all products.
- **55.3% of products are sold at a discount.** Among discounted items the average discount is 21.4%, and across the whole catalogue it is 11.8%.
- **Discounts vary a lot by category.** Kitchen, Garden & Pets (22.2%) and Fruits & Vegetables (21.2%) have the highest average discounts, while Baby Care (5.9%) and Snacks & Branded Foods (6.6%) have the lowest.
- **Prices are right-skewed.** The average sale price is Rs. 322.5 but the median is only Rs. 190, because a few premium items go up to Rs. 12,500.
- **Ratings are generally high.** The average rating is 3.94, and 65.3% of rated products have 4.0 or above.
- **Price and rating are almost unrelated** (correlation -0.08), so a higher price does not mean a better rating.
- **Fresho is the most common brand** (638 products), followed by bb Royal (539) and BB Home (428).

## Notebooks

| # | Notebook | Purpose |
|---|----------|---------|
| 1 | [NumPy Basics](notebooks/01_numpy_basics.ipynb) | Arrays, Indexing, Slicing, Numerical Operations |
| 2 | [Pandas Data Analysis](notebooks/02_pandas_data_analysis.ipynb) | Data Cleaning, Filtering, Grouping And EDA On BigBasket Data|
| 3 | [Matplotlib Visualization](notebooks/03_matplotlib_visualization.ipynb) | Line, Bar, Scatter Plots And Histograms |
| 4 | [Seaborn Visualization](notebooks/04_seaborn_visualization.ipynb) | Distribution And Relationship Plots |

## Getting Started

```bash
git clone https://github.com/ABHAYMARWADE2004/bigbasket-product-analysis.git
cd bigbasket-product-analysis

python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

pip install -r requirements.txt
jupyter notebook
```

## Project Structure

```
bigbasket-product-analysis/
├── data/
│   └── BigBasket_Products.csv
├── notebooks/
│   ├── 01_numpy_basics.ipynb
│   ├── 02_pandas_data_analysis.ipynb
│   ├── 03_matplotlib_visualization.ipynb
│   └── 04_seaborn_visualization.ipynb
├── images/
├── requirements.txt
└── README.md
```

## Tech Stack

Python · Jupyter Notebook · NumPy · Pandas · Matplotlib · Seaborn

## Skills Demonstrated

Data cleaning · Exploratory Data Analysis (EDA) · Data manipulation · Data visualization · Insight Storytelling

## Author

**Abhay Marwade**
 Aspiring Data Analyst

[GitHub](https://github.com/ABHAYMARWADE2004)
