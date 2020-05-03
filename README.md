# Yelp Review Analysis
In this project, a Spark cluster on AWS EMR is provisioned, connnected to a Jupyter Notebook to perform a series of queries (using DataFrame API and Spark SQL) which at the end, answer a few questions about the Yelp Data available on [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset#yelp_academic_dataset_user.json).

There are three datasets used fromt the Yelp Dataset, the business, review and user datasets. Each of them are loaded into [S3](https://s3.console.aws.amazon.com/s3/buckets/bucket2myh/?region=us-east-2&tab=overview). A view of my S3 containing the data files.
