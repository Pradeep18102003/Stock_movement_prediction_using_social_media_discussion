# 📊 Stock Movement Prediction using Social Media Sentiment

This project predicts **stock market movements** based on **sentiment analysis** from social media discussions on **Reddit**. It leverages **BERT embeddings**, **VADER sentiment analysis**, and **CNN models** to generate predictions.

---

## 📖 Table of Contents
- [🚀 Installation](#-installation)
- [📁 Project Structure](#-project-structure)
- [▶️ How to Run the Code](#-how-to-run-the-code)
- [📊 Results](#-results)
- [🔍 Future Work](#-future-work)
- [📧 Contact](#-contact)

---

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pradeep18102003/Stock_movement_prediction_using_social_media_discussion.git
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up API keys (if required):**
   - Create a Reddit app and obtain API credentials for data scraping.

---

## 📁 Project Structure

```
├── data/                 # Contains datasets
├── notebooks/            # Jupyter notebooks for data processing & modeling
├── requirements.txt      # List of dependencies
└── README.md             # Project documentation
```

---

## ▶️ How to Run the Code

1. Ensure all required libraries from `requirements.txt` are installed.

2. Obtain **Reddit API** credentials by creating a Reddit app.

3. Run the notebooks in the specified order:

   1. **Data_Scraping_from_Reddit**: 
      - Scrapes data from Reddit.
      - Outputs `Reddit_data.csv` (saved in the `data/` folder).
   
   2. **Stock_Movement_Data**: 
      - Scrapes stock movement data for **S&P 500**.
      - Outputs `Stock_Movement.csv` (saved in the `data/` folder).

   3. **Baseline_Model**: 
      - Implements a baseline model for stock movement prediction.

   4. **Model_Code**: 
      - Trains CNN models using BERT embeddings and VADER sentiment scores.
      - Outputs accuracy metrics for both models.

---

## 📊 Results

- **Baseline Model Accuracy:** 53.5%

- **CNN Model (without Sentiment Scores) Accuracy:**
  - Train set: 72.97%
  - Test set: 66.44%

- **CNN Model (with Sentiment Scores) Accuracy:**
  - Train set: 76.18%
  - Test set: 65.77%

---

## 🔍 Future Work

- **Enhanced Data Collection:**
  - Expand dataset by scraping more Reddit data (requires a paid subscription for higher data limits).

- **Model Optimization:**
  - Fine-tune hyperparameters for better generalization and accuracy.
  - Explore transformer-based architectures (e.g., RoBERTa, DistilBERT) for improved sentiment understanding.

- **Feature Engineering:**
  - Incorporate additional sentiment signals (e.g., post upvotes, comment volume) to enrich the dataset.

- **Deployment:**
  - Package the model as an API for real-time stock movement predictions.

---

## 📧 Contact

- **Email:** pradeep18kumar10@gmail.com
- **LinkedIn:** [Pradeep Kumar](https://www.linkedin.com/in/pradeep-kumar-bba090320/)

Feel free to reach out for questions, suggestions, or collaborations!
