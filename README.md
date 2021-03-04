# chenx_Portfolio
some data science project 

# [Project 1: UCI-heart-dosease-prediction-Web-App](https://github.com/chenx-git/UCI-heart-disease-prediction-Web-App)
<li>A Web App built by Python Streamlit using Kaggle UCI Heart Disease dataset:
<br>URL: https://www.kaggle.com/ronitf/heart-disease-uci
  
<li>The app is deployed in HEROKU: https://uci-heart-disease-streamlit.herokuapp.com/

<li>App contains 3 classifier (hyperparameters can be tuned by user):

  * SVM

  * Logistic Regression

  * Decision Tree

<li>The web app page view
  
![screenshot](https://github.com/chenx-git/chenx_Portfolio/blob/main/images/1.1.png)
![confusion matrix](https://github.com/chenx-git/chenx_Portfolio/blob/main/images/1.2.png)



# [Project 2: Medical-Notes-Entities-Extraction-and-Network-Generation](https://github.com/chenx-git/Medical-Notes-Entities-Extraction-and-Network-Visualization)
<li>Using ScispaCy to extract and identify entities in medical texts and generate networks visualizations
<li>Data Source---https://www.kaggle.com/c/medical-notes/data
NLP package used--ScispaCy <br>Website: https://spacy.io/universe/project/scispacy
<li>Data format--text
  
  * Text Data Example:
> The patient's laryngeal area was palpated during a dry swallow and he does have significantly reduced laryngeal elevation and radiation fibrosis.  The further evaluate of his swallowing function is safety; a modified barium swallow study needs to be concluded to objectively evaluate his swallow safety, and to rule out aspiration.  A trial of neuromuscular electrical stimulation therapy was completed to determine if this therapy protocol will be beneficial and improving the patient's swallowing function and safety.



<li>Project Consists of: 2 jupyter notebook files
  * 1. **NLP**: from medical note text data, extract entities informaiton to edges and nodes dataframe and stored in csv --- ScispaCy 
  * 2. **Network Visualization**: build network and sub-networks to visualize the entities relationship --- NetworkX


<li>Some network graphs:
  
![overall network](https://github.com/chenx-git/chenx_Portfolio/blob/main/images/2.1.png)
![abd sub network](https://github.com/chenx-git/chenx_Portfolio/blob/main/images/2.2.png)
![duo sub network](https://github.com/chenx-git/chenx_Portfolio/blob/main/images/2.3.png)
