# Fast Python implementation of popular recommendation algorithms for implicit feedback datasets using [Implicit](https://implicit.readthedocs.io/en/latest/quickstart.html) library

Dataset: [Google Analytics Database](https://support.google.com/analytics/answer/7586738?hl=en) (Taken from Google Bigquery)

If you want to have more information on how to set up your Google Bigquery account and access this dataset, check out the [documentation](https://cloud.google.com/bigquery/docs/) - it's well-made and it allows you to get started in a few minutes!

The Jupyter Notebook contains a brief guide to the implementation of two popular recommender systems, namely Alternating Least Squares (ALS) and Bayesian Personalized Ranking (BPR) for implicit feedback datasets. The notebook also contains a brief mathematical explanation of how the methods work.

Here's a brief explanation of the dataset (taken from Google description): <br><br>

"The sample dataset contains obfuscated Google Analytics 360 data from the Google Merchandise Store, a real ecommerce store. The Google Merchandise Store sells Google branded merchandise. The data is typical of what you would see for an ecommerce website. It includes the following kinds of information:

- Traffic source data: information about where website visitors originate. This includes data about organic traffic, paid search traffic, display traffic, etc.
- Content data: information about the behavior of users on the site. This includes the URLs of pages that visitors look at, how they interact with content, etc.
- Transactional data: information about the transactions that occur on the Google Merchandise Store website."

Note: You can either choose to take the datasets directly from the repository ([df.csv](https://github.com/gabrielebrunini/Recommender_system_implicit/blob/master/df.csv) and [item_names.csv](https://github.com/gabrielebrunini/Recommender_system_implicit/blob/master/item_names.csv) files) or you can choose to get it from Google Bigquery using a couple of SQL queries, which you can find in the notebook file (preferred if you are not familiar with it and want to practice a bit).
If you want to know more about how to create Google project and service account keys, follow this [link](https://cloud.google.com/storage/docs/projects)
