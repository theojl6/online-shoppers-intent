# online-shoppers-intent

Data analysis on the Online Shopping Behavior dataset from https://www.kaggle.com/henrysue/online-shoppers-intention

With Python, scikit-learn, pandas, numpy, matplotlib, seaborn

Full notebook: ![notebook](Online_Shopping_Behavior_Analysis.ipynb)

# 1. Data handling
![datahandling](images/data_handling.png)

# 2. Model fitting to predict buyers / non-buyers, with Support Vector Machines, Random Forest Classifier, XGBoost Classifier
![xgboost](images/xgb_classifier_results.png)

# 3. Data clustering with DBSCAN, k-means after dimensionality reduction with TSNE
Using TSNE to reduce high number of dimensions (20 features)
![tsne](images/tsne.png)
DBScan grid search
![dbscan](images/dbscan_gridsearch.png)
K-means algorithm
![kmeans](images/kmeans_clustering.png)

# 4. Cluster assignments from analysis
![clusters](images/cluster_assignment.png)
