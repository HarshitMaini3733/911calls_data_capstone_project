# 911calls_data_capstone_project
Data Science Project on analyzing 911 calls data from kaggle.

## [Project 1 Code](https://github.com/TatyaVichu/911calls_data_capstone_project/blob/main/01-911%20Calls%20Data%20Capstone%20Project.ipynb)

### Overview :  

For this capstone project we will be analyzing some 911 call data from [Kaggle](https://www.kaggle.com/). The data contains the following fields:

<ul>
<li>lat : String variable, Latitude</li>
<li>lng: String variable, Longitude</li>
<li>desc: String variable, Description of the Emergency Call</li>
<li>zip: String variable, Zipcode</li>
<li>title: String variable, Title</li>
<li>timeStamp: String variable, YYYY-MM-DD HH:MM:SS</li>
<li>twp: String variable, Township</li>
<li>addr: String variable, Address</li>
<li>e: String variable, Dummy variable (always 1)</li>
</ul>

### Dataframe Used : 

![](Images/2022-09-05_07-54.jpg)

#### Basic Questions :

##### Top Five Zip Codes Used : 

![](Images/5%20Zip.jpg)

##### Top 5 Townships : 

![](Images/5%20Townships.jpg)

#### Creating New Features :

In the titles column there are "Reasons/Departments" specified before the title code. These are EMS, Fire, and Traffic. Create a new column called "Reason" that contains this string value.

*For example, if the title column value is EMS: BACK PAINS/INJURY , the Reason column value would be EMS. *

<b>New DataFrame(with reason column):</b>

![](Images/Reason%20DF.jpg)
