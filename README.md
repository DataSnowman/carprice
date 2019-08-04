# Welcome to a hands-on exercise using the **Azure Machine Learning service** and **AI insights** in Power BI Dataflows.

The learning in this exercise is to learn how to create and deploy ML models using the Azure Machine Learning service and then to consume them using **AI insights** in Power BI Dataflows. 


## Prerequisites

1. Need an Azure Subscription for this demo. If you do not have an Azure account, you can sign up for free [here](https://azure.microsoft.com/free/)

2. Need to create a Machine Learning service workspace in an Azure Resource Group

![createworkspace](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/createworkspace.png)

You can find details on creating an AML service workspace [here](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-manage-workspace#create-a-workspace)

3. Save the csv file carprice.csv that is available [here](https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/carprice.csv) to a folder on your machine, e.g. to Documents\AutoML\CarPrice.  Or you can get it from this Repo [here](https://raw.githubusercontent.com/DataSnowman/carprice/master/dataset/carprice.csv)


## Using the **Automated machine learning UI**

To learn how to create and deploy a ML model for the carprice dataset using the Azure Machine Learning service **Automated machine learning UI** click [here](https://github.com/DataSnowman/carprice/tree/master/automl-ui)

## Using the **Notebook VM**

To learn how to create and deploy a ML model for the carprice dataset using the Azure Machine Learning service **Notebook VM** click [here](https://github.com/DataSnowman/carprice/tree/master/notebooks)

## Using the **Visual interface**

To learn how to create and deploy a ML model for the carprice dataset using the Azure Machine Learning service **Visual interface** click [here](https://github.com/DataSnowman/carprice/tree/master/visual-interface)

## Using **AI insights in Power BI**

To learn how to use the carprice ML model to predict the price of a car using **AI insights in Power BI** click [here](https://github.com/DataSnowman/carprice/tree/master/powerbi)

At the time of creating this Repo decorating the web service so that it is usable in **AI insights** in a Power BI Dataflow was not available when using the AML service **Visual interface**.  This will not be the case as we move into fall 2019 when this scenario will also work from the **Visual interface**. 