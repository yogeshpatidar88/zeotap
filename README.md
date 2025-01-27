# Assignment Solution - EDA, Lookalike, and Clustering

## 📝 Overview

This repository provides a solution for analyzing customer and transaction data, covering the following key tasks:

1. **Exploratory Data Analysis (EDA)**  
   Perform visualizations and derive insights to better understand customer behaviors.
   
2. **Lookalike Customer Recommendations**  
   Identify customers that resemble each other based on their transactional behavior using **cosine similarity**.

3. **Customer Clustering**  
   Group customers using clustering algorithms based on their purchasing patterns and behaviors.

---

## 🧑‍💻 Scripts

### 1. **`eda_script.py`**  
   - Conducts exploratory data analysis and generates visualizations.

### 2. **`lookalike_script.py`**  
   - Generates lookalike recommendations based on customer similarity and outputs them to `Ankur_Bhadauria_Lookalike.csv`.

### 3. **`clustering_script.py`**  
   - Applies clustering algorithms (e.g., K-Means) to group customers and outputs results to `customer_clusters.csv`.

### 4. **`image_to_pdf_script.py`**  
   - Converts images (`output_eda_1.jpg` to `output_eda_9.jpg`) into a PDF (`output_images.pdf`).

---

## ⚙️ How to Run

### Prerequisites

1. Install the required dependencies:

   ```bash
   pip install pandas numpy scikit-learn pillow fpdf
