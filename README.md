# online_retail_11
Online Retail Customer Segmentation (RFM Analysis)

This project focuses on analyzing customer purchasing behavior using the Online Retail II dataset. The goal is to understand how recently customers purchased (Recency), how often they purchased (Frequency), and how much they spent (Monetary Value) — also known as RFM Analysis.

About the Project

Businesses often struggle to understand which customers are loyal, inactive, or high-value.
Using RFM segmentation, we can group customers based on their shopping behavior and help businesses make smarter marketing decisions.

In this project, 

✔ Cleaned and prepared the retail dataset
✔ Calculated Recency, Frequency, and Monetary values for each customer
✔ Visualized the distribution of these RFM values (shown in the image above)
✔ Prepared the dataset for clustering and further insights

What the Visualizations Show

->Monetary Distribution
Most customers spend smaller amounts, but a few spend significantly more (right-skewed distribution).
-> Frequency Distribution
Many customers have purchased only a few times, while very few purchase frequently.
-> Recency Distribution
Recent buyers are fewer compared to those who haven't purchased in a while — useful to detect loyal vs lost customers.

Project Structure

📁 online_retail_11
├── online_retail.ipynb   # Main analysis notebook
├── README.md             # Project documentation
├── requirements.txt      # Python libraries used
├── data/                 # Dataset files (if added)
└── plots/                # Saved visualizations


Technologies Used

Library	Purpose
pandas	Data cleaning & manipulation
matplotlib	Data visualization
seaborn	Statistical plotting
scikit-learn	Clustering & preprocessing
openpyxl	Reading Excel dataset (.xlsx)

