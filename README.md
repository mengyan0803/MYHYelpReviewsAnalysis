# Yelp Review Analysis
In this project, a Spark cluster on AWS EMR is provisioned, connnected to a Jupyter Notebook to perform a series of queries (using DataFrame API and Spark SQL) which at the end, answer a few questions about the Yelp Data available on [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset#yelp_academic_dataset_user.json).

There are three datasets used fromt the Yelp Dataset, the business, review and user datasets. Each of them are loaded into [S3](https://s3.console.aws.amazon.com/s3/buckets/bucket2myh/?region=us-east-2&tab=overview). A view of my S3 containing the data files.


![image](https://user-images.githubusercontent.com/57573785/80927205-1b29de80-8d6a-11ea-841b-7923e214597b.png)


To start with the work, a Spark Cluster is created on AWS EMR with the follwoing configuration.



![image](https://user-images.githubusercontent.com/57573785/80927489-48778c00-8d6c-11ea-8a87-0689504c80bb.png)


Then, a new Jupyter Notebook is also created to run on the Cluster with the following configuration.



![image](https://user-images.githubusercontent.com/57573785/80927552-7f4da200-8d6c-11ea-844f-10b834e49f72.png)



