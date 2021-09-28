# Adventure-works-cycles

Adventure Works is a large, multinational manufacturing company. The company manufactures and sells metal, composite bicycles, accessories, components, clothing to North American, European and Australian commercial markets. While its base operation is located in Bothell, Washington with 290 employees, several regional sales teams are located throughout their market base in several countries. Research objectives of the project is to provide Customer segmentation, Growth and Territory analysis based on the database provided. Adventure Works Cycles should look to broaden its market share by targeting their sales to their best customers, extending their product availability through age groups, demographics, and customer needs.

Hence to aid that data driven decision making I have created a Power BI report that consists of 3 pages:

- Exec Summary

- Product Details

- Customer Details

Breif description of each page of the report is as follows:

# Exec Summary

This page of the report has various visual components which are as follows:

Starting of with the **_Slicer_** which enables the comsumer of the report to filter it out on the basis of start of month for year 2015 to 2017. This slicer is capable of interacting with rest of the visuals on this page of the report only.

Next up we have a **_TreeMap_** which showcases the Total Orders by Categories, with added tooltips telling about Total Profit and Total Revenue for each Category.

Below it we have a **_Stacked Bar Chart_** for Total Orders by SubCategories it is set to **highlight** mode as interaction with TreeMap.

Besides them we have **_Matrix_** visual with **Drill Down** functionality which follows the following hierarchy [ **"CategoryName"** -> **"SubcategoryName"** -> **"ProductName"**] to show values of Total Orders and Return Rate. The formatting of these two value columns is done such that the "Total Orders" has **Data Bars** applied to it
and "Return Rate" has **Background Color** applied to it.

Furthermore we have **_KPI Cards_** for Monthly Revenue, Monthly Orders and Monthly Returns; having Previous Month Revenue, Previous Month Orders and Previous Month Returns respectively as their target goals and **Start of Month** set as Trend Axis.

There too is the presence of 2 **_Cards_** which points to the **Top Product by Orders and Profit** as visual level filter is applied to them to filter Top 1 Product Name.

At the end we have a **_Map_** along with the **_Slicer_** to select Continent the bubbles on the Map shows the country and further the size of the bubbles is by Total Orders.

# Product Details

This page in the Report is connected to the **_Matrix_** on the **Exec Summary** page via the **Drill Through** functionality.

First up in the page we see 3 **_Gauge Chart_** that read **Current Month's** Orders, Revenue and Returns v/s their Target value which is previous month's Orders, Revenue and Returns

Below it we could see 2 **_Line Charts_** showing Weekly Profit the 1st one shows **Total Profit & Adjusted Profit** and the 2nd one shows **Total Profit along with Line Trend and forecasting** with 90% confidence interval

We also have added a **_What if Parameter_** named **Price Adjustment** to see how the increase or decrease in the Product price would affect the weekly profit.

Finally at the bottom of page we have a **_Stacked Area Chart_** with axis as **Start of Week**, legend as **CategoryName**, value as **Total Returns** and tooltips for **Total Orders and Total Revenue**.

# Customer Details

First up we have a **_Matrix_** that shows **Top 100** Customer Names by Revenue with corresponding values of **Total Orders** and **Total Revenue** with **Data Bar** and **Background Color** applied to them respectively.

And at the top of the page we see 3 **_Donut Charts_** with Legends as **Gender, IncomeLevel and Occupation** and Value as **Total Orders**.

Next up we have **_Line and Clustered Column Chart_** with shared axis as **Start of Month**, column values as **Total Orders** and line value as **Total Revenue**.

Then we have a *_TreeMap_** with **Current Age** as Group and  **Total Orders** as values.

And at the bottom of the page we get to see 3 **_Cards_** that show **Top Customer, their Order quantity and Revenue generated by them**.

And the **Edit Interaction** option for the Cutomer Matrix with other visual elements is set to **Filter**.
