# 🎬 Movie Recommendation System

This project is a **Movie Recommendation System** built using **Python, Pandas, and Collaborative Filtering** techniques. The system analyzes user ratings and recommends movies based on similarity to other movies using correlation methods.

---

## 📌 Features
- Loads and processes movie ratings dataset.  
- Merges movie IDs with movie titles for readability.  
- Computes:  
  - Average ratings per movie  
  - Rating counts per movie  
- Uses **pivot tables** to create a user–item matrix.  
- Implements **Collaborative Filtering** with Pearson correlation to find similar movies.  
- Provides recommendations based on user preference (e.g., *Star Wars (1977)*, *Liar Liar (1997)*).  
- Includes basic **data visualization** with Matplotlib.  

---

## 🛠️ Tech Stack
- **Python 3**  
- **Libraries**:  
  - `pandas` for data handling  
  - `numpy` for numerical computations  
  - `matplotlib` for visualization  

---

## 📂 Dataset
The project uses:  
- **Ratings dataset** (`u.data`)  
- **Movie titles dataset** (`Movie_Id_Titles.csv`)  

These files are merged to map ratings with actual movie names.

---

## 🚀 How It Works
1. Load datasets using `pandas`.  
2. Merge ratings with movie titles.  
3. Explore dataset with:  
   - Average ratings per movie  
   - Number of ratings per movie  
4. Visualize popular movies using `matplotlib`.  
5. Create **user-item matrix** using `pivot_table`.  
6. Choose a movie (e.g., *Star Wars (1977)*) and compute correlations with other movies.  
7. Return top correlated movies as recommendations.  

---

## 📊 Example Output
- Top-rated movies  
- Most-rated movies  
- Recommendations like:  
  - Movies similar to *Star Wars (1977)*  
  - Movies similar to *Liar Liar (1997)*  

---

## ▶️ Usage
Clone this repository and run the notebook:

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
jupyter notebook "movie recommendation system.ipynb"
```

---

## 📌 Future Improvements
- Use **Cosine Similarity** for better performance.  
- Implement **Matrix Factorization (SVD)**.  
- Add a **Flask/Django web app** interface.  
- Deploy as a **real-time recommendation API**.  

---

## 📜 License
This project is open-source and available under the MIT License.
