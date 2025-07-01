
# Swiggy Restaurant Analysis and Clustering 🍟





![Logo](https://companieslogo.com/img/orig/SWIGGY.NS_BIG-f0e9f79a.png?t=1731987060)



## 📍 Context

Swiggy has revolutionized how we order food in Indian cities. With thousands of restaurants across the country, the Swiggy platform offers a variety of cuisines—from biryani to sushi, from quick bites to gourmet dining.

This project analyzes Swiggy restaurant data and builds an intelligent system to:

->Understand restaurant performance trends

->Group restaurants using clustering

->Visualize consumer behavior

->Recommend strategies for new and existing restaurants

Just like the Zomato ecosystem, the Swiggy landscape is rich in diversity but also competitive. In cities like Bengaluru, Pune, and Mumbai, standing out as a restaurant is becoming increasingly difficult.

This system helps:

->Restaurant owners understand competition

->Swiggy analysts optimize listings

->Users explore clusters of dining choices

## 📋 Content
The main aim is to gain business and consumer insights using machine learning and data visualization techniques.

Key questions:

What type of restaurants perform well?

Are there meaningful clusters based on rating, price, and cuisine?

Can we group similar restaurants together to drive recommendations?

How can new restaurants position themselves?

## 🧪 Methodology

🔹 Phase I: Data Preprocessing

->Dropped irrelevant or missing values

->Standardized numerical features for clustering

->Feature selection: rating, pricing, cuisine count, etc.

🔹 Phase II: Exploratory Data Analysis

->Distribution plots of restaurant ratings

->Correlation matrix to analyze relationships between key features

->Insights on consumer price sensitivity vs. rating

🔹 Phase III: Clustering with KMeans

->Optimal number of clusters determined using Silhouette Score

->Final model selected with k=2 for maximum silhouette (~0.50)

->Cluster interpretation reveals restaurant positioning

🔹 Phase IV: Visualization

->PCA used to reduce high-dimensional data to 2D

->Clear visualization of clusters to observe spread, separation

->Cluster 0 → Highly rated, popular restaurants

->Cluster 1 → Less-rated or newer players

## 📈 Insights & Conclusion

✅ Cluster 0:

->High ratings (avg. 4.14)

->500+ reviews

->Decent pricing (~₹275)

->Reliable and popular

✅ Cluster 1:

->Slightly lower rating (avg. 4.02)

->Very low number of reviews (~35)

->Similar pricing

->Possibly new, niche, or underperforming restaurants

#### This shows that engagement (number of reviews) is more crucial than pricing or cuisine variety when it comes to perceived restaurant success.

## 📚 Sections

✔️ Exploratory Data Analysis

✔️ Visualization (Matplotlib, Seaborn, PCA)

✔️ Clustering (KMeans, Silhouette Score)

✔️ Business Insight Generation

✔️ (Optional Next Steps) Recommendation System

## 🚀 Future Work
 ->Add sentiment analysis if review text is available

 ->Include geographical clustering using latitude/longitude

 ->Deploy as an interactive web app using Streamlit

 ->Build personalized recommendation system

 ->Add cuisine-based search filters

 ->Expand data to include multiple cities













## Tech Stack

**Languages & Environment**:
Python, Jupyter Notebook, Google Colab

**Libraries & Frameworks**:

Data Analysis: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn (KMeans, Silhouette Score, PCA)

Clustering & Dimensionality Reduction: KMeans, PCA

Notebook Rendering & Display: IPython, Colab Widgets

*Tools & Platforms:*
Google Colab, GitHub, VS Code


## Run Locally

Clone the project

```bash
  git clone https://github.com/ChachanNaman/Swiggy-Restaurant-Analysis-and-Clustering
```

Go to the project directory

```bash
  cd Swiggy-Restaurant-Analysis-and-Clustering

```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  jupyter notebook
```





## 🧾 License

This project is licensed under the MIT License – see the [LICENSE](./LICENSE) file for details.



## Refrences 👏
- [Zomato Restaurant Clustering + Sentiment Analysis](https://www.kaggle.com/code/anandsiva/zomato-restaurant-clustering-sentiment-analysis/notebook#No.of-cluster-=-7)
- [Swiggy Restaurant's Dataset](https://www.kaggle.com/datasets/rrkcoder/swiggy-restaurants-dataset/data)




## 🚀 About Me
Naman Chachan


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naman-chachan-903bb9277/)
[![LeetCode Badge](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white
)](https://leetcode.com/u/chachannaman/)

