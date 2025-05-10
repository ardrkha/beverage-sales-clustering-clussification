
# Beverage Sales Clustering and Classification

Objective: create a clustering model from the beverage sales dataset, then the clustering results are used to create a classification model



## Dataset
The dataset used is a dataset from Kaggle with the following link:
https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales

The dataset includes the following features:
- Order_ID : Unique identifier for each order. Groups multiple products within the same order.
- Customer_ID : Unique identifier for each customer, distinguishing individual buyers.
- Customer_Type : Indicates whether the customer is B2B (business-to-business) or B2C (business-to-consumer).
- Product : The name of the product purchased, such as "Coca-Cola" or "Erdinger Weißbier".
- Category : The product category, such as "Soft Drinks" or "Alcoholic Beverages".
- Unit_Price : The price per unit of the product.
- Quantity : The number of units purchased for the specified product in the order.
- Discount : The discount applied to the product (e.g., 0.1 for 10%). Discounts are only given to B2B customers.
- Total_Price : The total price for the product after applying discounts.
- Region: The region of the customer, such as "Bayern" or "Berlin".
- Order_Date : The date when the order was placed.
## Usage

1. Clone the repository
```bash
git clone https://github.com/ardrkha/beverage-sales-clustering-classification.git
cd beverage-sales-clustering-classification
```
2. Create a Conda Environment
```bash
conda env create -f environment.yml
conda activate beverage_sales
```
3. Run the Project
```bash
beverage-sales-clustering-classification/
├── dataset/
├── [1. clustering model.ipynb] (run this notebook for the clustering model)
├── [2. classification model.ipynb] (run this notebook for the classification model)
└── ...
```
## Dependencies

All dependencies are listed in environment.yml. Ensure you install them using Conda.
## Contact

f you have any questions, feel free to reach out to us at hardatama27@gmail.com.

Developed by Hardatama Rakha Ugraha - 2024
