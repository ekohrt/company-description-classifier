# Company Description Classifier
Classifying companies into one of 41 industries based on a text description. Uses sentence-transformer embeddings and sklearn's NearestCentroid model.  

Dataset is modified from [this](https://github.com/datahoarder/crunchbase-october-2013) 2013 dump of Crunchbase company info, which contained company name, industry category, and crunchbase permalink. Used the free Crunchbase API to scrape the short description for each company.

Written in colab.
