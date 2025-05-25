# Movie-Recommendation-System-Using-Hadoop-

# 🎬 Movie Recommendation System Using Hadoop

This project implements a simple Movie Recommendation System using Hadoop MapReduce and Python.

## 📌 Objective
To recommend movies to users based on their preferences using collaborative filtering, specifically the Pearson correlation method.

## 🧰 Technologies Used
- Hadoop MapReduce
- Python
- Text file input/output

## 📁 Files
- `datasetSmall.txt`: Input data (user-movie-rating)
- `mapper.py`: Mapper script to group ratings by user
- `reducer.py`: Reducer script to calculate similarity and generate recommendations
- `outputfile.txt`: Output file showing recommendations per user

## 💡 Key Features
- Recommends top 5 movies to each user
- Based on user-user collaborative filtering
- Uses Pearson correlation for similarity

## 🧪 Sample Output

user1 ["'The Dark Knight'", "'Fight Club'", "'The Shawshank Redemption'"]
user2 ["'Titanic'", "'The Lion King'", "'Pulp Fiction'", "'Gladiator'", "'The Godfather'"]


