# Shoe Sales Customer Segmentation
## Project Overview
This project focuses on **customer segmentation** for shoe sales using Python and K-Means clustering.  
The goal is to analyze customer purchasing behavior and group similar customers based on **Total Sales** and **Quantity**.

---

## Dataset
- The dataset contains information about shoe sales in a specific region.
- Columns include:
  - **Brand**: Shoe brand (Nike, Adidas, Reebok, etc.)
  - **Model**: Specific shoe model
  - **Type**: Shoe type (Running, Casual, Skate, etc.)
  - **Gender**: Target gender (Men, Women, Unisex)
  - **Size**: Shoe size (US)
  - **Color**: Shoe color
  - **Material**: Main material of the shoe
  - **Price**: Price in USD
- For analysis, a new column **Total_Sales** is calculated:
- *(If Quantity column is not available, assumed 1 per row)*

---

## Tools & Libraries
- **Python 3**
- **Pandas** → Data manipulation
- **Matplotlib & Seaborn** → Data visualization
- **scikit-learn** → K-Means clustering

---

## Steps
1. Load the dataset into Google Colab.
2. Explore and clean the data.
3. Create `Total_Sales` column.
4. Select features for clustering (`Total_Sales` and optionally `Quantity`).
5. Find the optimal number of clusters using the **Elbow Method**.
6. Apply **K-Means clustering** to segment customers.
7. Visualize clusters using scatter plots.
8. Analyze the results and interpret customer groups.

---

## Customer Segments (Example Analysis)
- **Cluster 0** → High spenders / premium customers  
- **Cluster 1** → Frequent buyers with small purchases  
- **Cluster 2** → Average customers  
- **Cluster 3** → Occasional buyers  

---

## Results
- A CSV file `segmented_shoe_customers.csv` is generated with an additional **Cluster** column.
- Scatter plots show the distribution of customers by Total Sales and Price.

---

## How to Use
1. Open `shoe_sales_segmentation.ipynb` in Google Colab.
2. Upload the dataset and run the notebook.
3. Review clusters and analysis.
4. Use this project as a portfolio example or practice K-Means clustering.

---

## GitHub Repository
[https://github.com/username/shoe-sales-segmentation](https://github.com/username/shoe-sales-segmentation)

---
