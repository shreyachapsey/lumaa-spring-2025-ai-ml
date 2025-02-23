Movie Recommendation System
This project implements a content-based movie recommendation system using TF-IDF vectorization and K-Nearest Neighbors (KNN) to suggest movies based on user input. The system processes movie descriptions, genres, and languages to find the best matches.

Setup
Install dependencies:
pip install pandas numpy nltk scikit-learn

Download NLTK resources:
Run the following inside a Python script or Jupyter Notebook:
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')

Download the dataset and and place it in the project direcotry.

Run the script and enter a movie preference when prompted:

python recommend_movies.py
You will be asked to describe the type of movies you like (e.g., "action thriller in English"). The system will then process your input and return the top movie recommendations.
For example: 
![image](https://github.com/user-attachments/assets/c515b00a-02cd-42ca-8b9e-f788b1f0d459)







