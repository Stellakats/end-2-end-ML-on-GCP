# End to end Machine Learning on Google Cloud Platform

In this project, I am walking through the process of building a complete machine learning pipeline with Google Cloud Platform ML tools, in order to get an idea of how an ML model can be deployed into production. 

The objective of the project is to predict the weight of newborns in the US. The dataset is available [here]( https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=samples&t=natality&page=table&_ga=2.219613081.126878707.1593506711-1712496757.1581007489&_gac=1.60235103.1593288525.Cj0KCQjw3Nv3BRC8ARIsAPh8hgKon1ByjWW8BafyH4uTn3u60u2PResZz3Q2wkYPbHW3kLkpoUv3WQYaAua9EALw_wcB&pli=1&project=modern-tangent-281620&folder=&organizationId=).

It consists of 6 steps: 1. Explore and visualize the dataset in order to pick the most important features 2. Create a sample dataset, that is representative of the whole dataset, so that a model can be locally developed 3. Developing a model using Tensorflow’s high level API, tf.estimator, in and set a prototype in place. 4. Create a full-sized training and evaluation set using Dataflow, so that the pre-processing can be applied during prediction as well. 5. Train the model. 6. Deploy the model. 

This project was conducted under the guidance of the online course “End-to-End Machine Learning with TensorFlow on GCP” in Coursera, and part of the code was provided there. 
