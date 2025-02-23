## Movie Recommendation System
This project implements a content-based movie recommendation system using TF-IDF vectorization and K-Nearest Neighbors (KNN) to suggest movies based on user input. The system processes movie descriptions, genres, and languages to find the best matches.

# Setup
1. Install dependencies:    
`pip install pandas numpy nltk scikit-learn`

# Download NLTK resources:
2. Run the following inside a Python script:  
`import nltk`  
`nltk.download('punkt')`  
`nltk.download('stopwords')`  
`nltk.download('wordnet')`  

# Dataset
3. Download the dataset file, unzip it and and place it in the project direcotry. That is the file lumaa.py and movies_metadata.csv should be in the same folder.
   For example  
   -Downloads  
&nbsp;&nbsp;&nbsp;-lumaa  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-lumaa.py  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-movies_metadata.csv
(This dataset was downloaded from Kaggle and can be found online)

# Running the program
5. In the terminal, go to the directory where both the files are saved and run the following command:  
   `python lumaa.ipynb`  
Alternatively, you could also run it as a jupyter notebook. For this you will need to upload the CSV file and change the file path in line 146.
(You can refer to the vide. Both these methods are shown there)

# Input
6. You will be asked to describe the type of movies you like (e.g., "action thriller in English"). The system will then process your input and return the top movie recommendations.
For example: 
![image](https://github.com/user-attachments/assets/c515b00a-02cd-42ca-8b9e-f788b1f0d459)  

Salary expectation per month: $20-30/hr 







