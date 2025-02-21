# 🥦 Organic Products Customer Analysis

## **Project Overview**
This project focuses on identifying key customer segments that are most likely to purchase organic products using data analysis and machine learning techniques. The goal is to help businesses tailor marketing strategies and boost sales of organic items by understanding consumer behaviors and preferences.

The final model utilizes classification algorithms and a random forest surrogate tree to interpret feature importance, providing actionable insights for customer targeting.

---

## **Key Features**
- **Data Wrangling:** Cleaned and pre-processed raw data to prepare for analysis and modeling.
- **Feature Engineering:** Created new variables to capture customer behaviors and preferences.
- **Predictive Modeling:** Applied classification techniques (Random Forest, Logistic Regression) to predict the likelihood of purchasing organic products.
- **Model Interpretation:** Utilized a Random Forest Surrogate Tree to visualize and interpret the most important features affecting customer choices.
- **Insights & Recommendations:** Provided data-driven strategies to improve marketing outreach towards organic product buyers.

---

![Decision Tree Visualization](random_forest_surrogate_tree.pdf)

---

## **Getting Started**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/TinaGrkovic/organic_products.git
   cd organic_products
2. **Run the final notebook:**
   ```bash
   jupyter notebook notebooks/organic_products.ipynb

### **Repository Structure**
  ```bash
  organic-products-project/
  ├── organic_products.ipynb            # Main Jupyter Notebook with data exploration, modeling, and analysis
  ├── organics.xlsx                     # Original dataset containing customer data and purchase history
  ├── Organics Project.docx             # Business problem and data dictionary
  ├── Organic_Products_Tina.pptx        # Final presentation deck with key insights and visuals
  ├── random_forest_surrogate_tree.pdf  # Visualization of the surrogate tree highlighting feature importance
  └── README.md
