# Sentiment Analysis on University Course Reviews 📚🎓  

Welcome to the **Sentiment Analysis on University Course Reviews** project! This repository demonstrates how to perform sentiment analysis using **R**. Specifically, it explores techniques such as **Decision Tree** and **Support Vector Machine (SVM)** classifiers to analyze course reviews. In addition to the sentiment analysis, the project includes insightful **visualizations**, such as word clouds and data exploration, to help better understand the sentiments behind the reviews.  

---

## 📌 Features  

### 🔍 Sentiment Analysis  
- Uses **Decision Tree** and **SVM** models to classify sentiments as positive, negative, or neutral.  
- Preprocessing of text data, including tokenization, stemming, and stopword removal.  

### 🌟 Word Cloud Generation  
- Creates **word clouds** to visualize the most frequently used words in the course reviews.  
- Highlights keywords and recurring themes in the reviews.  

### 📊 Data Visualization  
- Generates a variety of visualizations using R's powerful libraries (e.g., `ggplot2`, `wordcloud2`, etc.).  
- Provides charts and graphs to analyze the distribution of sentiments and other data trends.  

---

## 📂 Project Structure  

```plaintext  
├── data/  
│   ├── course_data_clean.csv     # Cleaned and preprocessed data  
├── scripts/  
│   ├── mohinhhoa_nrc.Rmd            # Creates visualizations for insights   
│   ├── sentiment_analysis.Rmd       # Implements Decision Tree and SVM models  
│   ├── wordcloud.R                  # Generates word clouds  
├── README.md                      # Project documentation  
```  

---

## 🚀 How It Works  

1. **Data Collection**  
   - The dataset used in this project is sourced from **university course reviews**, where students shared their thoughts and feedback.  
   
2. **Preprocessing**  
   - Text data undergoes cleaning steps, including:  
     - Removing punctuation, special characters, and stopwords.  
     - Converting text to lowercase.  
     - Tokenization and stemming for more uniform analysis.  

3. **Modeling**  
   - Two machine learning models are implemented:  
     - **Decision Tree Classifier**: A simple yet interpretable model.  
     - **SVM Classifier**: A robust algorithm for classifying sentiments.  

4. **Visualization**  
   - The cleaned text data is used to generate visualizations such as:  
     - A **word cloud** to display commonly used words.  
     - **Sentiment distribution charts** to showcase the polarity of reviews.  

---

## 🛠️ Installation & Requirements  

### Prerequisites  
Make sure you have **R** installed on your system. You can download it from [CRAN](https://cran.r-project.org/).  

### Required Libraries  
The following R packages are required to run this project:  

```r  
install.packages(c("tm", "e1071", "rpart", "tidyverse", "textstem", "caret", "wordcloud2", "RColorBrewer"))  
```  

---

## 🖼️ Example Outputs  

### Word Cloud 🌤️  
![image](https://github.com/user-attachments/assets/2167b59b-5886-4d71-a4ef-376f288544b2)
 

### Sentiment Analysis Distribution 📊  
![image](https://github.com/user-attachments/assets/81ed1921-c59c-44be-94ab-8cd1dc73f364)

### Results of SVM and Decision Tree models ✍
![image](https://github.com/user-attachments/assets/e1bbaafb-7cf8-4aec-9608-e2007c6aff5e)

 

---

## 📈 Results  

- The Decision Tree model achieved an accuracy of **70.21%** on the test dataset.  
- The SVM model outperformed with an accuracy of **76.09%**, demonstrating its effectiveness in sentiment classification.  
- Word clouds and sentiment distribution charts provide clear insights into the common themes and overall sentiment of course reviews.  

---

## 📋 Future Improvements  

- Expand the dataset by incorporating reviews from multiple universities.  
- Explore advanced models, such as Random Forests or Neural Networks, for better accuracy.  
- Enhance visualizations to include interactive dashboards using tools like `shiny`.  
