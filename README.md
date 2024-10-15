# Data Analytics Portfolio

I am a Computer Science student at IPB University with a growing focus on data analysis and a developing skillset in machine learning, deep learning, and natural language processing. My experience includes:

- Participating in data science competitions like Satria Data, where I've gained hands-on experience analyzing datasets and building predictive models for text classification tasks.
- Working with substantial datasets, including a numeric dataset of 416,473 rows where I achieved over 70% accuracy.
- Exploring various NLP techniques using models like IndoBERT and other BERT variants.
- Applying both deep learning algorithms and classical machine learning methods like SVM, KNN, and clustering for supervised and unsupervised learning tasks.
- Developing proficiency in Python as my primary programming language for data analysis and machine learning projects.
- Practical experience with R, SQL, Excel, and Tableau for data manipulation, analysis, and visualization.
- Building a foundation in data analytics techniques including report writing, data mining, data merging, statistical analysis, and critical thinking.
- Currently learning about reinforcement learning and its potential applications in personalized learning systems.

## A Model to Classify Tweets About Presidential Elections into Asta Gatra Classes
In the Big Data Challenge (BDC) Satria Data 2024, participants were challenged to classify issues discussed by authors in their tweets related to the 2024 Presidential Election. This classification was based on the Astagatra framework, which represents components of national resilience. The task involved categorizing tweets into eight classes:
- Ideology: Fundamental values, principles, and worldviews guiding the nation and state.
- Politics: Government systems, policies, and political processes within the country.
- Economy: Economic management, financial resources, and efforts to create prosperity.
- Socio-Culture: Social values, cultural norms, and societal aspects influencing national unity and identity.
- Defense and Security: National defense and internal security against threats or disruptions.
- Natural Resources: Management and utilization of natural resources for development and national security.
- Geography: Location, physical conditions, and natural environment affecting life and policies.
- Demography: Population structure, growth, distribution, and dynamics influencing national policies and development.
This competition required participants to analyze tweets and correctly classify them into one of these eight categories related to the nation's resilience factors.

### Research Highlight
- Worked with a dataset of 5,000 tweets categorized and 8 classes. Cleaned the data by removing slang words, stopwords, and special characters, and applied tokenization.
- Developed a predictive model using IndoBERT for sequence classification. Configured the model with an optimizer and CrossEntropyLoss, and trained it using DataLoader for efficient batch processing.
- Evaluated the model, achieving a balanced accuracy of 41% on the new dataset

## A Forecasting Model Designed to Categorize Traffic Types Within Networks 

This project develops a machine learning model to classify network traffic in real-time, enhancing cybersecurity for high-traffic websites. By analyzing various traffic patterns, the system aims to differentiate between legitimate user activities and potential threats. The model will assist cybersecurity teams in quickly identifying and responding to suspicious activities, thereby improving overall network integrity and security posture.

Key features:
- Real-time traffic analysis
- Multi-class traffic classification
- Anomaly detection
- Scalable for high-volume data processing
This solution addresses the critical need for proactive cybersecurity measures in the digital era, helping companies protect their networks against evolving cyber threats.

### Research Highlight

- Build and develop a predictive model to classify various types of network traffic into 6 classes. from background until bruteforce-XML.
- Developed and trained a predictive model using a train dataset of 416,473 entries and evaluated it on a test dataset of 138,805 entries, implementing and fine-tuning an MLPClassifier, ReLU activation, and optimizer
- Achieved 73.5% accuracy in predicting the six traffic categories using the full feature set.
- Conducted feature selection using Genetic Algorithm, which resulted in a reduced accuracy of 68%, indicating the need for further refinement

## Logistic Regression for Fraud Detection in Financial Loan Payments
Fraud detection involves identifying user actions as fraudulent or not. In this context, fraud is defined as users who have borrowed financial products but have not made payments by the due date.
Key Points:
Role of Machine Learning: Machine learning is crucial in fraud detection. It helps in identifying patterns and predicting fraudulent activities.
Logistic Regression: This is a machine learning model used for classification. It predicts the probability of a categorical dependent variable. Logistic regression is chosen because:
Ease of Implementation: It is straightforward to apply.
Interpretability: The results are easy to understand, which is vital in fraud detection to comprehend the relationship between predictors and the likelihood of fraud.
Performance: Logistic regression often shows better average precision scores compared to some other algorithms.

### Research Highlights
- Used logistic regression to build a model for classifying the transaction. Logistic Regression effectively handled class imbalance and multicollinearity, outperforming complex models like LightGBM and FA-CNN with an average precision score of 0.8138 in detecting financial fraud.
- The dataset alone contains nearly one million observations, with highly imbalanced classes (98.74% non-fraud vs 1.26% fraud).
- Used Regularization techniques (L1/L2) helped manage multicollinearity, enhancing model stability.
- Logistic Regression emerged as a robust and reliable model for financial fraud detection, particularly when combined with regularization to address data issues. Despite challenges like class imbalance and multicollinearity, it proved more effective than complex algorithms, making it an optimal solution for this problem.

## Analysis of Flood and Education Level Relationship in DKI Jakarta

This project aims to develop a machine learning model to predict flood occurrences and their economic impact in Jakarta, Indonesia. Using historical data on rainfall patterns, urbanization metrics, and economic indicators, I create a robust predictive framework to Forecast flood likelihood and severity. 
My analysis combines time series forecasting, geospatial data, and educational statistic  to provide actionable insights for city planners and policymakers. This project aims to provide valuable insights for policymakers and education authorities. By understanding the role of education in disaster resilience, we can propose targeted educational programs and awareness campaigns to improve Jakarta's overall flood preparedness and response capabilities.
Key aspects of the project include:

- Data integration: Merging flood occurrence data with educational attainment statistics and socioeconomic indicators across Jakarta's districts.
- Correlation analysis: Examining the relationship between education levels and various flood impact metrics (e.g., damage costs, evacuation rates, recovery time).
- Predictive modeling: Developing machine learning models to forecast flood resilience based on educational and demographic factors.
- Policy implications: Identifying potential interventions in education that could enhance community flood resilience.
- Comparative analysis: Assessing how different levels of education (primary, secondary, tertiary) correlate with specific aspects of flood preparedness and response.
### Research Highlights
- Utilized linear regression method to understand the relationship between flood and education in Jakarta in 2020 - 2021
- Conducted a conclusion that there is no significant relationship between flood levels and education levels.
- Recommended strengthening educational initiatives to enhance environmental awareness, as higher education levels may influence future relationships between education and environment issue

  
# Building a Robust Skill Set in Data Science
My involvement in data science competitions has provided me with essential knowledge and hands-on experience that are equipping me for a career in data analysis. This includes the ability to:  
- Clean and structure data  
- Identify patterns and insights  
- Formulate significant conclusions  
- Effectively convey important findings.  

Through this program, I'm improving my skills with Python's data analysis utilizing tools like 
- Python (pandas, numpy, seaborn, matplotlib),
- PyTorch (AdamW optimizer and TensorDataset),
- scikit-learn, and
- Indonesian-specific NLP tools (Sastrawi, fuzzywuzzy, python-Levenshtein, indonlp) while building a portfolio of projects.

My evolving skill set covers aspects of machine learning, deep learning, NLP, and traditional data analysis techniques, allowing me to approach data science problems from multiple perspectives as I continue to learn and grow in the field.
