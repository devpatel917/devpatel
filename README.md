## Dev's Data Science Portfolio


<img align = "left" src="/docs/assets/IMG1048.jpg" width="378" height="504" hspace="20" vspace="20">

Hi!

I'm Dev, second year student at the University of Illinois studying Statistics and Computer Science. My interest lies in ML/AI and data science. Scroll down to check out some of my projects!

<br clear="left"/>


### Projects

**Face Mask Detection**
<img align = "left" src="/docs/assets/mask.png" width="348" height="234" hspace="20" vspace="20">

Masks play a crucial role in protecting the health of individuals against respiratory diseases. Trained with 5000 images of mask/no mask, this model can classify facial images with mask/without mask. 

[Face Mask Detector App](https://devpatel917-facemaskdetection-app-98f4fk.streamlitapp.com/)

Tools Used: CNN (ML Algorithm), TensorFlow, Streamlit (Frontend), OpenCV (Image Processing), Streamlit Cloud (Deployment)


<br clear="left"/>

**Stock Sentiment Analysis**

<img align = "left" src="/docs/assets/tsla.png" width="400" height="250" hspace="20" vspace="20">

Financial markets are hard to predict, but sentimental analysis is an increasingly popular method to gauge the general opinion on financial assets. In this project, we utilize an NLP model to conduct sentiment analysis on tweets related to stocks. The results of this model can help us better understand the correlation between public sentiment and stock price movement. 

Tools Used: Twitter API, Flair (NLP), Pandas, yfinance, Regular Expression

<br clear="left"/>

**Credit Card Fraud Detection**
<img align = "right" src="/docs/assets/tsla.png" width="400" height="250" hspace="20" vspace="20">

It is important that credit card companies are able to recognize fradulent credit card transactions so that customers are not charged for items that they did not purchase. In this project, we develop a machine learning model to identify fradulent credit card transactions. 

Tools Used: Pandas, Logistic Regression, sklearn


**Quantitative Momentum Investing Strategy** 

<img align = "right" src="/docs/assets/stock1.png" width="319" height="255" hspace="20" vspace="20">

In this stock investment strategy, we recommend the stocks with the highest HQM score. The HQM score is calculated by taking the arithmetic mean of the percentiles of one year price return, six month price return, three month price, return, and one month price return for each stock in the S&P 500 Index. 

[Quant Momentum Investing Strategy](https://devpatel917-quantfinanceprojects-app-vpqh88.streamlitapp.com/)

Tools Used: IEX Cloud API, Pandas, Streamlit

<br clear="right"/>

**Department Deep Structure (Illinois Geometry Lab)**


<img src="/docs/assets/DeepStructure.png" width="388" height="268" hspace="20" vspace="20" class = "center">

What is the structure of the math department at the University of Illinois? The question is not as simple as it seems: the research group composition changes fast, and their impact on the global scale might be smaller or larger than it seems. The goal of this project is to detect research clusters in the math department at the University. 

1. We used python libraries Selenium and BeautifulSoup to web scrape data from MathSciNet, a research database containing mathematical publications, references, citations, etc
2. From this extracted information, we generated distance matrices to represent connections between each pair of faculty in the math department
3. We applied hierarchical clutering algorithms to these distance matrices to generate research clusters between faculty members

[Final Report](https://drive.google.com/file/d/1g3Dv-cTI_qWQOws_tKPm-aUfNhc8Uagn/view?usp=sharing)

[Poster](https://drive.google.com/file/d/14vDHpwclFKu1Q50qCm7aBtL-sq-H8VeM/view?usp=sharing)

Tools: Selenium and Beautiful Soup, Web Scraping, Hierarchial Clustering Algorithms



**Gut Microbiome Data Science Project (National Center for Supercomputing Applications)**

<img src="/docs/assets/spin.png" width="362" height="269" hspace="20" vspace="20" class = "center">

Diet is a modifiable lifestyle factor that can alter the composition of the human gastrointestinal microbiome. To study these changes, data science techniques can be applied to identify fecal metabolites as objective biomarkers of food consumption. The aim of this project was to identify
significant metabolites and taxonomic groups from five separate randomized, controlled dietary interventions providing almonds, avocados, broccoli, whole grain barley and oats, and walnuts.

1. Data Cleaning/Pre-processing - Separating control vs treatment participants, handling missing values, data normalization, etc
2. Exploratory Data Analysis - Create box and whisker plots for control vs treatment for all metabolites/taxonomic groups
3. Significance Testing - Utilized t test to determine significant metabolites and bacterial groups that caused the most change in the gut microbiome
4. Principal Component Analysis - Generated PCA plots to show if significant clusters between control vs treatment arised for all food interventions
5. Machine Learning Models - Used Random Forest and Logistic Regression to classify food intake from significant metabolites and taxonomic groups

[Final Report](https://drive.google.com/file/d/1PuUYHk2G0YUckFo4FEECkubsmZK4WMq0/view?usp=sharing)

[Poster](https://drive.google.com/file/d/1P1kzv5zsek4r7QCOsSr7Gk9YfFbhIi4L/view?usp=sharing)

Tools: Data Cleaning, EDA, Random Forest, Principal Component Analysis, Statistical Significance Testing



**NFL Big Data Bowl 2022 (Kaggle Competition)**

<img src="/docs/assets/bigdata.png" width="407" height="215" hspace="20" vspace="20" class = "center">

In this project, we create a new metric to evaluate kickers in the NFL. This new metric provides a 'clutchness' rating for the kicker, taking into account both the difficulty of the kick and the situation in the game. 

1. Data Cleaning and Data Collection - Weather data for each game, kicking play data, etc
2. Feature Extraction - Kick Length, Quarter, Time Remaining in game, temperature, etc for each kick of each kicker from 2018-2020
3. Model Building - Created two different models using feed forward neural networks. The first model predicts if a kick was made independent of kicker info. The second model predicts if a kick was made dependent on kicker info. The difference between these models suggests the performance of the kicker. 


[Submission](https://www.kaggle.com/code/mattt31/evaluating-kicker-performance-using-ker/notebook?scriptVersionId=84600332)

Tools: Data Cleaning, Neural Networks


**Job Scheduler Application (IT Expert System Internship)**

<img src="/docs/assets/itexperts.png" width="431" height="268" hspace="20" vspace="20" class = "center">

In this project, we built a job scheduling application that automates business tasks such as sending birthday emails, generating reports, sending SMS messages, and converting audio to text using AWS, Knack Database, and python. 

[Presentation](https://drive.google.com/file/d/14DDx_nlLiqxYkd8V77GPPZEJePfb88SN/view?usp=sharing)

[Code](https://github.com/anandani4136/ITExpsGUI)

 Tools: AWS, Knack Database, Knack API, Threading, AWS S3 Buckets, Python tkinter, AWS Polly



**Kaggle Competitions**

[Titanic](https://github.com/devpatel917/TitanicKaggleML) : Built a machine learning model that predicts which passengers survived the Titanic using passenger data (name, age, gender, socioeconomic class, etc) 

[Spaceship Titanic](https://www.kaggle.com/code/devpatel917/79-random-forest-model) : Built a Random Forest Classifer that predicts which passengers were transported into another dimension with 79.9% accuracy (Top 30% of kaggle submissions). 

Techniques Implemented: Exploratory Data Analysis, Feature Engineering, Hyperparameter Optimization, K fold cross validation, Random Forest, XGBoost, Logistic Regression



