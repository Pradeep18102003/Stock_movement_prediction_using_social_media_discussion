# Stock Movement Prediction using Social Media Sentiment

This project predicts stock market movements based on sentiment analysis from social media discussions using Reddit. It combines BERT embeddings, VADER sentiment analysis, and CNN models to achieve predictions.

## Table of Contents
- [Installation](#installation)
- [Project Structure](#project-structure)
- [How to run the code](#How-to-run-the-code)
- [Results](#results)

## Installation
1. Clone the repository:
   ```bash
   git clone (https://github.com/Pradeep18102003/Stock_movement_prediction_using_social_media_discussion.git)
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   ## Project Structure
- `data/`: Contains datasets
- `notebooks/`: Jupyter notebooks for analysis
- `requirements.txt`: Dependencies

   ## How to run the code
- First you need to install the libraries in requirements.txt file
- In Notebooks folder there will four notebooks you need to run the notebooks in the same order
     - First Notebook is Data_Scrapping_from_Reddit this notebook has the code to scrape data from reddit and will give a file Reddit_data.csv that will be saved in Data folder
     - Second Notebook which Stock_Movement_data this has the code to scrape the stock movement data of **S&P500** and give a csv file Stock_Movement.csv
     - Third Notebook has the baseline model
     - Fourth Notebook is the model codel it will create CNN models based on the data we got above and gives the accuracy


   ## Results:

  - Baseline model accuracy: 53.5%
  - CNN model without Sentiment Scores accuracies
    - Train set: 72.97%
    - Test set: 66.44%
  - CNN model with Sentiment Scores accuracies
    - Train set: 76.18%
    - Test set: 65.77%

