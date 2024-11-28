# 🎵 Music Recommendation System  

This project is a machine learning-powered **Music Recommendation System** built and deployed using **Streamlit**. The system provides personalized music recommendations by clustering songs based on user preferences. It leverages the **K-Means clustering algorithm** and calculates similarity using **Euclidean distance**.

You can access the live, deployed app here:  
👉 [Music Recommendation System - Streamlit App](https://music-recomendation-system-7zukmujcfsxxtappgzo9b3a.streamlit.app/)

---

## 🌟 Features
- **Data Transformation**: Converts unstructured data into structured data for analysis.
- **Interactive User Interface**: An easy-to-use interface built with Streamlit.
- **Music Clustering**: Groups songs into clusters based on features like genre, tempo, and other metadata.
- **Personalized Recommendations**: Suggests songs similar to a user's selected track.
- **Efficient Similarity Calculation**: Uses Euclidean distance for finding song similarities.

---

## 🚀 How It Works
1. **Data Collection**:
   - Music data was obtained from Dropbox as unstructured data.
   - The data was preprocessed and converted into a structured format (e.g., CSV).
2. **Feature Engineering**:
   - Extracted relevant features from the dataset, such as tempo, genre, and pitch-related attributes.
3. **K-Means Clustering**:
   - Grouped songs into clusters based on their attributes.
   - Each cluster represents songs with similar characteristics.
4. **Recommendation Engine**:
   - When a user selects a song, the app identifies its cluster.
   - Recommendations are made from the same cluster using Euclidean distance for similarity ranking.

---

## 📦 Installation and Setup
Follow these steps to run the app locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/music-recommendation-system.git
   cd music-recommendation-system
   ```

2. **Install Dependencies**:
   Create a virtual environment and install the required packages.
   ```bash
   python -m venv env
   source env/bin/activate  # Use `env\Scripts\activate` on Windows
   pip install -r requirements.txt
   ```

3. **Run the App**:
   ```bash
   streamlit run app.py
   ```

4. **Access the App**:
   Open your browser and navigate to `http://localhost:8501`.

---

## 🛠 Tools and Technologies
- **Programming Language**: Python
- **Framework**: Streamlit
- **Algorithms**: K-Means Clustering, Euclidean Distance
- **Data Preprocessing**: Conversion of unstructured data into structured formats.
- **Libraries**: 
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `librosa` (if working with audio features)
  - `matplotlib` (for visualizations)

---

## 📂 Project Structure
```
music-recommendation-system/
│
├── app.py                 # Streamlit app code
├── data/
│   └── songs_data.csv     # Preprocessed structured dataset
├── models/
│   └── kmeans_model.pkl   # Pre-trained K-Means model (if applicable)
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## ✨ Key Highlights
- **Data Transformation**: Preprocessed unstructured music data into a structured dataset suitable for machine learning.
- **Unsupervised Learning**: Demonstrates clustering for recommendation systems.
- **Customizable Recommendations**: Flexible system that can adapt to new datasets or features.
- **Scalable Deployment**: Deployed using Streamlit for easy accessibility and scalability.

---

## 🖼 Demo
![App Screenshot](screenshot.png)  
*A screenshot or GIF of the app in action.*

---

## 🧑‍💻 Author
Developed by **[Afolabi Azeez](https://github.com/afolabi022)**.  
Feel free to connect with me for feedback or collaboration.

---

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
