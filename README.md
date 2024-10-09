# Music Recommendation System 🎶

This project is a **Music Recommendation System** developed as part of a task from **CodeAlpha**. The system analyzes song features and recommends similar tracks based on the user's preferences, using clustering and distance-based algorithms.

## Project Overview

The Music Recommendation System uses a combination of **K-Means Clustering**, **t-SNE**, and **PCA** for feature reduction, along with distance metrics such as **Hamming**, **Cosine**, and **Euclidean** to recommend songs that align with a user's music taste.

### Features

- **Personalized Music Recommendations**: Provides song recommendations based on user preferences.
- **Advanced Data Analysis**: The project uses **Pandas** and **NumPy** for data handling, and **Matplotlib**, **Seaborn**, and **Plotly** for data visualization.
- **Innovative Distance Metrics**: Leverages **Cosine**, **Hamming**, and **Euclidean distances** for song similarity analysis.

## Tech Stack & Tools 🛠️

- **Python**: Main programming language
- **Pandas & NumPy**: For data manipulation and analysis
- **Matplotlib, Seaborn, Plotly**: For data visualization
- **Scikit-learn**: For machine learning algorithms
- **Yellowbrick**: For feature correlation analysis
- **SciPy**: For spatial distance metrics
- **Jupyter Notebook**: For interactive development and testing
- **Git**: For version control

## LinkedIn Share
I've shared this project on my [LinkedIn profile](https://www.linkedin.com/in/alirizalaçin) where you can find more information and updates on my work.

## Getting Started 🚀

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ali-RzA7/CodeAlpha_Music_Recommendation_System.git
   cd CodeAlpha_Music_Recommendation_System
2. **Run the project: Launch Jupyter Notebook and open the .ipynb file:**
   ```bash
   jupyter notebook
3. **Prepare the Dataset:** Download the dataset containing song features and place it in the data folder. This should include attributes like danceability, energy, valence, and others.

## Example Usage
  ```python
  # Example usage
  song_name = "Shape of You"
  recommendations = Content_filter_music_recommender(song_name, 5)
  print(recommendations)

