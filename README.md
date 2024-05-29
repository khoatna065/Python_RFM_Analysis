# RFM_Analysis_Python
## I. Introduction

### 1. Business questions

  SuperStore is a global retail company. The Marketing Department wants to run campaigns during the Christmas and New year holidays to thank customers who have supported the company over the past time. As well as potential customers can be upgraded to be come loyal customers.

  The Marketing Director also proposed a plan to use RFM model to segment customers and then launch appropriate marketing campaigns. Analyze the current situation of the company and give suggestions to The Marketing Team. 

  With the retail model of SuperStore company, which indicator should be most focused on in the three indicators R, F, or M?

### 2. Dataset

Dataset includes 2 tables: ecommerce retail and segmentation. 

- Ecommerce retail dataframe:

[![alt](https://github.com/khoatna065/Python_RFM_Analysis/assets/167158955/6ae37129-8bde-43ed-b2a2-6dde04bda44b)

![alt](https://github.com/khoatna065/Python_RFM_Analysis/assets/167158955/2989bed5-b889-4d38-b2b1-2f8c8b25b822)

- Segmentation dataframe: We have to split each RFM score into single rows.

![alt](https://github.com/khoatna065/Python_RFM_Analysis/assets/167158955/6f7d3a07-2ee9-4e3d-a64d-78fa926a420a)

### 3. RFM model

RFM (Recency, Frequency, Monetary) analysis is a customer segmentation technique that uses past purchase behavior to divide customers into groups. RFM helps divide customers into various categories or clusters to identify customers who are more likely to respond to promotions and also for future personalization services.

RECENCY (R): Days since last purchase

FREQUENCY (F): Total number of purchases

MONETARY VALUE (M): Total money this customer spent.

## II. Data visualization & Insight

![alt](https://github.com/khoatna065/Python_RFM_Analysis/assets/167158955/eb6fb922-d1ce-4a24-a260-b0f6b5c9e903)

![alt](https://github.com/khoatna065/Python_RFM_Analysis/assets/167158955/570111ca-9562-4fc1-a2b1-a077f6b453c0)

![alt](https://github.com/khoatna065/Python_RFM_Analysis/assets/167158955/a5302bb3-0ab4-4c7a-85ab-e6d3630c80e3)

![alt](https://github.com/khoatna065/Python_RFM_Analysis/assets/167158955/b23c0c75-8da7-46b7-804d-0ba5bd185e6b)

![alt](https://github.com/khoatna065/Python_RFM_Analysis/assets/167158955/e2901877-12fd-463e-8fa8-7056dc8b6494)

![alt](https://github.com/khoatna065/Python_RFM_Analysis/assets/167158955/e2901877-12fd-463e-8fa8-7056dc8b6494)

- Distribution
    
    All three distributions are skewed to the right, indicating that customers have made recent purchases, low frequency, and spent very little money. At the end of the Recency distribution, there is a stretch showing that there are still many individual customers who have placed orders a long time ago. The Frequency model shows a large group of low-frequency customers with about 1 order per customer. The Monetary model is similar with a large segment of customers only spending a small amount of money.
    
- Segments
    
    The Champion customer group is the group with the largest number of customers and is also the customer group that brings the highest profit (with 19.25% of the total number of customers generating 62.89% of revenue), this shows that the company has a A large number of customers are very satisfied and attached to the product.
    
    Loyal and Potential Loyal groups (the ideal segment) account for about 19.4% of total customers and generate about 14% of sales.
    
    At the same time, the worrying point in the Hibernating group is too large, accounting for 16.04%. This shows that a significant portion of customers were once active but are no longer there. It is necessary to find out the reason why this group no longer buys (caused by product quality, service or other factors). Create strategies to attract customers back.
    
    A large number of customers in the At Risk, Lost Customers and Need to Sleep groups require businesses to pay attention to understanding the reasons behind their behavior and implement intervention measures to prevent customer loss. 
    

## III. Recommendation

SuperStore should focus more on enhancing Recency and Frequency performance. In this Christmas and New Year Marketing campaign, SuperStore needs to prioritize their efforts to retain Champions and Loyals group, and fine ways to reacquaint Hibernating group with brand.

- Champions: Reward them. Can be early adopters for new products and will help promote brand.
- Loyals: These users are responsive to your promotions, and you can suggest to them higher value products. Also, ask them for reviews.
- Potential Loyalist: Engage them with long-term offers like loyalty programs or membership reward. Suggest other categories of products to them.
- Hibernating: Share a high level brand video/ image that covers essence of brand. Recommend products for other categories and provide personalized offers.
- Lost: Make your presence known through different campaigns.
