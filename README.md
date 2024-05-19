# Bigfootprint
Predict where the elusive Bigfoot will be based on temporal/weather information

### Data
This data comes from the Bigfoot Field Researchers Organization (BFRO), which is dedicated to discovering the truth of Bigfoot's existence. The data used in the models is from https://www.kaggle.com/datasets/thedevastator/unlocking-mysteries-of-bigfoot-through-sightings?select=bfro_locations.csv and originates from Timothy Renner, who has a pipeline to obtain the data at https://github.com/timothyrenner/bfro_sightings_data

All data that will be used is within the /data folder

### Files
BigFootNLP.ipynb - Contains all NLP code including both NLP models and the word clouds <br>
Bigfoot_EDA.ipynb - Contains all research into the data used <br>
Clustering.ipynb - Contains the code to cluster the sightings into groups <br>
ClusterPred.ipynb - Contains the code that creates models based on the clusters <br>
Multi-Output Regression DL.ipynb - Contains the code that creates the model for predicting bigfoot <br>
