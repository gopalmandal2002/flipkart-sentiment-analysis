# Flipkart Sentiment Analysis 📊
##OBJECTIVE
A sentiment analysis project on Flipkart product reviews using Python NLP techniques and a Power BI dashboard.

## 🔍 Overview
- Analyzed 20,000+ reviews using TextBlob & VADER
- Preprocessing: tokenization, lemmatization, stopword removal
- Classification into Positive, Neutral, and Negative
- Power BI dashboard with filters: Product, Rating, Sentiment
  
## 📝 Project Process: Flipkart Review Sentiment Analysis & Dashboard
- 1. Data Collection
-Collected customer review data from Flipkart, including columns like Product_Name, Review, and Rating.
-2. Data Preprocessing (Google Colab using Python)
-Removed missing values and duplicate reviews.
-Performed text cleaning:
-Lowercased all text
-Removed stopwords, punctuations, and special characters
-Applied stemming using NLTK's PorterStemmer
-3. Sentiment Prediction
-Used TextBlob to calculate polarity:
Polarity > 0 → "Positive"
Polarity = 0 → "Neutral"
Polarity < 0 → "Negative"
Stored the sentiment result in a new column: Predicted_Sentiment
Saved the final DataFrame to a CSV: flipkart_sentiment_results.csv
-4. Power BI Dashboard Creation
Imported the flipkart_sentiment_results.csv file into Power BI.
🔸 Created Key Visuals:
Bar Chart for product-wise sentiment distribution.
Pie Chart to display sentiment percentage.
Stacked Column Chart for Rating vs Sentiment overview.
Slicers for dynamic filtering:
Product_Name
Rating
Predicted_Sentiment
🔸 KPI Cards (Quick Summary):
Created 4 card visuals for at-a-glance insights:
👍 Total Positive Reviews → Count of "Positive" from Predicted_Sentiment
👎 Total Negative Reviews → Count of "Negative" from Predicted_Sentiment
⭐ Average Rating → Average of Rating
📦 Total Products → Distinct count of Product_Name
🔸 Visual Formatting:
Used Segoe UI Bold for slicer titles.
Background color-coded based on sentiment:
✅ Positive → #c8e6c9 (Green)
🟨 Neutral → #fff9c4 (Yellow)
❌ Negative → #ffcccc (Red)


## datasets
<a href="https://github.com/gopalmandal2002/flipkart-sentiment-analysis/blob/main/flipkart.csv">Dataset</a>
<a href="https://github.com/gopalmandal2002/flipkart-sentiment-analysis/blob/main/archive%20(2)%20(1).zip">RAW DATASET</a>
<a href="https://github.com/gopalmandal2002/flipkart-sentiment-analysis/blob/main/flipkart_sentiment_results%20(2).csv">RESULT</a>
## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- TextBlob, VADER
- Seaborn, Matplotlib
- Power BI
## 📊 Dashboard Preview
<img width="1329" height="732" alt="deshboard (1)" src="https://github.com/user-attachments/assets/57701d40-25ea-44e4-8e20-29423cd239a9" />

## 🔗 How to Use
1. Open the notebook
2. Run all cells
3. View interactive Power BI insights from exported CSVs


