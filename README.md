# instagram-likes-linear-regression# 

This project predicts the number of likes a post gets on Instagram based on the author's followers and their past post performance, using Linear Regression.

## 🔍 Project Objective

To understand how followers and historical engagement influence the number of likes on a post.

## 📦 Dataset

- **Source:** Provided during Le Wagon Bootcamp
- **Size:** ~2.2 million Instagram posts
- **Columns:**
  - `id`: Author ID
  - `followers`: Number of followers
  - `comments`: Number of comments
  - `posts`: Number of posts
  - `likes`: Number of likes
  - `ts`: Timestamp

## 🧪 Models & Features

### Model 1:
- **Input:** Followers
- **R² Score:** ~0.22 (Test)
- **MAE:** ~33 likes

### Model 2 (Improved):
- **Input:** Followers + Historical Likes (Median of past likes)
- **R² Score:** ~0.55 (Test)
- **MAE:** ~23 likes

## 📈 Visualizations
- Scatterplot showing correlation between likes and followers

## ⚙️ Technologies
- Python
- Pandas, Seaborn, Scikit-learn
- Google Colab

## 🚀 How to Run

1. Clone the repo
2. Upload the dataset `posts.csv` to your notebook
3. Run the notebook step by step

## 🙋‍♀️ About Me

This project was completed as part of the [Le Wagon Data Analytics Bootcamp](https://www.lewagon.com/). 

