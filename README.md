# 💻👾🚀 Tiffany Zhu

# 👋 Contact

📧 [Email](mailto:tlzhu@alumni.cmu.edu) / ![](https://i.stack.imgur.com/gVE0j.png) [LinkedIn](https://www.linkedin.com/in/tiffany-zhu1/) / ![](https://i.stack.imgur.com/tskMh.png) [GitHub](https://github.com/tlzhu19/)

---

# 👩🏼‍🎓 Education

| MS in Data Science @ [Columbia University](https://www.columbia.edu/) | Aug 2019 - Dec 2020 |
| BS in Mathematical Sciences (Statistics), Minor in Computer Science @ [Carnegie Mellon University](https://www.cmu.edu) | Sept 2013 - May 2017|

---

# 🔧 Technologies & Tools

![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-R-informational?style=flat&logo=r&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/ML-Pandas-informational?style=flat&logo=pandas&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/ML-Numpy-informational?style=flat&logo=numpy&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/ML-ScikitLearn-informational?style=flat&logo=scikit-learn&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/ML-TensorFlow-informational?style=flat&logo=TensorFlow&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Framework-Flask-information?&style=flat&logo=flask&logoColor=white&color=blue)
![](https://img.shields.io/badge/Framework-Django-information?&style=flat&logo=django&logoColor=white&color=blue)
![](https://img.shields.io/badge/Framework-Bootstrap-information?&style=flat&logo=bootstrap&logoColor=white&color=blue)
![](https://img.shields.io/badge/Framework-jQuery-information?&style=flat&logo=jquery&logoColor=white&color=blue)
![](https://img.shields.io/badge/Tools-Heroku-informational?style=flat&logo=heroku&logoColor=white&color=red)
![](https://img.shields.io/badge/Tools-PostgreSQL-informational?style=flat&logo=postgresql&logoColor=white&color=red)
![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=red)
![](https://img.shields.io/badge/Tools-Red_Hat_OpenShift-informational?style=flat&logo=red-hat-open-shift&logoColor=white&color=red)

---

# 👩🏼‍💻 Work Experience

### **Cognitive Developer** @ [IBM](https://www.ibm.com/)
**June 2020 - present**
* Optimized manufacturing production process, collaborating with a team of data scientists and engineers. Trained and evaluated linear regression models and neural networks to predict targets that measure factory efficiency. The models are fed into the optimization system where for every change in the control variables, the predicted targets are optimized. The system autonomized the factory and increased the production. 
  * *Technology stack*: IBM Cloud, Python (Pandas for data cleaning, Scikit Learn for modeling, IBM research's SROM for optimization)
* Developed a research NLP application with Python Flask (backend) and React (front end) to 1. train a domain specific named entity recognition (NER) model and 2. expand domain specific text training data using a feedback loop. For the second task, the user can give continuous input to train a classification model that extracts documents from Wikipedia and classifies which are relevant to the domain.
  * *Technology stack*: Python Flask (backend), React (frontend)
* Preprocessed insider trading data and created aggregated features per day with Pandas. Trained XGBoost and SVM regression models to predict the risk of insider trading and other fraudulent activities. Deployed the model with IBM Cloud and developed R Shiny dashboard to display important insights from the data and the model.
  * *Technology stack*: IBM Cloud, Python (Pandas, Scikit Learn), R Shiny for dashboard
* Deployed a Python Flask web application using IBM Cloud Foundry to demonstrate industry use cases of datasets from CODAIT’s Data Asset Exchange (DAX). [Comments organizer](https://community.ibm.com/accelerators/catalog/content/Customer-Online-Comments-Organizer) helps companies better organize their comments by providing them a central place to 
  1. Import comments, 
  2. Automatically group comments using KMeans (model from Scikit learn and is deployed using Watson Machine Learning)
  3. Analyze the sentiment of comments as a whole and by sentence,
  4. Visualize frequently used words and comment sentiments.
* Create lessons and practice labs for Data Analysis with R and Data Visualization with R on [Coursera](https://www.coursera.org/instructor/tiffanyzhu).

### **Software Engineer** @ [EAB](https://eab.com/)
**July 2017 - July 2019 | Washington, DC**
* Developed a rule-based degree audit engine with a team of software engineers using Python/Django to help college students track their academic progress. Used ANTLR to create our own grammar and parse rules to map to our abstract syntax tree (AST).
* Automated the degree audit report generation framework. Used Redis Queue (RQ) to asynchronize (queue and process in the background) reports, making it faster to analyze audits and onboard new colleges to our system. 
* Spearheaded project to emulate a new degree audit system that used various relational database tables to create rules rather than parsing text files.

### **Software Engineer** @ [NASA](https://www.nasa.gov/)
**Internship | May - Aug 2016 | Kennedy Space Center, FL**
* Worked with a team of engineers and scientists to create a software tool using Python to automate the generation of Virtual Machine Language (VML) commands based on queries from the Master Measurement List Database stored on a Django web application. Used for the RESOLVE Payload for the [Resource Prospector Lunar Volatiles Mission](https://www.nasa.gov/resource-prospector).

---

# 📊 Projects/Research

### EPA text classification and scoring
**Spring 2020 | Columbia University Vagelos College of Physicians and Surgeon | Mentors: Dr. Henry Park, Dr. Anhphan Ly**
* Automated medical student evaluations and competency checks (EPAs) to reduce the hours of tedious labor doctors could otherwise be spending their time on.
* Fitted Long Short-term Memory (LSTM) model using Tensorflow and XGBoost model to conduct classification and sentiment analysis on EPAs (used to evaluate medical students)

### **[Recommender Systems for Businesses on Yelp](https://github.com/tlzhu19/personalization-final-project)**
**Fall 2019 | Columbia University Data Science Institute**
* Used Yelp dataset and Python to implement various models to predict the last review of each active user (users who rated at least 5 businesses). 
* Worked with a team to implement a learned bias baseline model (took average ratings of users and businesses), as well as SVD, nonnegative matrix factorization, and wide and deep models. 
* Evaluated models using RMSE and catalog coverage to analyze improvements compared to the baseline.

### Capstone - Energy Efficient Machine Learning on the Edge
**Fall 2020 | Columbia University Data Science Institute**
* Collaborating with researchers at General Electric (GE), explored ways to make machine learning more carbon efficient by using various quantization methods on training data at different bit precision levels. 
* Modularized quantization methods (fixed, quantiles, stochastic methods) with Python to easily apply on different datasets.
* Ran quantized data on various machine learning models and compared results at different bit precision levels.
* Evaluated significance of different quantization methods using paired t-test. Used the  accuracy of a model trained with a certain quantization method against another quantization method to run tests.


