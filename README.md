# Music Recommendation System

This project is a Music Recommendation System that suggests songs based on input details provided by the user. It uses a combination of data preprocessing, feature engineering, and cosine similarity to recommend songs that closely match the user's input.

Features:
Data Cleaning: Handles missing values and standardizes data for better recommendations.
Feature Engineering: Combines attributes like Singer/Artists, Genre, and Album/Movie into a single feature for processing.
Text Vectorization: Uses TF-IDF (Term Frequency-Inverse Document Frequency) for text feature vectorization.
Similarity Computation: Calculates cosine similarity between songs to determine the most relevant recommendations.
Interactive Input: Allows users to input song details and provides top recommendations in real-time.

Installation:
  Clone this repository:
    git clone https://github.com/triptisharma27/Music-Recommendation-System-Dataset.git

  Navigate to the project directory:
    cd music-recommendation-system

  Install the required Python packages:
   pip install -r requirements.txt

Usage
  Ensure your dataset (ex.csv) is placed in the project directory.
  Run the Jupyter Notebook or execute the script:
    python Music_Recommedation_System.py
  
  Follow the prompts to enter song details:
    Singer/Artists: Name of the artist(s)
    Genre: Genre of the song
    Album/Movie: Album or movie name

  View the recommended songs based on your input.

Example
  Input:
    Singer/Artists: John Mayer
    Genre: Pop
    Album/Movie: Continuum

  Output:
    Recommended Songs:
    1. Gravity
    2. Slow Dancing in a Burning Room
    3. Your Body is a Wonderland
    4. Daughters
    5. Waiting on the World to Change

Requirements

   Python 3.x
   pandas
   scikit-learn
   numpy

Install dependencies using:
   pip install pandas scikit-learn numpy

How It Works
 Data Loading:
   Reads the dataset containing song information.
   Preprocessing: Cleans and processes text data for compatibility with the recommendation system.
   TF-IDF Vectorization: Converts text features into numerical vectors based on term frequency.
   Cosine Similarity: Computes similarity scores between the user's input and all songs in the dataset.
   Recommendation: Sorts songs by similarity score and returns the top results.

Dataset:
The dataset (ex.csv) should include the following columns:
   Song-Name: Name of the song
   Singer/Artists: Artist(s) of the song
   Genre: Genre of the song
   Album/Movie: Album or movie associated with the song
   User-Rating: User-provided rating for the song (e.g., "4.5/5")

Contributing
  Contributions are welcome! Please submit a pull request or open an issue for suggestions or improvements.

Acknowledgments

Libraries: pandas, scikit-learn, numpy

Tools: TF-IDF Vectorization, Cosine Similarity
