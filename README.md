# Financial Sample Analysis

##Table of content.

- [Data Source](#data-source)
- [Data cleaning and Preparartion](#data-cleaning-and-preparation)
- [Results/Findings](results/findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

### Project overview

This data analysis project aims to provide insights into the financial report of a producing  company over two years which are 2013 and 2014. By analyzing various aspects of the financial data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's financial report.

### Data source

Sales Data: The primary dataset used for this analysis is the "financial sample.xslx." file, containing detailed information about financial details of the company.

### Tools

- Excel- Data cleaning and building of dashboards.
    - [download here](https://microsoft.com)
- Powerbi-Data formatting and visualization.

 ### Data cleaning and Preparation

  In the initial data preparation phase, we performed the following tasks:
1.	Data loading and inspection.
2.	Handling missing values.
3.	Data cleaning and formatting.

### Explanatory Data Analysis

  EDA involved exploring the sales data to answer key questions, such as:
-	What is the overall profit trend per date?
-	Which products are top sellers per country and year?
-	Which of the products gives the best sales and profit ?

 ### Data Analysis

 Include some interesting code/features worked with
 
 ```DAX
 Units sold bin 2 = IF(financials[Units Sold]<=500,"0-500",IF(financials[Units Sold]<=1000,"501-1000",IF(financials[Units Sold]<=1500,"1001-1500",IF(financials[Units Sold]<=2000,"1501-2000",
    IF(financials[Units Sold]>2000,"above 2000")))))
Calender = CALENDAR(MIN(financials[Date]),MAX(financials[Date]))

```

### Results/Findings

The analysis results are summarized as follows:
1.	The company's financials have been steadily increasing over the two years, with a noticeable peak during the last quarter of the year.
2.	Product Paseo is the best-performing prodduct in terms of sales and revenue while the government segment gives all the product a good sale and profit.
3.	France and Canada are the country with the highest profit 
4.	Channel partners segment and united States of America should be targeted for marketing efforts.
5.	The low discount band can be seen to be associated with products of higher sales unit and profit 


### Recommendations
Based on the analysis, we recommend the following actions:
  -	Invest in marketing and promotions during peak sales seasons to maximize revenue.
  -	Focus on expanding and promoting Paseo and VTT products.
  -	Channels and Midmarket Segment needs more marketing strategies while Government and Small business Segment should be more encouraged.
  -	The use of High discount band may need to be reconsidered.
  -	Implement a customer segmentation strategy to target countries with low sales and profit effectively.


### Limitations

I had to transform the numbers to whole number the units sold column because they would have affected the accuracy of my conclusions from the analysis. And I removed Montana product from the products column based on recommendations


### Dashboard

![financial dashboard 1](https://github.com/ADETOLAADEBANJI/ANALYSED-EXAMPLES/assets/149164492/895429cf-364c-473e-9d0a-e795dcfdb8ac)


### References







 

 
  

   


  
