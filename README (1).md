# 🎬 Personalized Movie Recommendation System

This project is a simple content-based movie recommendation system that helps users discover movies they’re likely to enjoy, based on genres and movie metadata. Built using Python and scikit-learn, this tool demonstrates how intelligent filtering can enhance the user experience in streaming platforms.

## 📌 Features

- Content-based filtering using TF-IDF vectorization and cosine similarity.
- Lightweight and fast — ideal for prototypes and demos.
- Easy to extend with more metadata (e.g., cast, directors, keywords).
- Simple user interface via function calls or integration with web apps (e.g., Flask).



### 🧪 Run on Google Colab

You can also run the notebook directly in [Google Colab](https://colab.research.google.com/):

- Upload the `Movie_Recommendation_System.ipynb` notebook.
- Run each cell to test the recommendation logic.

## ⚙️ Requirements

Install required packages:

```bash
pip install -r requirements.txt
```

## 🧠 How It Works

1. Movie genres are processed using **TF-IDF vectorization**.
2. **Cosine similarity** is calculated between all movie pairs.
3. The system suggests the top N most similar movies to a given title.

### Example

```python
recommend_movies("Toy Story (1995)", 3)
```

Returns:

```
1    Jumanji (1995)
4    Father of the Bride Part II (1995)
2    Grumpier Old Men (1995)
```

## 📂 Project Structure

```
movie-recommendation-system/
├── Movie_Recommendation_System.ipynb
├── README.md
├── requirements.txt
```

## 📈 Future Improvements

- Add collaborative filtering or hybrid methods.
- Integrate with a front-end using Flask or React.
- Deploy using Streamlit or FastAPI.

