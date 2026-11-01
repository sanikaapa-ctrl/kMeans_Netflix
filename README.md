# 🎬 Netflix Movie Recommendation System
## 📌 Project Overview
This project focuses on building a Netflix Movie Recommendation System using Machine Learning techniques. It combines K-Means Clustering and a Hybrid Recommendation approach to analyze movie characteristics and recommend similar movies.

The system uses movie genres, ratings, votes, release years, and runtime to explore movie patterns and generate recommendations.

## 🎯 Project Objectives
- Analyze Netflix movie data.
- Perform data preprocessing and exploratory data analysis.
- Apply K-Means Clustering to group similar movies.
- Calculate movie similarity using TF-IDF.
- Build a Hybrid Recommendation System.
- Recommend movies based on content similarity and collaborative filtering scores.

## 🛠️ Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF Vectorizer

## 📂 Dataset
The project uses `Netflix.csv` containing movie-related information.

Important features include:
- Title
- Genre
- Year
- Rating
- Votes
- Runtime

## ⚙️ Data Preprocessing
- Checked missing values.
- Checked duplicate records.
- Analyzed unique values.
- Removed unnecessary columns.
- Converted numeric columns into appropriate data types.
- Filled missing numeric values using median imputation.
- Performed outlier analysis using boxplots.

## 📊 Exploratory Data Analysis (EDA)
The following visualizations are performed:
- Movie Rating Distribution
- Rating vs Runtime
- Rating vs Votes
- Correlation Heatmap
- Boxplot for Outlier Detection

## 🤖 K-Means Clustering
K-Means Clustering is applied to group movies based on numerical features.

**Selected Features:**
- Year
- Rating
- Vote
- Runtime

**Model Parameters:**
- Number of Clusters: 2
- Random State: 42
- Number of Initializations: 10

StandardScaler is used to normalize the numerical features before clustering.

## 🎯 Hybrid Recommendation System

The project combines two recommendation techniques:

### 1. Content-Based Filtering
- Uses movie genres.
- Applies TF-IDF Vectorization.
- Calculates cosine similarity between movies.
- Recommends movies with similar content.

### 2. Collaborative Filtering
- Creates a User-Item Rating Matrix.
- Calculates user similarity using cosine similarity.
- Uses similarity scores to generate recommendation scores.

### 3. Hybrid Recommendation
Combines content-based and collaborative filtering scores.

**Default Weights:**
- Content Weight: 0.5
- Collaborative Weight: 0.5

The system generates the Top 10 movie recommendations based on the hybrid score.

## 📈 Model Visualization
The project includes:
- K-Means Clustering Visualization
- Cluster Centroids
- Rating vs Runtime Clustering Plot
- Rating vs Votes Clustering Plot
- Hybrid Movie Recommendation Bar Chart

## 🏁 Conclusion
This project demonstrates the use of Machine Learning and recommendation techniques for movie recommendations. K-Means Clustering helps group movies based on their numerical features, while the Hybrid Recommendation System combines content-based and collaborative filtering approaches to generate movie recommendations.

## 👩‍💻 Author
**Sanika Patil**  
