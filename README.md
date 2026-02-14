📰 AI-Based Fake News & Misinformation Detection System
📌 Project Overview

The rapid growth of social media has accelerated information sharing worldwide. However, this has also led to the widespread circulation of fake news and misinformation, which can influence public opinion, disrupt elections, create panic, and harm social stability.

This project presents an AI-powered Fake News Detection System that automatically classifies news articles as REAL or FAKE, highlights suspicious phrases, and generates credibility explanations.

🎯 Project Objectives

The system is designed to:

✅ Accept a news article as input

✅ Classify it as REAL or FAKE

✅ Provide a confidence score

✅ Highlight suspicious words/phrases (Explainable AI using LIME)

✅ Generate a credibility explanation

✅ Display model evaluation metrics

🧠 Technologies Used

Python

Natural Language Processing (NLP)

TF-IDF Vectorization

Logistic Regression

Explainable AI (LIME)

Scikit-learn

Pandas & NumPy

📂 Dataset

Dataset used:

Kaggle – Fake and Real News Dataset

It contains:

True.csv → Real news articles

Fake.csv → Fake news articles

⚙️ System Architecture
Input News Article
        ↓
Text Preprocessing
        ↓
TF-IDF Vectorization
        ↓
Logistic Regression Classifier
        ↓
Prediction (REAL / FAKE)
        ↓
Confidence Score
        ↓
LIME Explanation (Highlighted Phrases)
        ↓
Generated Credibility Explanation

🚀 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection

2️⃣ Install Required Libraries
pip install pandas numpy scikit-learn lime

3️⃣ Place Dataset Files

Make sure the dataset files are inside:

/content/sample_data/


Or update file paths in the code accordingly.

4️⃣ Run the Project
python fake_news_detection.py

📊 Model Evaluation Metrics

The model outputs:

Accuracy

Precision

Recall

F1-Score

Example:

Accuracy  : 0.9852
Precision : 0.9821
Recall    : 0.9875
F1 Score  : 0.9848

🧪 Sample Model Interaction
🔹 Sample Input
Scientists have confirmed that drinking hot lemon water completely cures cancer within two weeks.

🔹 Output
Prediction            : FAKE
Confidence Score      : 96.45 %
Suspicious Phrases    : ['completely cures', 'confirmed', 'within two weeks']
Generated Explanation : The article is classified as FAKE with high confidence...

🔍 Explainable AI (LIME)

The project integrates LIME (Local Interpretable Model-agnostic Explanations) to:

Identify key influential words

Highlight suspicious phrases

Improve transparency of predictions

This ensures the model is interpretable and trustworthy.

📈 Key Features

✔ Automated fake news detection
✔ Confidence-based classification
✔ Explainable AI integration
✔ User input testing interface
✔ Robust CSV parsing (handles corrupted rows)
✔ Clean modular code structure

📌 Future Improvements

🔥 Upgrade to BERT / Transformer-based model

🔥 Deploy as a Web Application (Flask/Streamlit)

🔥 Add live news API integration

🔥 Multi-language support

🔥 Deep learning model (LSTM/GRU)

👨‍💻 Author

Fayas Mohammed
B.Tech Graduate | AI & ML Enthusiast

📜 License

This project is for academic and educational purposes.
