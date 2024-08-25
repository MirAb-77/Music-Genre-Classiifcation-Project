# 🎶 Music Genre Classification Using Deep Learning 🎧

Welcome to the **Music Genre Classification** project, where the power of deep learning meets the world of music! This project explores the intricate patterns in audio data to classify music into different genres and recommends similar tracks based on an input song.

## 🎯 Project Overview

In this project, I combined the art of music with cutting-edge deep learning techniques to develop a robust system capable of identifying music genres and recommending similar songs. The project is divided into three key phases:

1. **Exploratory Data Analysis (EDA) & Visualization**
2. **Model Development & Training**
3. **Music Recommendation System**

## 🛠️ Technologies and Concepts

This project leverages a variety of deep learning models and data visualization techniques:

### 1. **Exploratory Data Analysis (EDA)**
   Before diving into modeling, I performed a thorough EDA to understand the audio features better. I used various plotting methods to visualize the sound:

   - **Waveplot**: Visualizes the raw waveform, giving an insight into the audio signal's amplitude over time.
   - **Mel Spectrogram**: Converts the audio signal into a visual representation, showcasing the intensity of different frequencies over time.
   - **Audio Segment Signal**: Focuses on specific segments of the audio to analyze detailed sound patterns.
   - **Chroma Features & Spectral Roll-Off**: These plots provide a deeper understanding of the harmonic content and energy distribution across frequencies.

  #### 1. Waveplot & Mel Spectrogram Examples
  <img width="859" alt="p2" src="https://github.com/user-attachments/assets/0d0581d8-4c70-4e9a-827d-706c7d5bdb6f">
  
  #### 2. Spectral Roll-off & Audio Segment Example
  <img width="872" alt="p3" src="https://github.com/user-attachments/assets/7b0c67cc-f4e0-43ae-ba95-6c4e0e81775d">

  #### 3. Chroma Features
  
<img width="389" alt="Chroma Features" src="https://github.com/user-attachments/assets/79a39c43-3381-4ab2-8f7b-7c8526004007">

### 2. **Model Development**
   To classify the music genres, I implemented two deep learning models:

   - **Fully Connected Neural Network (FNN)**: This model acts as the backbone of the system, processing the extracted features to classify the music genres accurately.
   - **CNN & LSTM Hybrid Model**: By combining Convolutional Neural Networks (CNN) with Long Short-Term Memory (LSTM), this model captures both spatial and temporal patterns in the audio, leading to more accurate genre predictions.

   <img width="355" alt="Model Architecture" src="https://github.com/user-attachments/assets/d3d6e483-23d2-49f0-80cc-2a1911dec32d">


### 3. **Music Recommendation System**
   Building upon the classification model, I developed a **Music Recommendation System**. This system takes an input song and analyzes its features to find and recommend similar tracks, creating a personalized listening experience. Whether you're into jazz, rock, or EDM, this recommendation engine will curate the perfect playlist for you!

## 📊 Results and Performance

Both models were trained on a diverse dataset of music genres, achieving impressive accuracy and robustness in genre classification. The recommendation system was evaluated for its ability to match songs with similar audio features, ensuring a satisfying user experience.

## 🚀 Getting Started

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/music-genre-classification.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd music-genre-classification
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebook**:
   Open the `Music_Genre_Classification.ipynb` file in Jupyter Notebook to explore the code, visualizations, and results.

## 💡 Future Work

- **Enhanced Feature Extraction**: Implement additional audio features to further improve classification accuracy.
- **Real-Time Prediction**: Develop a real-time genre classification and recommendation system for streaming platforms.
- **User Interface**: Create an interactive web-based interface for users to upload songs and receive genre classifications and recommendations.

## 🙌 Acknowledgments

This project was a harmonious blend of my passion for music and the ever-evolving field of deep learning. Special thanks to the creators of the datasets and the open-source community for providing the tools that made this project possible.

## 📄 License

This project is licensed under the Apache 2.0 License. Feel free to fork, modify, and use it in your own projects!

