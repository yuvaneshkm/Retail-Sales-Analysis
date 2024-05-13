# Retail Sales Report

# Project steps:

## Requirement Gathering:
* Gathering requirements involves understanding the objectives, scope, and constraints of the project. This typically involves creating
    * BRD (Business Requirement Document)
    * FRD (Functional Requirement Document)
* Here, for this project both BRD and FRD are given in a single pdf file.


## Data Collection:
* The data for this project is collected from various sourses like Excel Spread sheet, CSV file, MySQL Database, and from a folder containing multiple files each containing similar data.


## Data Cleaning and Preprocessing:
* Data that comes from different sources is not in the proper format. So, we need to clean the data, as well as if needed we can add new columns to the existing table or we can create new table.
* The Data Cleaning is done with the help of DAX (Data Analysis Expression) in Power BI.
![Creating New Columns](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Creating%20new%20columns.png)
![Creating New Table for Datemaster](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Creating%20new%20table.png)


## Data Modeling:
* The Data is comming from different sources. So, it is necessary to structure and organize the data to create relationships between different tables, enabling more efficient analysis and visualization.
![Data Modeling](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Data%20Modeling.png)


## UI Report:
* Once the data cleaning and data modeling is over, then we can start creating our report in the Power BI desktop. The report is created based on the requirements given by the client.
* We can use various charts and graphs that are available in the Power BI desktop.
* Even we can use some custom charts in the Power BI Desktop for building our report.
* In this project I used  scroller chart.
![Using Custom Charts](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Custom%20Visuals.png)


## Additional Information (DAX Calculation) DAX--->Data Analysis Expression:
* While building the report you may need some measures(additional informations need to be calculated). These measures can be calculated by DAX in Power BI.
* Here I created Quater on Quater (QoQ) and Month on Month (MoM) total revenue change by using DAX (Data  Analysis Expression).
![Measures](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Measures.png)


## RLS (Role Level Security):
* After building the report, you need to implement RLS (Role Level Security) within the Power BI Desktop. This RLS will give specific access to specific users.
* That is, if you need to restrict particular user from seeing the particular countries sales, you can restrict them by using RLS.
![RLS](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Role%20Level%20Security.png)


## Create New Workspace:
* After completing the report, you need to share the report with your team mates. So, that we need to create a new workspace in Microsoft Fabric previously Power BI Service.
![New Workspace](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Creating%20new%20workspace.png)


## Publish:
* After creating the new workspace we now need to publish our end report to the workspace to share with the team mates.
![Final Report](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Final%20Report.png)


## Workspace Access:
* After Publishing the report to the workspace, we need to provide workspace access within the team.
![Workspace Access](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Access%20to%20the%20workspace.png)
* You can also implement Role Level Security(RLS) within the team.
![RLS](https://github.com/yuvaneshkm/Retail-Sales-Analysis/blob/main/screenshorts/Implementing%20Role%20Level%20Security.png)

## Dashboard:
* You can create a dashboard by pinning important visuals from various reports and organize it in a single dashboard.


* Share the Report
* Create App and Share