# MeToo Twitter Data
This repository is used for the Master Thesis of Sophie Mottier, entitled *"Au delà des 280 caractères: modes de constitution des collectifs et formes énonciatives au sein du mouvement #MeToo sur Twitter"*.

This repository contains the code used to extact tweets and key statistics about the MeToo Movement on Twitter. 

The MeToo dataset was downloaded using Hydrator, extracting tweets specified in the Harvard Dataverse [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/2SRSKJ).

The data processing is done in the notebook called ```extact_information.ipynb```, using helper functions defined in ```src/helpers.py```. The directory ```export_summary``` contains extracted aggregated data which is used for the plots in the thesis. 


![Wordcloud of the top retweeted tweets](https://github.com/DenizIra33/metoo-twitter-data/blob/main/wordcloud.png?raw=true)
