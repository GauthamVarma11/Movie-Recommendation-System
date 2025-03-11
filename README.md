# Movie-Recommendation-System 🎬
A hybrid recommendation system using collaborative filtering, content-based filtering, and hybrid techniques to provide personalized movie suggestions. The backend is powered by R scripts, while a Streamlit web app serves as the frontend.

# 🚀 Overview
Recommendation systems play a vital role in platforms like Netflix, Amazon Prime, and YouTube by personalizing user experiences. This project combines user-based collaborative filtering, item-based filtering, and content-based approaches to predict movies users might enjoy.

# ✨ Features
# 1️⃣ Advanced Recommendation Algorithms
✔ User-Based Collaborative Filtering (UBCF) – Recommends movies based on user similarities.

✔ Item-Based Collaborative Filtering (IBCF) – Suggests movies similar to those a user has liked.
✔ Content-Based Filtering – Matches movies with similar genres and metadata.
✔ Hybrid Recommendation System – Combines multiple techniques for improved accuracy.

# 2️⃣ Interactive Streamlit Web App
✔ User-friendly UI for selecting algorithms, entering movie names, and adjusting recommendation settings.
✔ Real-time results displayed directly in the app.
✔ Option to export recommendations as CSV files for offline analysis.

# 📊 Dataset Information
# 📌 Source
The dataset is sourced from the UCI Machine Learning Repository, containing anonymized user demographics, ratings, and movie metadata.

# 📁 Dataset Structure
Feature	Description
user_id	Unique identifier for users
movie_id	Unique identifier for movies
rating	User rating (1–5 scale)
timestamp	Date and time of the rating
genres	Movie genres
title	Movie title


# ⚙️ Setup Instructions
# 1️⃣ Prerequisites
📌 Install Python (>=3.7) and R (>=4.3.3)

# 2️⃣ Install Python Dependencies
pip install streamlit pandas
# 3️⃣ Install R Libraries
install.packages(c("recommenderlab", "dplyr", "reshape2", "proxy"))
# 4️⃣ Run the Application
streamlit run index.py
