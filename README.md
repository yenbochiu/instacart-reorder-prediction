# Instacart Reorder Prediction

This project investigates **what makes a customer repurchase a product** using the [Instacart Online Grocery Shopping Dataset](https://www.kaggle.com/datasets/instacart/instacart-market-basket-analysis).

The project serves as a portfolio piece and a personal learning journey to deepen my understanding of **consumer behaviour, feature engineering, and predictive modelling**, while also giving me the opportunity to practise with **SQL and Tableau**.

---

## Research Focus

- What features are most predictive of product reorders?
- How do user and product behaviours differ across departments?
- Can we build a robust model to predict whether a product will be reordered?

---

## Project Structure
- **01_initial_eda.ipynb**: exploratory analysis
- **02_feature_engineering.ipynb**: new features for user/product/order
- **03_model_training_and_insights.ipynb**: LightGBM classifier with 96% AUC, key drivers of reordering behaviour
- **04_dashboard**: SQL & Tableau visualisations [View Dashboard on Tableau](https://public.tableau.com/views/ReorderAnalysis/Dashboard5?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Tools Used

- Python (pandas, matplotlib, seaborn, scikit-learn)
- SQL (via pandasql or DuckDB)
- Tableau (for interactive dashboard)
- Jupyter Notebook
- GitHub (for version control and publishing)

---

## Dataset

The data is not uploaded due to size limits and policy.  
To reproduce the project:

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/instacart/instacart-market-basket-analysis)
2. Place all CSV files in the `data/` folder
3. You’re good to go!

---

## Key Results

- Top features: up_order_count, order_number, total_orders
- Departments with high reorder rate: dairy eggs, beverages, produce
- Users tend to reorder items added early in their cart

---

## Business Implications

- Promote repeat items early in UI to triger high-reorder products being added to the carts
- Add a "smart-order" button for higher reorder consistency customers for enhancing their habit
- Personalised recommendations based on past frequency, especially for those with lower reorder consistency
- Daily grocery is more likely to be ordered than personal care, pantry, or household stuff

---

## Future Work
- Collaborative filtering / embeddings
- Time-based features (seasonality)
- Deployment as API or dashboard

---

## Author

Name: Yen-Bo Chiu    
Contact: yenbochiu@gmail.com    
Edu: MSc Business Analytics, University of Edinburgh/ BA Economics, National Taiwan University  
Loc: I'm currently based in Edinburgh, Scotland/ Taipei, Taiwan


