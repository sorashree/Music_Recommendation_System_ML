# Music_Recommendation_System_ML

# Music Recommendation System

A machine learning-based music recommendation system built with Python and Streamlit. The application recommends songs that are similar to a song selected by the user.

# Features

*  Select a song from the available dataset
*  Get recommendations for similar songs
*  Uses content-based filtering
*  Interactive web interface built with Streamlit
*  Fast recommendations using precomputed similarity data

# Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Pickle

## 🧠 How It Works

The system uses a content-based recommendation approach.

When a user selects a song, the application compares its features with other songs using a precomputed similarity matrix. The system then returns songs that are most similar to the selected song.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the project directory

```bash
cd Music-Recommendation-System
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add the model files

The trained model files are not included directly in this repository because of their large file size.

Download the required model files from:

**[Model Files – Add Your Link Here]**

After downloading, place the files inside the `models/` directory.

### 5. Run the application

```bash
streamlit run app.py
```

The application will open in your browser.



## 🔮 Future Improvements

* Improve recommendation accuracy
* Add personalized recommendations
* Add collaborative filtering
* Integrate real-time music data
* Add user playlists and favorites
* Deploy the application online



This project was created as a learning project to explore machine learning, recommendation systems, Python, and Streamlit.
