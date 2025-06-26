# bigdata-movie-dataset
Developing an End-to-End Big Data Pipeline Using Hadoop, Spark, and MLlib

# Movie Rating Classification with PySpark and Scikit-learn
Today, digital movie platforms often struggle to classify movies by quality. As a result, users may receive irrelevant or poorly-rated recommendations.
I found my dataset on Kaggle and chose it. Because it looked interesting and I might make a business insight with this data. It contained various movie related features like runtime, vote count, language, and ratings. 

This project aims to classify movie ratings into categories like `poor`, `average`, `good`, and `excellent` using PySpark and Random Forest.

# Tools Used
- **Docker** to set up a local big data environment
- **Apache Spark (PySpark)** for data wrangling and transformation
- **Spark SQL** for analysis and aggregation
- **Scikit-learn** for model training (Random Forest Classifier)
- **Pandas / Matplotlib / Seaborn** for visualization

# Model Accuracy
- Accuracy: **80.4%**
- F1 Score (Excellent class): **0.96**
- Most influential feature: **vote_count**

# How to Run
1. Clone the repo
2. Start Docker (`docker-compose up`)
3. Open Jupyter and run the notebook step by step

# Data Link
https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies 
Version 614 (562.7 MB)

# Contact
For any questions, contact me at: Q1087824@students.berlinsbi.com
