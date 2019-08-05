# Welcome to a hands-on exercise using **AI insights** in Power BI Dataflows to predict car price


## Setup Power BI Dataflow

1. Go to https://powerbi.com and Sign in
2. Create a workspace

![createbpiws](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/createbpiws.png)

3.	Give the Workspace a name like CarpriceDemo.  Note that the Workspace name must be globally unique so add you initials or pick something unique that works for you.

![pbiwsname](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/pbiwsname.png)

4.	Create new content
5.	Click on Get started under Dataflows

![dataflow](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/dataflow.png)

6.	Click on Add new entities

![newentity](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/newentity.png)

7.	Select Text/CSV as a Data source

![datasource](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/datasource.png)

8.	Paste the URL ``https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/carprice.csv`` for the csv file carprice.csv
9.	Click `Next`

![csv](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/csv.png)

10.	Enter a Name for the query (like carprice)
11.	Click Save & close

![queryname](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/queryname.png)

12.	Name the dataflow (like carpriceDF)
13.	Click Save

![dfname](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/dfname.png)

14.	Click on Refresh now

![refresh](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/refresh.png)

15.	Click on the left most Edit entity icon in Actions

![editentity](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/editentity.png)

16.	Find the bore column.
17.	Click on the dropdown
18.	Click on Text filters

![editbore](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/editbore.png)

19.	Choose does not equal
20.	Enter ?
21.	Click OK

![doesnotequal](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/doesnotequal.png)

