# Book Recommendation System

A simple book recommendation system built with Python, Flask, and machine learning.  
It provides book recommendations based on popularity and collaborative filtering.

---

## 🔗 Live Demo

The app is deployed on Render and accessible at:  
[Book Recommendation System](https://bookrecommsystemm.onrender.com)

---

## 🛠 Features

- Recommend books based on user preferences  
- Popularity-based and collaborative filtering recommendation  
- Uses pre-trained models (`.pkl` files) for fast predictions  
- Built with Python, Flask, and Pandas  

---

## 📓 Jupyter Notebook

The repository includes `book_recommender.ipynb` demonstrating:

- Loading and exploring datasets: `books.csv`, `users.csv`, `ratings.csv`  
- Cleaning and checking for missing/duplicate values  
- Popularity-based recommendation system  
- Collaborative filtering recommendation system  
- Saving processed data and models using pickle (`popular.pkl`, `pt.pkl`, `books.pkl`, `similarity_scores.pkl`)  

**Example usage:**

```python
from notebook import recommend

recommend('1984')
# Example output:
# [
#   ['Animal Farm', 'George Orwell', 'http://images.amazon.com/...'],
#   ["The Handmaid's Tale", 'Margaret Atwood', 'http://images.amazon.com/...'],
#   ['Brave New World', 'Aldous Huxley', 'http://images.amazon.com/...'],
#   ['The Vampire Lestat', 'ANNE RICE', 'http://images.amazon.com/...']
# ]
