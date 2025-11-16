 📊 Customer Sentiment Analysis — iPhone 15 (128GB) Flipkart Reviews

This project performs end-to-end sentiment analysis on customer reviews of the iPhone 15 (128GB) scraped from Flipkart.
It includes web scraping, data cleaning, preprocessing, sentiment scoring, visualization, and insights generation.

🚀 Project Objective

To extract customer reviews from Flipkart and analyze them using NLP techniques to understand customer sentiment, identify key themes, and derive meaningful business insights.

🧰 Tech Stack & Libraries
Languages & Tools

Python

Jupyter Notebook

Selenium (Web Scraping)

BeautifulSoup

NLTK

TextBlob

Pandas, NumPy

Matplotlib, Seaborn

🕸️ 1. Web Scraping

The project uses Selenium WebDriver to:

Load product review pages on Flipkart

Extract reviewer details, ratings, and review text

Store the scraped results in a dataframe

Key Steps:

Launch browser driver

Loop through multiple review pages

Extract and clean raw HTML

Save dataset for analysis

🧹 2. Data Cleaning & Preprocessing

The dataset undergoes several preprocessing steps:

Removing duplicates

Converting text to proper case

Cleaning city/author fields

Removing unwanted characters

Tokenizing review content

Creating additional derived columns:

Reviews_t — tokenized sentences

Review_Length — word count

Polarity — sentiment score

Sentiment_Class — negative / neutral / positive

🧠 3. Sentiment Analysis

Using TextBlob, the project computes:

Polarity Score (−1 to +1)

Sentiment Category

Negative

Neutral

Positive

A helper function was used to classify polarity ranges into categories.

Average Polarity Score is also calculated to understand overall sentiment trends.

📈 4. Data Visualization

The notebook generates visual insights such as:

Distribution of sentiment categories

Polarity score histogram

Review length analysis

Bar charts highlighting sentiment proportions

These help in understanding how customers feel about:

Product quality

Price

Performance

Delivery experience

🔍 5. Key Insights (Sample)

(You can add your actual findings here.)

Most reviews lean towards positive sentiment.

Common praise: camera quality, design, performance.

Negative patterns relate largely to delivery delays or overheating concerns.
