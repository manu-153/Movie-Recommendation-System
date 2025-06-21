# Movie Recommendation System using Collaborative Filtering 

  # 🎬 Movie Recommendation System using Collaborative Filtering

## 📌 Overview  
This project develops a **collaborative filtering-based recommendation system** using **TensorFlow** and **NumPy**. It estimates movie ratings based on user history and delivers personalized movie suggestions.

The model is trained on a subset of the **MovieLens dataset**, applying **matrix factorization** to learn underlying patterns between users and movies.

---

## 🚀 Features  
- ✅ **Collaborative Filtering** – Learns embeddings for users and movies based on past ratings.  
- ✅ **Adam Optimizer** – Utilizes adaptive gradient descent for efficient and robust training.  
- ✅ **Mean Normalization** – Handles sparse data and improves predictions for users with fewer interactions.  
- ✅ **Vectorized Operations** – Boosts performance with efficient matrix computations.  
- ✅ **Personalized Recommendations** – Suggests top-rated unseen movies for each user.

---

## 📊 Dataset  
This system is built using a curated version of the [MovieLens dataset](https://grouplens.org/datasets/movielens/):

- 🎥 **Movies**: 4,778 titles  
- 👤 **Users**: 443 unique users  
- ⭐ **Ratings**: Range from **0.5 to 5.0** in **0.5** increments  

---

## ⚙️ How It Works  
1. **Load Data** – Import user ratings and movie details from the MovieLens dataset.  
2. **Preprocessing** – Normalize ratings and initialize user/movie feature matrices.  
3. **Model Training** –  
   - Learn latent vectors for users and movies  
   - Include bias terms for improved accuracy  
   - Apply regularization to avoid overfitting  
4. **Optimization** – Use **TensorFlow's autodiff** and the **Adam optimizer** to minimize loss.  
5. **Prediction** – Estimate ratings for unrated movies.  
6. **Recommendation** – Provide top personalized movie picks for each user.

---

## 🛠️ Installation  

### 🔧 Prerequisites  
- Python 3.8+  
- TensorFlow  
- NumPy  
- Pandas  

### 📥 Clone the Repository  
```bash
git clone https://github.com/yourusername/movie-recommender.git
cd movie-recommender
movie-recommender/
│
├── data/              # Filtered MovieLens dataset  
├── models/            # Trained models  
├── notebooks/         # Jupyter notebooks for experiments  
├── src/               # Source code  
│   ├── preprocess.py      # Data preprocessing script  
│   ├── train.py           # Model training  
│   └── recommend.py       # Generate recommendations  
└── README.md          # Project documentation
 



