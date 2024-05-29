# RFM_Analysis_Python
## I. Introduction

### 1. Business questions

  SuperStore is a global retail company. The Marketing Department wants to run campaigns during the Christmas and New year holidays to thank customers who have supported the company over the past time. As well as potential customers can be upgraded to be come loyal customers.

  The Marketing Director also proposed a plan to use RFM model to segment customers and then launch appropriate marketing campaigns. Analyze the current situation of the company and give suggestions to The Marketing Team. 

  With the retail model of SuperStore company, which indicator should be most focused on in the three indicators R, F, or M?

### 2. Dataset

Dataset includes 2 tables: ecommerce retail and segmentation. 

- Ecommerce retail dataframe:

[![alt](https://drive.google.com/drive/u/0/folders/1VnSzvzJ6Rvdh_OvLgTvcNYmSNobij41l)](https://github.com/khoatna065/Python_RFM_Analysis/issues/1#issuecomment-2136418742)

![alt](https://prod-files-secure.s3.us-west-2.amazonaws.com/55146c29-fb50-49f3-a16e-d40cce873dc3/f3694098-0050-4b45-85de-6d747933100a/Untitled.png)

- Segmentation dataframe: We have to split each RFM score into single rows.

![alt](https://prod-files-secure.s3.us-west-2.amazonaws.com/55146c29-fb50-49f3-a16e-d40cce873dc3/90f6e9f2-3227-4d2e-899b-fc6e5bd82781/Untitled.png)

### 3. RFM model

RFM (Recency, Frequency, Monetary) analysis is a customer segmentation technique that uses past purchase behavior to divide customers into groups. RFM helps divide customers into various categories or clusters to identify customers who are more likely to respond to promotions and also for future personalization services.

RECENCY (R): Days since last purchase

FREQUENCY (F): Total number of purchases

MONETARY VALUE (M): Total money this customer spent.

## II. Data visualization & Insight

![alt](https://prod-files-secure.s3.us-west-2.amazonaws.com/55146c29-fb50-49f3-a16e-d40cce873dc3/8176aa39-03c3-43e0-81f0-4e4f7d97ebb2/Untitled.png)

![alt](https://prod-files-secure.s3.us-west-2.amazonaws.com/55146c29-fb50-49f3-a16e-d40cce873dc3/bda739b2-f883-4e69-be7d-bb13dfba037e/Untitled.png)

![alt](https://prod-files-secure.s3.us-west-2.amazonaws.com/55146c29-fb50-49f3-a16e-d40cce873dc3/3a273b8f-4f41-455b-9547-89a8fd180518/Untitled.png)

![alt](https://prod-files-secure.s3.us-west-2.amazonaws.com/55146c29-fb50-49f3-a16e-d40cce873dc3/ef4011c6-f0c2-412b-859e-ac05e745f929/Untitled.png)

![alt](https://prod-files-secure.s3.us-west-2.amazonaws.com/55146c29-fb50-49f3-a16e-d40cce873dc3/5da62101-519e-4b42-8244-7a9c0652b8ed/Untitled.png)

![alt](https://prod-files-secure.s3.us-west-2.amazonaws.com/55146c29-fb50-49f3-a16e-d40cce873dc3/d3c6dca5-5921-499b-ba7f-faebdb156823/Untitled.png)

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
