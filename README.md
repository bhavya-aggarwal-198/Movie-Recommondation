\# 🎬 Movie Recommendation System



An AI-powered Movie Recommendation System built using \*\*FastAPI\*\*, \*\*Streamlit\*\*, and \*\*Machine Learning\*\*. The application recommends movies using \*\*TF-IDF-based content similarity\*\* and \*\*genre-based recommendations\*\*, while also integrating with the \*\*TMDB API\*\* to fetch movie details, posters, and metadata.



\---



\## ✨ Features



\* 🔍 Search movies by title using TMDB API

\* 🎬 View movie details, posters, and release information

\* 🤖 TF-IDF based content recommendation engine

\* 🎭 Genre-based movie recommendations

\* 🖥️ Interactive and responsive Streamlit interface

\* ⚡ FastAPI backend for high-performance API endpoints



\---



\## 🛠️ Tech Stack



\### Frontend



\* Streamlit



\### Backend



\* FastAPI

\* Uvicorn



\### Machine Learning \& Data Processing



\* Pandas

\* NumPy

\* Scikit-learn

\* NLTK



\### External API



\* TMDB (The Movie Database) API



\---



\## 📂 Project Structure



```text

movie-recommendation/

│

├── app.py                 # Streamlit frontend

├── main.py                # FastAPI backend

├── df.pkl                 # Processed movie dataset

├── indices.pkl            # Movie index mapping

├── tfidf.pkl              # TF-IDF vectorizer

├── tfidf\_matrix.pkl       # TF-IDF matrix

├── requirements.txt

├── README.md

└── .env

```



\---



\## 🚀 Installation



\### Clone the repository



```bash

git clone https://github.com/bhavya-aggarwal-198/Movie-Recommondation.git

cd Movie-Recommondation

```



\### Install dependencies



```bash

pip install -r requirements.txt

```



\### Create a `.env` file



```env

TMDB\_API\_KEY=your\_tmdb\_api\_key

```



\---



\## ▶️ Running the Project



\### Start the FastAPI backend



```bash

uvicorn main:app --reload

```



\### Start the Streamlit frontend



```bash

streamlit run app.py

```



\---



\## 🧠 Recommendation System



The recommendation engine uses:



\* \*\*TF-IDF Vectorization\*\* to identify content similarity between movies.

\* \*\*Cosine Similarity\*\* to recommend movies with similar descriptions and features.

\* \*\*Genre-Based Recommendations\*\* using TMDB data.



\---





\## 🙏 Acknowledgements



\* The UI design and certain frontend implementation ideas were developed with assistance from AI tools for faster prototyping.

\* The complete recommendation engine, including data preprocessing, feature engineering, TF-IDF model training, recommendation logic, and project architecture, was independently designed and implemented by me.



\---



\## 👨‍💻 Author



\*\*Bhavya Aggarwal\*\*



If you like this project, feel free to ⭐ the repository.



