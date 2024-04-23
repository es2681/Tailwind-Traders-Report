# Tailwind Traders Sales Report

## Project Overview
Tailwind Traders is an international retailer for hardware such as plumbing, lighting, and gardening supplies among other home improvement products. Tailwind Traders requested a report detailing the company's recent sales data.

## Resources
- The Countries, Purchases, and Sales Data tables were imported into Power BI from Microsoft Excel files. Excel was used to clean and transform the Sales Data table.
- The Exchange Data table was added direcctly to the project using a Python script in Power BI.
- A DAX expression was written in Power BI to add the Calendar table.
- Power BI Desktop was utilized to further clean, transform, and load data. The data model was designed using Power BI.
- The final report was published to a new dashboard in Power BI Service.

## Analysis & Results
### Transforming Sales Data in Microsoft Excel
Excel formulas were used to calculate Gross Revenue, Total Tax, and Net Revenue for each product. These columns were added to the Sales Data table.

### Configuring Data in Power BI
The Microsoft Excel Sales Data, Purchases, and Countries tables were imported into Power BI. The data was examined for blank cells or any unexpected entries. Each column was checked or altered to ensure the correct data type designation. A currency exchange table was added to the file to homogenize the sales figures.

### Designing the Data Model
The table relationships were configured to ensure the accuracy of the data model. A Calendar table was generated using a DAX formula and was then marked as a Date Table. Using the Exchange Data table, the Sales Data table was duplicated with all currency converted to US dollars and renamed Sales in USD.
![Data Model](https://github.com/es2681/Tailwind-Traders-Report/blob/main/Resources/Data%20Model.png)
### Calculating Aggregations
DAX code was used to calculate aggregations for Yearly Profit Margin, Quarterly Profit, Year-to-Date Profit and Median Sales. 

### Developing a Sales Report
Graphs, charts, and other visuals were generated according to Tailwind Trader specifications into a Sales Report, including pages for Tailwind Traders' Sales Overview and Profit Overviews. Text was enlarged and an accessible theme was used so that the report is accessible to a greater audience.
#### Sales Overview Page
![Sales Overview](https://github.com/es2681/Tailwind-Traders-Report/blob/main/Resources/Sales%20Overview.png)
#### Profit Overview Page
![Profit Overview](https://github.com/es2681/Tailwind-Traders-Report/blob/main/Resources/Profit%20Overview.png)

### Creating an Executive Dashboard
The finalized report was published to Power BI Service. The charts were added to an Executive Dashboard where they were designed to be viewed via the web on a computer as well as a mobile device.
## Summary
