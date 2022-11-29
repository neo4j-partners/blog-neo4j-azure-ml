# Neo4j Integration with Azure Machine Learning

This repository is meant to demonstrate the integration between Neo4j Graph Data Science and Azure Machine Learning. 
The [data](data/) is from [Kaggle](https://www.kaggle.com/datasets/ifteshanajnin/carinsuranceclaimprediction-classification?select=train.csv) and is about Car Insurance policies to detect potential fraudulent claims in the next 6 months.

Notebooks are located [here](notebook/) and are meant to be run inside Azure ML Studio.

## Pre-requisites
- Neo4j Graph Data Science instance
- Azure ML instance

The [notebooks](notebook/) cover on how to ingest data to Neo4j Graph Data Science instance, create node embeddings, export them to Azure ML and use AutoML to create a best model that can predict fraud claims in the next 6 months.