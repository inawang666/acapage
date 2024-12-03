---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

 <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
---

# Welcome to my page! 🔥 🎉

My research interest includes natural language and its processing from different perspectives. Here are some details about me.

# 📖 Education
- *2011.09 - 2014.06*, Lu’an First Middle School, Lu’an, Anhui, China. 

- *2014.09 - 2018.07*, Anhui University of Technology(AHUT). **B.L**, English Language and Literature (GPA: 90.50/100.00).

- *2019.09 - 2022.07*, University of Chinese Academy of Sciences(UCAS). **M.A**, Linguistics and Applied Linguistics in Foreign Languages (GPA: 3.64/4.00)

# Languages
- the highest levels (“Excellent”) in TEM-4 and TEM-8 (Test for English Major)
- Shanghai Advanced Interpretation Certificate (translation)
- studied German as the 3rd language and know some Japanese (e.g., recitation of a German poem in the department official account https://mp.weixin.qq.com/s/hW8ibLhZ4_QPSmXEugP7QA)
- TOEFL iBT score: 104 (Home Edition) (Reading 29, Listening 27, Speaking 21, Writing 27) 
- passed Visual Basic prog Grade 2 (95/100)
- able to program in languages such as python and C++.

# 💻 Research
## 1. Selected Projects

### *2014.09 - 2018.07 (AHUT)*

### **Project 1**
- Thesis: **On English Translation Strategies of Passive Sentences from the Perspective of Figure-Ground Theory - A Case Study of English Translation of *Zhuangzi***
- (dis)similarities of translation strategies of Old Chinese passives in two English versions 
- results: the translation conforms to the salience principle of figure-ground theory

<div class='paper-box'><div class='paper-box-image'><div><img src='images/zhuangzi.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### **Project 2**
- **RoboCup Simulation 2D Soccer Competition** (top 2-5% among all academic competitions)
- mainly responsible for **Team Description Paper (TDP)** translation in Yushan2015, Yushan2018, etc.(📝 publications: http://archive.robocup.info/Soccer/Simulation/2D/TDPs/RoboCup/)

### **Project 3**
- one of the project leaders in the National College Student Innovation and Entrepreneurship Training Project
- **the learning pattern of interpretation major and the demand for professional interpreters in the market**
- main contribution: questionnaire design and collection

### *2019.09 - 2022.07 (UCAS)*
### **Project 4**
- researcher for being part of a Beijing Municipal Humanities and Social Sciences Project
- Thesis: **Media Depictions of Chinese International Students in UK Newspaper Coverage (2006-2020): A Discourse-Historical Approach** (📝 publications: paper under review, first author)

### **Project 5 (mini)**
- [psycholinguistic experiment about **associative vocabulary recognition of Chinese students**](https://github.com/inawang666/naive-JATOS-psychoexperiment)
- collect online keyboard and button responses of the participants with jsPsych and ngrok tool on JATOS; analyze the CSV file downloaded from the database 

## 2. Selected Experiments
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

# Activities
## 1. Academic Activities
- 2020.10
became a member of the Special Committee of Language, Literature and Science studies affiliated with **Chinese Society for the History of Science and Technology**

### 💬 Invited Talks
- 2021.04
invited to report at the high-level **Forum of Language Data Application & the Corpus Research Center Opening Ceremony of China Three Gorges University**
- 2021.11
invited to report at **the Ninth International Academic Symposium on Contemporary Chinese New Discourses & the Second International Discourse Studies Frontier Conference**

- research & teaching assistant for UCAS undergraduates and graduates

## 2. Social Activities
### *2014 - 2016*
- participated in some volunteer activities (e.g. removing advertisements on walls, picking up trash on roads, etc.)
### 2018 - 2019
- donated some money to non-profit platforms such as **UNICEF** and **Shuidichou** to help the poor
- *2019 - 2020*
- became an editor of the department official account & actively promoted linguistic classics
### *2020 - 2021*
- volunteered for the school library to carry out **Red Classics Recitation activity** by punching time clocks online & engaged in the interaction with participants positively
- volunteered for **Babaoshan Revolutionary Cemetery services** in Shijingshan district & organized the distribution of materials and equipment to participants
- volunteered for the 2021 **online academic summer camp** of the department
- participated in many inter-departmental teaching practice like visiting the **Huairou Science City**

# 🎖 Honors & Awards
- 2014 - 2015
the 1st-class **academic scholarship**
- 2015 - 2016
**Special academic scholarship**
- 2016 - 2017
the 1st-class **academic scholarship**
- 2017 - 2018
the 2nd-class **academic scholarship**
- 2019 - 2020
the 2nd-class **academic scholarship**
- 2020 - 2021
the 2nd-class **academic scholarship**
- 2021 - 2022
the 2nd-class **academic scholarship**
- 2014
**Award of Merit** in FLTRP Cup: English Department Speaking Competition
- 2015
**the runner-up in FLTRP Cup**: AHUT English Reading Competition
- 2014 - 2015
**AHUT Merit Student**
- 2015
**the champion** in provincial RoboCup Simulation 2D Soccer Competition, the 3rd place in the National Competition & the 6th place in world RoboCup Competition (team award)
- 2015
the 3rd prize
**AHUT IGEM competition** (team award)
- 2016
**the runner-up** in AHUT Handicraft Innovation Competition (team award)
- 2015 - 2016
**Outstanding League Member**
- 2021
**The Best City Volunteer** in Beijing volunteering activity for Babaoshan Revolutionary Cemetery

# Part-time Jobs
- 2014 - 2015
an summer intern in **Shanghai Xueying Clothing Factory** and a building materials market
- 2018.03
an intern, responsible for teaching, translation and interpretation (Municipal Police Station & a Sino-German company called Zhonglan-WOCO in Ma'anshan) activities, in **Margaret Culture Media Co. Ltd**. in Ma'anshan, Anhui province
- 2018.04 - 2018.05
an English teaching assistant in **Ma’anshan Qing Hong Sinology Kindergarten**
- 2018.07 - 2018.08 & 2019.01
both an English and a math teacher in **Ma’anshan Oxford Culture and Arts School**
- 2019.04 - 2019.05
a customer service intern in **Shanghai Homevoila Electronic Commerce Co. Ltd**
- 2022.06 - 2022.09
an English teacher in **Huidu International Education**, Fangshan Campus, Beijing
- 2022.09 - 2022.12
an English training teacher in **China Foreign Affairs University**
- 2022.10 - present
an English teacher in **Angel International Education**, Lugouqiao Campus, Beijing

##### ----------------bottom line's bottom line: the end----------------
