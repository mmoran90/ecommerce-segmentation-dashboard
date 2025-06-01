📌 Overview
This project aims to identify distinct customer segments for an e-commerce business using unsupervised machine learning. By analyzing customer behavior through RFM (Recency, Frequency, Monetary) analysis, we apply clustering techniques to group customers into actionable segments. An interactive dashboard built with Streamlit allows stakeholders to explore and visualize these segments.

🧠 Objectives
Perform data cleaning and feature engineering on raw transactional data

Construct RFM features to capture customer purchasing behavior

Apply K-Means clustering to uncover customer segments

Visualize segment characteristics through dimensionality reduction and statistical summaries

Build a Streamlit dashboard to explore customer groups interactively

🧰 Technologies Used
Python

Pandas, NumPy – data manipulation

Matplotlib, Seaborn – visualizations

Scikit-learn – clustering & preprocessing

Streamlit – dashboard development

📂 Project Structure
graphql
Copy
Edit
ecommerce_segmentation_dashboard/
├── data/                   # Raw dataset
├── notebooks/              # EDA and development notebooks
├── pipeline/               # Data processing scripts
├── app/                    # Streamlit dashboard
├── outputs/                # Saved figures and tables
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
📈 RFM Feature Explanation
Recency: Days since the customer's last purchase

Frequency: Total number of purchases

Monetary: Total spend across all purchases

These features allow us to define customer value and engagement levels.

💡 Key Results
Identified X customer segments with unique behavioral profiles

Found high-value, loyal customers and at-risk customers

Developed a dashboard to support marketing decision-making
