# Instacart Dataset Instructions

This folder is intended to store all original CSV files from the **Instacart Online Grocery Shopping Dataset**.

Due to file size and licensing restrictions, the dataset is **not included in this repository**.  
To replicate the analysis, please follow the steps below:

---

## Step-by-step Instructions

1. Go to the Kaggle dataset page:  
   👉 [https://www.kaggle.com/datasets/instacart/instacart-market-basket-analysis](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis)

2. Download the dataset (you may need to log into your Kaggle account)

3. Extract the contents and place all CSV files inside this `data/` folder:
   - `aisles.csv`
   - `departments.csv`
   - `order_products__prior.csv`
   - `order_products__train.csv`
   - `orders.csv`
   - `products.csv`

4. Your folder structure should now look like:
<img width="255" height="162" alt="image" src="https://github.com/user-attachments/assets/53acd5d7-d365-4567-9fb2-fb05ba6e6334" />

---

## Notes

- `order_products__prior.csv` is the largest file (~3 million rows). Consider sampling if you encounter memory issues.
- Data is from actual Instacart users’ anonymised purchase history.
- Always cite the original dataset if reusing this project for academic or professional purposes.
