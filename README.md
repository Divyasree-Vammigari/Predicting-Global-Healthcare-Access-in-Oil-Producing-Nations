This project aims to predict the Healthcare Access Index worldwide and understand its 
relationship with various socio-economic and health indicators. Data was collected from 
reputable sources, including Our World in Data, the World Bank, and Transparency 
International, covering a range of indicators for OPEC countries and the USA. After merging 
and cleaning the datasets, Singular Value Decomposition was applied to impute missing values. 
The data were then standardized and reduced in dimensionality using Principal Component 
Analysis. Clustering analyses, including K-means and hierarchical clustering, were conducted 
to identify distinct groups within the data. Exploratory Data Analysis provided insights into the 
distribution and relationships between various indicators. 
Supervised learning models, including Decision Trees and Boosting, were developed to predict 
the Healthcare Access Index. These models were fine-tuned using “GridSearchCV”, and their 
performance was evaluated using class. Feature importances were extracted from the Boosting 
model to identify key predictors. The Decision Tree model achieved an accuracy of 97.7%, 
while the Boosting model achieved an accuracy of 98%. The analysis revealed that countries 
with higher GDP per capita generally had better healthcare access, and there was a significant 
inverse relationship between cardiovascular death rates and healthcare access, indicating that 
improved healthcare access is associated with lower cardiovascular mortality. 
