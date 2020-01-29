# Welcome to a hands-on exercise using the **Azure Machine Learning service** and **AI insights** in Power BI Dataflows.

The learning in this exercise is to learn how to create and deploy ML models using the Azure Machine Learning service and then to consume them using **AI insights** in Power BI Dataflows. 


## Prerequisites

1. Need an Azure Subscription for this demo. If you do not have an Azure account, you can sign up for free [here](https://azure.microsoft.com/free/)

2. Need to create a Machine Learning service workspace in an Azure Resource Group

![createworkspace](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/createworkspace.png)

You can find details on creating an AML service workspace [here](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-manage-workspace#create-a-workspace)

3. Save the csv file carprice.csv that is available [here](https://raw.githubusercontent.com/DataSnowman/carprice/master/dataset/carprice.csv)

You can also get the file by downloading a zip of this repository or by cloning this GitHub repository using Git and the following commands:

``git clone https://github.com/DataSnowman/carprice.git``

## Using the NEW **Workspace2 AML Preview Automated machine learning UI**

To learn how to create and deploy a ML model for the carprice dataset using the Azure Machine Learning service **Workspace2 AML Preview Automated machine learning UI** click [here](https://github.com/DataSnowman/carprice/tree/master/ws2preview-automl-ui)

![ws2](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/ws2.png)

## Using the **Azure Portal Automated machine learning UI**

To learn how to create and deploy a ML model for the carprice dataset using the Azure Machine Learning service **Azure Portal Automated machine learning UI** click [here](https://github.com/DataSnowman/carprice/tree/master/automl-ui)

![portal](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/portal.png)

## Using the **Notebook VM**

To learn how to create and deploy a ML model for the carprice dataset using the Azure Machine Learning service **Notebook VM** click [here](https://github.com/DataSnowman/carprice/tree/master/notebooks)

![notebook](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/notebook.png)

## Using the **Visual interface**

To learn how to create and deploy a ML model for the carprice dataset using the Azure Machine Learning service **Visual interface** click [here](https://github.com/DataSnowman/carprice/tree/master/visual-interface)

## Using **AI insights in Power BI**

To learn how to use the carprice ML model to predict the price of a car using **AI insights in Power BI** click [here](https://github.com/DataSnowman/carprice/tree/master/powerbi)

![pbi](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/pbi.png)

At the time of creating this Repo decorating the web service so that it is usable in **AI insights** in a Power BI Dataflow was not available when using the AML service **Visual interface**.  This will not be the case as we move into fall 2019 when this scenario will also work from the **Visual interface**. 

Add to test connection to GitHub