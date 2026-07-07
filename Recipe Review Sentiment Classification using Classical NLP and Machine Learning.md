# 🍽️ Recipe Review Sentiment Classification using Classical NLP and Machine Learning

##### 

##### 📖 Project Overview



This project demonstrates an end-to-end Natural Language Processing (NLP) workflow for sentiment classification using recipe reviews. It explores how classical machine learning techniques can be used to classify user sentiment while addressing real-world challenges such as highly imbalanced datasets.

Originally developed as the final project for the ReDI School Machine Learning Program, the project was later refined to improve its organization, documentation, visualizations, and overall presentation for a professional portfolio.



##### 🧰 Technologies



Python • Pandas • NumPy • Scikit-learn • NLTK • Matplotlib • Seaborn • SMOTE • NLP • TF-IDF • CountVectorizer • Linear SVC



##### 🎯 Business Problem



Online recipe platforms rely on user reviews to understand customer satisfaction, improve recipe recommendations, and identify quality issues.



The objective of this project is to build and evaluate machine learning models capable of predicting review sentiment while comparing different text representation techniques and strategies for handling class imbalance.



##### 📊 Dataset



Source: UCI Machine Learning Repository

Size: 18,182 recipe reviews



The dataset includes:



* Review text
* Star ratings
* User reputation
* Recipe information
* User engagement metrics
* Timestamps



##### 🛠 Project Workflow



The project follows a complete NLP pipeline:



* Data cleaning and feature engineering
* Exploratory Data Analysis (EDA)
* Text preprocessing:

  * Tokenization
  * Lowercasing
  * Stopword removal
  * Lemmatization



* Lexicon-based sentiment analysis using VADER
* Text vectorization:

  * CountVectorizer
  * TF-IDF

&#x20; 

* Multi-class sentiment classification
* Handling class imbalance using SMOTE
* Model evaluation and comparison
* Semantic similarity search using TF-IDF and cosine similarity



##### 🤖 Models Evaluated



Six-Class Rating Prediction



* Logistic Regression + CountVectorizer
* Logistic Regression + TF-IDF
* Multinomial Naive Bayes + CountVectorizer



Three-Class Sentiment Classification (After SMOTE)



* Logistic Regression
* Multinomial Naive Bayes
* Linear SVC



**Linear SVC trained on SMOTE-balanced data achieved the best overall performance (Accuracy ≈ 75%, Weighted F1 ≈ 0.78).**



##### 📈 Key Results



* The dataset is heavily imbalanced, with approximately 77% of reviews receiving the highest rating.
* Six-class rating prediction proved considerably more difficult than broader sentiment classification.
* Applying SMOTE substantially improved minority-class performance.
* Linear SVC achieved the strongest overall balance between accuracy and weighted F1 score.
* Review length and textual content provided meaningful predictive information.
* A semantic recipe search demonstration illustrates an additional practical NLP application beyond classification.







##### 💡 Machine Learning Skills Demonstrated

##### 

* Natural Language Processing (NLP)
* Text preprocessing
* Feature engineering
* Feature extraction
* Machine learning model selection
* Class imbalance handling (SMOTE)
* Model evaluation using Accuracy, Macro F1, and Weighted F1
* Data visualization
* Business-oriented interpretation of ML results



##### 🚀 Future Improvements



* Fine-tune transformer-based models (e.g., BERT)
* Perform hyperparameter optimization
* Deploy the best model as a web API
* Add explainability with SHAP or LIME
* Explore aspect-based sentiment analysis



##### 🚀 Running the Project



Clone the repository:



git clone <repository-url>



Install dependencies:



pip install -r requirements.txt



Launch Jupyter Notebook:



jupyter notebook Sentiment\\\_Analysis\\\_Notebook.ipynb





##### 📦 Main Libraries



Data Analysis



* pandas
* numpy



Visualization



* matplotlib
* seaborn



NLP



* nltk
* CountVectorizer
* TF-IDF
* VADER



Machine Learning



* scikit-learn
* imbalanced-learn (SMOTE)







##### 🤝 Project Evolution







This project was originally developed as the final project for the ReDI School Machine Learning Program.



After completing the course, it was revisited and enhanced to improve:



* notebook organization
* documentation
* code readability
* visualizations
* business interpretation
* overall presentation quality



The core machine learning methodology and experimental results remain consistent with the original work.



##### 🤖 Use of AI Tools



AI tools (including ChatGPT and DeepSeek) were used as development assistants to support:



* debugging Python code
* improving notebook structure and documentation
* refining explanations and project presentation
* reviewing code for clarity and readability



All machine learning experiments, implementation decisions, model evaluation, and final validation were completed by the author.



























