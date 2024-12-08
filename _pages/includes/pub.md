# 📝 <span id='-publications'>Publications (and research experience)</span> 
## 🔍 1. Selected Projects

### *2014.09 - 2018.07 (AHUT)*

<div class='paper-box'><div class='paper-box-image'><div><img src='images/zhuang.png' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

### **Project 1**
- Thesis: **On English Translation Strategies of Passive Sentences from the Perspective of Figure-Ground Theory - A Case Study of English Translation of *Zhuangzi***
- (dis)similarities of translation strategies of Old Chinese passives in two English versions 
- results: the translation conforms to the salience principle of figure-ground theory
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/robo.jpg' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
### **Project 2**
- **RoboCup Simulation 2D Soccer Competition** (top 2-5% among all academic competitions)
- mainly responsible for **Team Description Paper (TDP)** translation in [Yushan2015, Yushan2018, etc.](https://archive.robocup.info/Soccer/Simulation/2D/TDPs/RoboCup/) (📝 technical reports)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/inter.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
### **Project 3**
- one of the project leaders in the National College Student Innovation and Entrepreneurship Training Project
- **the learning pattern of interpretation major and the demand for professional interpreters in the market**
- main contribution: questionnaire design and collection
</div>
</div>

### *2019.09 - 2022.07 (UCAS)*

<div class='paper-box'><div class='paper-box-image'><div><img src='images/stu.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
### **Project 4**
- researcher for being part of a Beijing Municipal Humanities and Social Sciences Project
- Thesis: **Media Depictions of Chinese International Students in UK Newspaper Coverage (2006-2020): A Discourse-Historical Approach** (📝 publications: paper under review, first author)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/mem.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
### **Project 5 (mini)**
- [psycholinguistic experiment about **associative vocabulary recognition of Chinese students**](https://github.com/inawang666/naive-JATOS-psychoexperiment)
- collect online keyboard and button responses of the participants with jsPsych and ngrok tool on JATOS; analyze the CSV file downloaded from the database 
</div>
</div>

## 🔍 2. Selected Experiments
### *2022.07-present*
### **Experiment 1**
- **Transformer-based English to French Machine Translation**
- a Seq2Seq model using Transformer architecture (Position embedding, Encoder, Decoder, multi-head attention)
- a Fra2Eng dataset from the Tatoeba Project
- results: training loss: 0.032, test score (BLEU) : 0.586.

### **Experiment 2**
- **Automatic Spam Detection System**
- a spam classifier using Multinomial Naïve Bayes, and logistic regression with
different feature extraction methods
- SMS Spam Collection dataset
- results: CountVectorizer outperformed TfidfVectorizer for both classifiers; logistic regression outperformed Naïve Bayes for both vectorizers; training accuracy: 99.38%, test accuracy: 98.64%.

### **Experiment 3** 
- **Data Mining of Commodity Information**
- Kaggle Mercari Price Suggestion Challenge
- visualize price distribution of shipping, item category, brand and item descriptions
- generate word clouds of top 100 frequent key words for different categories
- narrow down the key words with TF-IDF, and visualize key words of 2D after TruncatedSVD (aka LSA) and further reduction via TSNE
- cluster item descriptions with KMeans, and topics of top 10 key words via LDA.

### **Experiment 4**
- **Industrial Steam Capacity Prediction**
- Alibaba Cloud Tianchi Challenge
- linear regression with comparisons between Z-score and MaxMin normalization, and between Lasso, Ridge, and ElasticNet regularization
- results: linear regression without any processing has most loss (3.0896); z-score (0.3236), and ElasticNet (0.1277) is better than others in both own groups; Z-score + ElasticNet (0.2778) is the best, but only slightly better than Z-score + Lasso (0.2759)
- further improvement: EDA, stacking, Random Forest, XGBoost...

### **Experiment 5**
- **Charges Prediction of China Life Insurance (Group) Company**
- EDA: use seaborn to visualize all relevant features; features engineering: drop unimportant features (“sex”, “region”); convert discrete features (“bmi”, “smoker”) into one-hot encodings; increase feature dimensions (polynomial degree=2), and compare linear regression and ElasticNet methods for polynomials
- results: pure linear regression is better. R2 scores of training and test is 0.88 and 0.86, better than ElasticNet’s 0.83 and 0.80.

### **Experiment 6**
- **Loan Disbursing Prediction for Banks**
- use dataset of Analytics Vidhya Data Hackathon to build a XGBoost classifier with optimal hyperparameters (e.g., max_depth, min_child_weight, gamma, and reg_alpha) through Grid Search cross validation
- results: after grid search, training (test) AUC decreased from 0.9296 (0.8464) to 0.8575 (0.8385); after learning rate and tree number adjustment (0.2; 31), both training (0.9301) and test AUC scores (0.8390) outperformed results before searches; almost no differences between training (test) accuracies (98.41%) before and after optimizations.
 
### **Experiment 7**
- **Relevance of Movie with Different Genres**
- MovieLens ml-latest-small movie dataset
- one-hot encoding for the feature “genres”
- get frequent itemsets of movies via apriori algorithm; apply association rules to the sets and get related movies
- results: there are 45 itemsets when min_support is 0.025; “Children” and “Animation” has the highest association (when lift > 4, num_itemsets=3); “Children” are also associated with other genres in 362 movies (3.72% of all).

### **Experiment 8**
- [**Online Auto-System of Solving Rubik’s Cube**](https://github.com/12hyhy12/softwareproject)
- co-developer, mainly responsible for front-end coding
- JavaScript (bootstrap, Three WebGL, TouchSlide), HTML5 (WebGL), CSS
- results: interactive Cube introduction and solving webpages.
