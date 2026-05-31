<img width="1918" height="1047" alt="Image" src="https://github.com/user-attachments/assets/d354d6e5-aee6-43b9-970a-1eb2e601757f" />

## TripleTen

**Program:** BI Analytics

**Sprint:** 5-Storytelling with Data

**Project:** Superstore - Causes of Returns

**Analyst:** Cesar A. Nieto


PATH FOR TABLEAU DASHBOARD:
https://public.tableau.com/views/Project5StorytellingwithData/UNDERSTANDINGRETURNS?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

### Overview
This analysis aims to determine the actions to be taken after appropriate measures and graphic demonstrations have revealed the reasons why the company experiences a considerable level of post-sales order returns.

### Research
**Summary of Analysis**
To determine the causes of order returns, we attempted to cross-reference customer feedback with the available data. Unfortunately, Superstore's data does not provide information on the reasons customers cite for order returns, whether due to quality issues or operational deficiencies in shipping and/or delivery. Therefore, we will attempt to determine the causes based on statistical data. The following is the scope of the
research:

1. **Period:** Four years (2018-2021), with annual and monthly comparative periods.
2. **Location:** US (50 states), covering all states.
3. **Strategy:** Comparative analysis of transactions (order returns) by product categories and sub-categories. We have also identified the market segments involved and even conducted an analysis at the individual customer level.
4. **Measuring Returns:** To obtain a true understanding of the level of order returns, we consider the following measures appropriate:
_Order Return Rate
Number of Returned Orders
Cost of Returned Orders_
5. **Causes of Returned Orders:** The increase in returns is driven by a combination of:
_Product Issues.- Inconsistent sizing standards, quality variability from suppliers, and Inaccurate or incomplete product descriptions.
Logistics Issues.- Packaging not suitable for long-distance shipping
Carrier handling issues.- Incorrect item fulfillment
Customer Expectation Gaps.- No Information available_

**Overview of Visualizations** 
To display the analyzed information and draw conclusions, we have created the following Worksheets, Dashboard, and Story in Tableau. The following is the explanation of what each worksheet contains and how it should be interpreted. _All our worksheets and the dashboard itself are sensitive to the following filters: Year, Month, State, Product Category, and Product Sub-Category._

1. **Return Rate:** The top right corner of our dashboard shows the return rate in the US (50 states) during the whole period (2018-2021), including all products Categories and Subcategories. This rate will vary if we apply one, some, or all the mentioned filters. It is the result of the calculation of the average number of returned orders.
2. **Correlation: Sales vs Returns by Sub-Category:** Expressed in US$ using the product sub-category level to get a better idea of what kind of products are being returned
3. **Return Rate by Customers:** This visualization displays the number of orders returned by individual customers, offering the ability to apply the aforementioned filters in various combinations. This functionality allows us to identify behavioral trends based on a variety of different factors.
4. **Return Rate by Category:** This visualization displays the number of orders returned by product categories, offering the ability to apply the aforementioned filters in various combinations. This functionality allows us to identify the product categories' returns based on a variety of different factors.
5. **Order Returns by Year/Month:** This chart enables the analysis of return trends based on seasonality, as well as comparative analysis across specific months and years.
6. **Return Rate by State:** Provides a graphical, macro-level overview of return patterns across each state.
7. **Return Rate by Year/State:** Provides an annual, macro-level overview of return patterns across each state.
8. **Understanding Returns (Dashboard):** To understand how to use the Dashboard first and foremost, it should be viewed as a diagnostic tool
designed to assist stakeholders in performing the following key functions:
_**Monitor Return Performance**
a. Across various dimensions, including Time, Geography, and Product Type/Quality.
**Investigate the Underlying Causes of Returns**
a. By utilizing all available filters to generate in-depth metrics, users can isolate specific issues by cross-referencing data points simultaneously to
draw meaningful comparisons.
**Make Data-Driven Decisions Based on the Results**
a. To make well-founded decisions, stakeholders should begin with a general, global overview of the return rate and ask themselves whether the current level of returns is minimally acceptable.
b. Regardless of that initial assessment, the Time Dimensions help determine during which periods or seasons return rates tend to rise.
c. In the meantime, the Geographic Dimensions reveal which regions of the country exhibit the highest volume of returns.
d. The Product Type/Quality Dimensions indicate which products have a higher propensity to be returned, while combinations of all these
dimensions provide a deeper and more comparative insight into the identified problems._
9. **Presentation - Story Arc (Story):** The following are the story points you will find in our Tableau Story; they will be supported for worksheets
_**The Most Important Signal**
Caption: Between 2018-2021 this was the level of Order Return Rate at Superstore in United States including all products categories and subcategories.
**How We Measure Returns**
Caption: Return rate shows customer behavior; total returns and cost of returns quantify operational impact. Use all three for a complete view.
**Geographic Hotspots**
Caption: California, Texas, and Florida show the highest return rates, driven by long shipping distances and heavy online ordering.
**Product Categories Driving Returns**
Caption: In general, the three main product categories show the same return rates, however, Technology is the one who has the highest rate of returns.
**Customer Behavior Patterns**
Caption: Filtering out one-time buyers reveals repeat customers with consistently high return rates, indicating expectation gaps.
**Composite View: Connecting the Factors**
Caption: Combining geography, product category, and time reveals a chain reaction: inaccurate info + weak packaging + long-distance shipping.
**How to Use the Dashboard**
Caption: Start with overall return rate, drill down by category or geography, and use filters to isolate root causes.
**Recommended Actions**
Caption: Improve product descriptions, standardize sizing, reinforce packaging, retrain fulfillment centers, and monitor returns in real time.
**Conclusion & Next Steps**
Caption: Addressing product clarity, quality consistency, and operational gaps will reduce returns and improve customer experience nationwide._

### Conclusion
**The rise in returns is actionable and reversible. By addressing product clarity, quality consistency, logistics reliability, and customer expectations, the company can significantly reduce return rates and improve profitability across all 50 states.**
