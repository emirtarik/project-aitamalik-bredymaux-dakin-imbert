# Big Data Project
#### Amine AITAMALIK - Charlotte BREDY-MAUX - Emir DAKIN - Yann IMBERT

For this project, we picked a data set about songs from Spotify. The variables include (but are not limited to) loudness, popularity and danceability. Here is the link for the data set: https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks?select=tracks.csv

The goal here is to predict popularity based on the other variables. We consider that a popular song has a popularity score higher than 50.

Three notebooks are available in this repository. The first one ``data_exploration_databricks.ipynb`` is, obviously, an exploratory notebook. However, we have encountered some issues while running it on Databricks so the last cells face errors. This is why we kept the jupyter version, ``data_exploration_jupyter.ipynb``. The third one ``sparkes.ipynb`` delves deeper into exploration in order to create new variables for the upcoming models. Afterwards, it uses the MLLIB and Pipeline frameworks from PySpark in order to train, test and evaluate different models.  

Please note that these notebooks have been exported from Databricks where the data has been uploaded directly on the DBFS. On this repo, we could only upload the zip file. Therefore, an extraction of the ``tracks.csv`` file is necessary before running the notebooks.
