# Suspected-Fraud-Analysis.Tableau

## **Suspected Fraud Analysis Dashboard**

**Overview**

The Tableau Public dashboard provides insights into suspected fraud within the supply chain data. It includes various visualizations that help in understanding the trends and patterns of fraud over time. 

**Datasource**
You can download the datasource from my repository.

### Dashboard Components

#### Percentage of Suspected Fraud by Shipping Mode
**Description:** This bar chart displays the distribution of fraud incidents by shipping class.
**Insight:** The majority of fraud incidents are associated with the Standard Class (59.28%).


#### Suspected Fraud Trend by Year
**Description:** This line chart shows the trend of fraud incidents over the years from 2014 to 2018.
**Insight:** There are noticeable fluctuations and peaks in fraud incidents over the years.

#### Top Product Fraud and Loss Analysis
**Description:** This bar chart lists the top product codes associated with the most fraud incidents.
**Insight:** Product code 1004 has the highest number of fraud incidents.

#### Percentage of Suspected Fraud By Customer Segment
**Description:** This pie chart shows the distribution of fraud incidents by customer segment.
**Insight:** The Consumer segment has the highest number of fraud incidents.



# **Tableau Dashboard Visuals**

**Percentage of Suspected Fraud by Shipping Mode**
**Visualization Type:** Bar Chart

**Fields Used:**
Dimensions: Shipping Class
Measures: Count of Fraud Incidents
Insights:
Standard Class: 59.28%
Second Class: 18.44%
First Class: 16.89%
Same Day: 5.39%

![Percentage of suspected fraud by shipping mode](https://github.com/user-attachments/assets/7618f4e1-dbb3-4a06-8b7e-5e95d732e6aa)



**Suspected Fraud Trend by Year**
**Visualization Type: Line Chart**

Fields Used:
Dimensions: Year
Measures: Count of Fraud Incidents
Insights:
Significant peaks in fraud incidents observed in certain periods.
Overall trend shows fluctuations from 2014 to 2018.

![Suspected Fraud Trend by Year](https://github.com/user-attachments/assets/9fcb7f99-5b95-4e3b-a1ef-b87a18077ac4)




**Top Product Fraud and Loss Analysis**
**Visualization Type: Bar Chart**

Fields Used:
Dimensions: Product Code
Measures: Count of Fraud Incidents
Insights:
Product code 1004 has the highest number of fraud incidents.
Other top products include codes 957, 403, 1073, and 365.

![Top Product Fraud and Loss Analysis](https://github.com/user-attachments/assets/0326993f-574b-462c-849b-ba89dd8dc648)




**Percentage of Suspected Fraud By Customer Segment**
**Visualization Type: Pie Chart**

Fields Used:
Dimensions: Customer Segment
Measures: Count of Fraud Incidents
Insights:
Consumer segment has the highest number of fraud incidents.
Other segments include Corporate and Home Office.

![Percentage of Suspected Fraud by Customer Segment](https://github.com/user-attachments/assets/1bc2c722-732b-455c-a1ac-db4438ee136f)



**Connecting SSMS and Tableau Public via Excel**

**Exporting Data from SSMS:**
Data from the SSMS database is exported to Microsoft Excel using Power Query.

**Connecting Excel to Tableau Public:**
The Excel file with the exported data is then imported into Tableau Public as a data source.

**Creating Visualizations:**
Various visualizations are created in Tableau Public using the imported data.
Building the Dashboard:
The visualizations are arranged into a cohesive dashboard that provides insights into suspected fraud patterns.

**Conclusion**

This project demonstrates the integration of SSMS, Excel, and Tableau Public to analyze and visualize supply chain data. The resulting dashboard provides valuable insights into patterns of suspected fraud, helping to identify and address potential issues within the supply chain.

# **Suspected Fraud Analysis Dashboard**

![Suspected Analysis Dashboard](https://github.com/user-attachments/assets/ebf44127-e359-4698-a47a-1e21d1c89f57)
