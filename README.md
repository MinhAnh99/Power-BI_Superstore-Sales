# Power BI_Superstore-Sales

## I. Introduction
### 1. Dataset

Global Superstore Sales

Dataset stores sales information of some products of a company worldwide, include of 3 data tables:

- Table 1: Orders: Fact order
- Table 2: People: Information of Sales person
- Table 3: Returns: Information of Returned orders.

### 2. Data dictionary
- Dimension: Customer ID, Location, Market, Item Category, Order date, Shipping date, Return 
- Measure: Sales, Profit, Number of item, shipping cost

### 3. Business Questions
- Determine potential items and markets before focusing on development. 
- Business must understand the features of revenue and profit distribution to determine whether the company should promote a strong product to multiple markets or each market will have distinct outstanding products.

## II. Applying design thinking
#### Step 1 - Empathize
![Screenshot 2024-01-30 205917](https://github.com/MinhAnh99/PBI_Superstore-Sales/assets/74374068/538641d4-d142-458b-9831-14e0211bf16a)

#### Step 2 - Define point of view
![Screenshot 2024-01-30 210001](https://github.com/MinhAnh99/PBI_Superstore-Sales/assets/74374068/cce78ab6-cf3e-4341-8f2e-0f2f1aae001b)

#### Step 3 -  Ideate
![Screenshot 2024-01-30 210304](https://github.com/MinhAnh99/PBI_Superstore-Sales/assets/74374068/e6a87c51-ae86-4938-9756-4ffffea040b2)

#### Step 4 -  Prototype
![Screenshot 2024-01-30 210317](https://github.com/MinhAnh99/PBI_Superstore-Sales/assets/74374068/0e777ced-06d6-4614-ab4c-07394f9704a5)

#### Step 5 -  Review
![Screenshot 2024-01-30 210325](https://github.com/MinhAnh99/PBI_Superstore-Sales/assets/74374068/e7dd953b-1399-4e9e-8ab9-e48f9adcec81)

## III. Building dashboard
### 1. Overview
![Screenshot 2024-02-01 214241](https://github.com/MinhAnh99/Power-BI_Superstore-Sales/assets/74374068/efb48f0a-b355-4567-be78-0761b69c96d4)

### 2. Market
The top three revenue-generating markets are APAC (1.78 million), the EU (1.36 million), and the United States (1.11 million). In general marketplaces, the proportions of the three industries are approximately equal, but technology industry continue to account for the biggest amount.
- APAC (1.78 million)
![apac](https://github.com/MinhAnh99/Power-BI_Superstore-Sales/assets/74374068/81c8c260-480a-44ca-8bc7-3698581b841a)

- EU (1.36 million)
![image](https://github.com/MinhAnh99/Power-BI_Superstore-Sales/assets/74374068/d792f4a9-ae62-4a2c-8712-327a40913703)

- US (1.11 million)
![image](https://github.com/MinhAnh99/Power-BI_Superstore-Sales/assets/74374068/8b3cc411-f47d-4475-9805-e4c6d001a41a)


- The EMEA market has the highest compound annual growth rate (CAGR) (21.38%), followed by APAC and EU (19.01%). Although the United States is one of three key markets, its growth rate is the slowest, at around 10%.

### 3. Product
- The company's products are all seasonal, with sales growing greatly nearly the end of the year.
- The Office Supplies and Technology industry has the highest Gross Profit Margin (14.03% and 13.97%), which is nearly double the Furniture industry's margin of 6.76%.
- The following sub-category products make the most revenue: phones (0.83 million), copiers (0.72 million),
  ![image](https://github.com/MinhAnh99/Power-BI_Superstore-Sales/assets/74374068/63e48798-2075-498a-aed0-859dc7536ca6)
  
  chairs (0.75 million), and bookcases (0.69 million).
  ![image](https://github.com/MinhAnh99/Power-BI_Superstore-Sales/assets/74374068/e627a14e-966c-4e83-a66e-4f380dd43aff)

- The following sub-categories have the highest profit margins: paper (24.66%), labels (19.63%), envelopes (17.57%), accessories (17.95%), and copiers (16.58%). However, only Copier and Accessories provide significant revenue. The remaining products are all included in a group of five with the lowest revenue in the company.
- Particularly, Tables is a product that has a negative profit margin (7.09%) although having an acceptable revenue (401K).
- ![image](https://github.com/MinhAnh99/Power-BI_Superstore-Sales/assets/74374068/220703ac-b60e-4199-9eb8-88295a7d13e6)


## IV. Insights
- From 2011 until the end of 2014, sales generally increased at a compound annual growth rate (CAGR) of 19.01%. However, sales generally rises year over year over all categories until the fourth quarter, at which point it falls suddenly in the first quarter of the next year.
- Over the past four years, the gross profit margin remained stable at 11%.
- The B2C customers group provides the most revenue for the organization (51%), followed by Corporate (31%) and Home Office (17%). However, in recent years, revenue from this group has declined slightly. The revenue structure in 2014 shows that the Home Office customer group tends to increase.
 	
## V. Recommendations
- Find an effective business development plan by researching why revenue frequently decreases at the beginning of the year.
- Continue to promote business strategies in major markets like APAC and the EU, while also growing and exploring development methods for future areas with strong CAGRs like Canada and Africa. This is a massive market in the United States, but it also has a large amount of inertia. As a result, a new business plan is needed to promote revenue growth.
- Promote marketing activities in the third and fourth quarters of every year, focusing on potential products (low sales but high profit margin) such as Accessories, Art, Papers, Evelopes, in addition to products in the Phones, Bookcases, Copier, and Chair is inherently the company's strength.
- Promote upselling and cross-selling to boost order value.

