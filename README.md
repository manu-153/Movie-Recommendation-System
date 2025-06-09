

## Dataset  
The project uses a **filtered version** of the [MovieLens dataset](https://grouplens.org/datasets/movielens/).  
- **Movies**: Over **4,778** titles.  
- **Users**: **443** users with different rating preferences.  
- **Ratings**: From **0.5 to 5** in increments of **0.5**.  

## How It Works  
1. **Load the MovieLens dataset** – Movie ratings and user interactions.  
2. **Preprocess Data** – Normalize ratings and set up feature matrices.  
3. **Collaborative Filtering Algorithm** – Train the system using:  
   - **User and movie feature vectors**  
   - **Bias terms for users**  
   - **Regularization to prevent overfitting**  
4. **Optimize using TensorFlow** – AutoDiff and **Adam optimizer** for learning.  
5. **Generate Predictions** – Compute expected ratings for unrated movies.  
6. **Recommend Movies** – Suggest top-rated movies for users.  

## Installation  
### **Prerequisites**  
Make sure you have **Python 3.8+** and the necessary dependencies installed.  

### **Clone the Repository**  
1. Clone this repository.  
2. Navigate to the project directory.  
3. Run the training script to generate recommendations.  

## Example Output  
### **Predicted Top Recommendations**  
Predicting rating 4.49 for movie My Sassy Girl (2001)  
Predicting rating 4.48 for movie Memento (2000)  
Predicting rating 4.47 for movie The One I Love (2014)  

### **Original vs Predicted Ratings**  
Original: 5.0 | Predicted: 4.90 | Shrek (2001)  
Original: 3.0 | Predicted: 3.00 | Inception (2010)  
Original: 1.0 | Predicted: 1.26 | Nothing to Declare (2010)  

## Project Structure  
- **data/**: MovieLens dataset  
- **models/**: Trained models  
- **notebooks/**: Jupyter notebooks for analysis  
- **src/**: Source code  
  - preprocess.py: Data preprocessing  
  - train.py: Training script  
  - recommend.py: Generate recommendations  
- **README.md**: Project documentation  

## References  
- **MovieLens Dataset** – [F. Maxwell Harper & Joseph A. Konstan (2015)](https://doi.org/10.1145/2827872)  
- **Deep Learning Recommender Systems** – Various research papers  

## Contributing  
Feel free to submit **issues** or **pull requests**. Contributions are welcome!  

## License  
This project is licensed under the **MIT License**.  



