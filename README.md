# Covid-19-Analysis

### 1. Covid-19 Human Behaviour Analysis: A creative Reseach
##### (A) Description:
- Herd Behavior is commonly used in Financial Markets to predict uncertainty. 
- Common Models : Econometrics Regression  and Time Series 
- Research Value :  Very Rarely applied in the Covid-19 Mobility case but Human behavior uncertainty affects the policy effectiveness 

#### (B) Model:
- Baseline Model : Bayesian Ridge Regression

---
### 2. Covid-19 Sentiment Analysis: A Chinese NLP Study
##### (A) Description:
- 数据集依据与“新冠肺炎”相关的230个主题关键词进行数据采集，抓取了2020年1月1日—2020年2月20日期间共计100万条微博数据，并对其中10万条数据进行人工标注，标注分为三类，分别为：1（积极），0（中性）和-1（消极）
- 评价指标 Evaluation Matrix: Macro-F1 score

#### (B) Model:
- 数据预处理：分词，去重复，去同义词
- Machine Learning Model: Naive Bayes, Logistic regression -> result F1 score : 0.74
- Deep Learning Model：RNN (RNN+LSTM)， CNN

