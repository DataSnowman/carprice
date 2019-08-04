# Welcome to a hands-on exercise using the **Azure Machine Learning service** to author a model using the **Automated machine learning UI**


## Create an AutoML Experiment

1. Open the Azure Machine Learning workspace by clicking on it in the Azure portal

![openworkspace](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/openworkspace.png)

2.	Click on Automated machine learning under the Authoring section

![openautoml](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/openautoml.png)

3.	Click on Create experiment.

![createexp](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/createexp.png)

4.	Enter an Experiment name and click on Create a new compute

![expname](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/expname.png)

5.	Enter a Compute name, Select virtual machine size, set Minimum number of nodes to 1, and click Create (Note if you want the compute to decrease back to 0 nodes you might want to create the AML compute prior to running the experiment)

![createcompute](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/createcompute.png)

6.	Select a training compute and chose the new compute created above.  Click ``Next``

![amlnext](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/amlnext.png)

7.	Click on Upload to upload the carprice.csv you downloaded in the prerequisites. Or get it from the path where you cloned this GitHub repo.

![uploaddataset](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/uploaddataset.png)

8.	Select carprice.csv

![selectcarprice](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/selectcarprice.png)

9.	Preview the data.  You may need to have at least 1 node runnin on on ML compute to see the preview.

![previewdata](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/previewdata.png)

10.	Ignore the SYMBOLING and NORMALIZED-LOSSES columns (features) by clicking on the Included/Ignored slider

![ignore](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/ignore.png)

11.	Chose Regression for the prediction task and price for Target column.
12.	Click ``Start``

![start](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/start.png)

13.	Let it run to finish to complete the experiment.  Do this the first time ahead of the demo to have a completed experiment.

## Review the AutoML Experiment

Once the AutoML experiment completes 

1.	Click on the Run ID of the completed experiment

![runid](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/runid.png)

2.	View the Iteration Chart and view some of the point on the graph

![ichart](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/ichart.png)

3.	Scroll down to the Iterations and talk about the models and their Spearman Correlation

![spearman](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/spearman.png)

4.	Scroll down and click on Deploy Best Model

![deploybest](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/deploybest.png)

5.	Register Model
6.	Download Scoring Script
7.	Download Environment Script
8.	Deploy Model

![rddd](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/rddd.png)

9. Edit the scoring script (scoring.py) file

10. Edit the environment script (condaEnv.yml) file

11.	Create an Image

12. Create a Deployment

13.	Consume the AKS web service in Power BI by clicking [here](https://github.com/DataSnowman/carprice/tree/master/powerbi)




