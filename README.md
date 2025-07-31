# 🎵 Music Genre Classification - GTZAN Dataset

This project is part of the Elevvo ML Internship.  
It aims to classify music genres based on audio features extracted from the [GTZAN dataset](http://marsyas.info/downloads/datasets.html), using both tabular and audio-based approaches.

## 📌 Objective

Build machine learning models that can predict the genre of a song by analyzing extracted audio features and MFCCs.

## 📁 Dataset

- **Source**: GTZAN Genre Collection
- **Size**: 1000 audio tracks (30s each), 10 genres
- **Used File**: `features_30_sec.csv` (pre-extracted features)

## 🧠 Models Used

### Tabular Models
- 🎯 Logistic Regression
- 🌲 Random Forest Classifier
- 📈 Support Vector Machine (SVM)

### Audio-Based Model
- 🔊 Extracted MFCCs from uploaded audio files using `librosa`
- Used trained Random Forest model for genre prediction

## 📊 Evaluation

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ~66%     |
| Random Forest      | ~78%     |
| SVM                | ~70%     |

✅ Random Forest gave the best performance.

## 🛠️ Main Tools & Libraries
- Python, Scikit-learn, Pandas, NumPy
- Librosa (for audio analysis)
- Matplotlib & Seaborn (for visualization)
- Colab for development

## 🎧 Upload Your Own Song

The notebook supports uploading any `.wav` file from your device.  
It extracts MFCC features and predicts the genre using the trained model.

## 🖼️ Screenshots
_Add screenshots here if needed – confusion matrix, waveform, MFCC plot, etc._

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/YourUsername/music-genre-classification.git
   cd music-genre-classification
