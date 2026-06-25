# Sentiment Analysis on Amazon Product Reviews

## 📌 Project Overview

This project performs Sentiment Analysis on Amazon customer reviews using Natural Language Processing (NLP). The objective is to analyze customer feedback and classify reviews into Positive, Neutral, and Negative sentiments. The project also includes data visualization and word cloud generation to better understand customer opinions.

---

## 🎯 Objectives

* Analyze customer review text from Amazon products.
* Classify reviews as Positive, Neutral, or Negative.
* Visualize sentiment distribution using charts.
* Generate word clouds to identify frequently used words.
* Extract meaningful insights from customer feedback.

---

## 📂 Dataset

**Dataset:** Amazon Product Reviews Dataset (Datafiniti)

The dataset contains:

* Product information
* Customer ratings
* Review titles
* Review text
* User information

**Review Column Used:**

* `reviews.text`

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* TextBlob
* WordCloud
* Jupyter Notebook
* VS Code

---

## 📋 Project Workflow

### 1. Data Loading

* Imported dataset using Pandas.
* Inspected dataset structure and contents.

### 2. Data Exploration

* Checked dataset shape.
* Examined column information.
* Identified missing values.

### 3. Data Cleaning

* Removed missing review records.
* Converted review text into string format.

### 4. Sentiment Analysis

* Used TextBlob to calculate sentiment polarity.
* Classified reviews into:

  * Positive
  * Neutral
  * Negative

### 5. Data Visualization

* Sentiment Distribution Bar Chart
* Sentiment Distribution Pie Chart

### 6. Word Cloud Generation

* Positive Review Word Cloud
* Negative Review Word Cloud

### 7. Insights and Conclusion

* Analyzed customer sentiment trends.
* Summarized key findings.

---

## 📊 Results

### Sentiment Distribution

| Sentiment | Number of Reviews |
| --------- | ----------------: |
| Positive  |            31,162 |
| Neutral   |             2,000 |
| Negative  |             1,497 |

The results indicate that the majority of customers expressed positive opinions about the products.

---

## 📈 Visualizations

The project includes the following visual outputs:

* Sentiment Distribution Bar Chart
* Sentiment Distribution Pie Chart
* Positive Review Word Cloud
* Negative Review Word Cloud

All generated images are stored in the `images/` folder.

---

## 🔍 Key Insights

* Positive reviews dominate the dataset.
* Customer satisfaction appears to be high.
* Negative reviews represent only a small portion of the feedback.
* Sentiment analysis helps businesses understand customer perception.
* Word clouds highlight commonly used terms in customer reviews.

---

## 🚀 How to Run the Project

1. Clone the repository.
2. Open the project in VS Code.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn textblob wordcloud
```

4. Open the Jupyter Notebook:

```text
Sentiment_Analysis.ipynb
```

5. Run all cells sequentially.

---

## 📁 Project Structure

```text
Sentiment_Analysis/
│
├── data/
│   └── 1429_1.csv
│
├── images/
│   ├── sentiment_distribution.png
│   ├── sentiment_pie_chart.png
│   ├── positive_wordcloud.png
│   └── negative_wordcloud.png
│
├── Sentiment_Analysis.ipynb
│
└── README.md
```

---

## ✅ Conclusion

This project successfully applied Natural Language Processing (NLP) techniques to analyze Amazon customer reviews. Using TextBlob sentiment analysis, customer feedback was classified into Positive, Neutral, and Negative categories. The analysis revealed that most customers had a positive experience with the products, demonstrating the effectiveness of sentiment analysis in understanding customer opinions and supporting data-driven decision-making.

## Dataset

The dataset used for this project was obtained from publicly available sources. Due to file size limitations, the dataset is not included in this repository.