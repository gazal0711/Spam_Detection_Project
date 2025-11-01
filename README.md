# SMS Spam Detection System

## Introduction  
The SMS Spam Detection System leverages machine learning to identify whether an incoming SMS is spam or legitimate. Designed using Python and deployed via Streamlit, this solution is both efficient and user-friendly, making it accessible for a wide range of applications.  

---

## Key Highlights  

### Tools and Libraries  
- **Programming Language**: Python  
- **Libraries Used**: Scikit-learn, Pandas, NumPy, and Streamlit  

### Core Features  
1. **Data Collection**: Integrates a labeled dataset of SMS messages.  
2. **Text Processing**: Applies advanced natural language processing (NLP) techniques for message cleaning and transformation.  
3. **Modeling**: Incorporates multiple machine learning algorithms to identify the most accurate classifier.  
4. **Web Interface**: User-friendly web app for real-time predictions.  

---

## Dataset Overview  
The SMS Spam Collection dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset), consists of 5,500+ messages labeled as either spam or legitimate.  

### Data Preparation  
1. **Cleaning**: Removed duplicates, addressed missing values, and standardized text by converting it to lowercase.  
2. **Preprocessing**:  
   - Tokenization: Breaking down messages into individual words.  
   - Removal: Eliminated stop words, special characters, and punctuation.  
   - Stemming: Reduced words to their root forms.  

---

## Insights Through Data Analysis  
Comprehensive exploratory data analysis (EDA) was conducted to understand the characteristics of the dataset:  
- **Textual Metrics**: Analyzed word count, character count, and sentence length distributions.  
- **Visualization**: Utilized bar charts, pie charts, and heatmaps for insights.  
- **Word Clouds**: Generated word clouds for spam and legitimate messages, highlighting frequently used terms.  

---

## Machine Learning Approach  
Various classifiers were evaluated for performance, including:  
- Naive Bayes  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Decision Trees  
- Logistic Regression  
- Extra Trees Classifier  
- Support Vector Classifier (SVC)  

The model with the highest precision (achieving 100%) was selected for deployment.  

---

## Deployment with Streamlit  
The SMS Spam Detection model is deployed as an interactive web app using Streamlit. Users can input an SMS into the app's interface, and the system will instantly classify it as spam or legitimate.  

 

---

## How to Use Locally  
Follow these steps to run the project on your local machine:  
1. Clone the repository.  
2. Install the required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Launch the app:  
   ```bash  
   streamlit run app.py  
   ```  
4. Open your browser and navigate to `localhost:8501`.  

---

## Contribute  
We welcome contributions to improve this project! Feel free to:  
- Open issues for bugs or feature requests.  
- Submit pull requests with enhancements or fixes.  

