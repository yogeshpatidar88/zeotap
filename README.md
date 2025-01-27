# zeotap
Assignment Solution - EDA, Lookalike, and Clustering
Overview
This repository provides solutions for the assignment, which includes:

Exploratory Data Analysis (EDA): Visualizations and insights to understand customer behaviors.
Lookalike Recommendations: Identifying similar customers using cosine similarity.
Customer Clustering: Grouping customers based on purchasing behavior using clustering algorithms.
Scripts
eda_script.py: Performs EDA and generates visualizations.
lookalike_script.py: Generates lookalike customer recommendations and outputs them to Ankur_Bhadauria_Lookalike.csv.
clustering_script.py: Applies clustering to customer data and outputs results to customer_clusters.csv.
image_to_pdf_script.py: Converts images (output_eda_1.jpg to output_eda_9.jpg) into a PDF (output_images.pdf).
How to Run
Install dependencies:

bash
Copy
Edit
pip install pandas numpy scikit-learn pillow fpdf
Run the scripts:

EDA: python eda_script.py
Lookalikes: python lookalike_script.py
Clustering: python clustering_script.py
Images to PDF: python image_to_pdf_script.py
Outputs
Lookalikes: Ankur_Bhadauria_Lookalike.csv
Clustering: customer_clusters.csv
PDF: output_images.pdf
Conclusion
This project provides an end-to-end solution for customer analysis, including EDA, lookalike recommendations, and clustering.
