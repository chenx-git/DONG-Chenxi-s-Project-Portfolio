# Project's Portfolio
### Email: chenxdong3-c@my.cityu.edu.hk


## [Project 0: CO2-Crude oil Minimum Miscibility Pressure prediction](https://researchportal.hw.ac.uk/en/publications/accurate-prediction-of-cosub2sub-minimum-miscibility-pressure-usi)
* Python and Matlab toolbox
* A two stage model to predict pressure 
  * predictor filtering: XGBoost feature importance ranking (select top 4 factors)
  * pressure prediction: Matlab ANFIS toolbox
* Tested by field data, achieved >90% accuracy
* CO2-Crude Oil MMP <br> ![](/images/0_0.png)


## [Project 1: UCI-heart-disease-prediction-Streamlit-Web-App](https://github.com/chenx-git/UCI-heart-disease-prediction-Web-App)
* A Web App built by Python Streamlit using [Kaggle UCI Heart Disease dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
* The [Web app is deployed in HEROKU](https://uci-heart-disease-streamlit.herokuapp.com/) : https://uci-heart-disease-streamlit.herokuapp.com/
* App contains 3 classifier (hyperparameters can be tuned by user):
  * SVM
  * Logistic Regression
  * Decision Tree
* The web app page view<br>![](/images/1.PNG)


## [Project 2: Medical-Notes-Entities-Extraction-and-Network-Generation](https://github.com/chenx-git/Medical-Notes-Entities-Extraction-and-Network-Visualization)
* Using ScispaCy to extract and identify entities in medical texts and generate networks visualizations
* [Data Source](https://www.kaggle.com/c/medical-notes/data)
* NLP package used--ScispaCy <br>Website: [https://spacy.io/universe/project/scispacy](https://spacy.io/universe/project/scispacy)
* Data format--text data
  * Medical note text Example:
> The patient's laryngeal area was palpated during a dry swallow and he does have significantly reduced laryngeal elevation and radiation fibrosis.  The further evaluate of his swallowing function is safety; a modified barium swallow study needs to be concluded to objectively evaluate his swallow safety, and to rule out aspiration.  A trial of neuromuscular electrical stimulation therapy was completed to determine if this therapy protocol will be beneficial and improving the patient's swallowing function and safety.
* Project Consists of: 2 jupyter notebook files
  * 1. **NLP**: from medical note text data, extract entities informaiton to edges and nodes dataframe and stored in csv --- ScispaCy 
  * 2. **Network Visualization**: build network and sub-networks to visualize the entities relationship --- NetworkX
* Some network graphs:
  
![](/images/2.1.PNG)
![](/images/2.2.png)
![](/images/2.3.PNG)


## [Project 3: Twitter sentiment analysis related to Covid-19](https://github.com/chenx-git/COVID-19-tweets-sentiment-analysis)
* Mainly use nltk library
* Datasource: [https://www.kaggle.com/gpreda/covid19-tweets](https://www.kaggle.com/gpreda/covid19-tweets)
* clean the text by:<br>  * remove url;<br>  * convert to lower case;<br>  * remove punctuations,stopwords(from nltk library package),numbers
* use SentimentIntensityAnalyzer() to generate polarity value and hence label it as:
  * positive
  * neutral
  * negative 
* The most frequent words:![highest freq word](/images/3.1.png)

* 3 types of sentiment ratio:<br>![sentiment](/images/3.2.png)

* sentiment trend:![trend](/images/3.3.png)

* wordcloud:![wordcloud](/images/3.4.png)




