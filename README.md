Online retail is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. 
The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.



# What we want to acheive ?

segement the Customers based on RFM so that the company can target its customers efficiently.

### R (Recency): Number of days since last purchase
### F (Frequency): Number of tracsactions
### M (Monetary): Total amount of transactions (revenue contributed)




# Advantahes of segementing the Customers based on RFM 

### 1. Personalized Marketing:
RFM segmentation allows companies to create highly personalized marketing campaigns. 
By understanding the recency of a customer's last purchase (R), their purchase frequency (F), and the monetary value of their purchases (M), companies can send targeted messages, 
product recommendations, and offers that resonate with each customer segment's preferences and behaviors.

### 2.Increased Customer Engagement: 
Targeting customers with relevant offers and messages enhances their engagement with the brand. Customers are more likely to respond positively when they receive offers that 
align with their buying habits and needs, leading to higher open rates, click-through rates, and conversion rates.

### 3.Improved Customer Retention:
Identifying and segmenting high-value and loyal customers allows companies to develop specific retention strategies for these segments.
By acknowledging and rewarding loyal customers, businesses can foster stronger brand loyalty and reduce churn rates.

### 4.Improved Marketing ROI
Since RFM segmentation targets customers with higher potential to convert, the return on investment (ROI) for marketing campaigns tends to be higher. 
This is because marketing efforts are directed towards customers who are more likely to make a purchase, leading to increased revenue and profitability.



# Ouput of Model 
 The complite customers are divided into 3 clusters where each cluster have one unique clsuter_ID.\n
 The Clusters_ID are 0 , 1, 2

### 1. Amount vs Clusters ID
This Below graph show 

           1.Customers having cluster_ID=0 are spending less money into the shop.
           
           2.Customer  having cluster_ID=1 are spending more money into the shop.
           
           3.Customer having cluster_ID=2 are moderatly spending money into the shop.
           


![Screenshot (1074)](https://github.com/vaibhav-423/Customer_Segmentation_Machine_Learning/assets/109592379/cbd8a977-2038-437a-a027-c5a82bb4fd5a)


### 2. Frequency vs Clusters ID

This Below graph show 

           1.Customers having cluster_ID=0 are less repeating customers.
           
           2.Customer  having cluster_ID=1 are highly repeating customers.
           
           3.Customer having cluster_ID=2 are moderatly repeating customers.


![Screenshot (1075)](https://github.com/vaibhav-423/Customer_Segmentation_Machine_Learning/assets/109592379/0a937cb1-58a9-4997-903a-1ee97c31156d)



### 2. Recency vs Clusters ID

This Below graph show 

           1.Customers having cluster_ID=0 have high Recancy.
           
           2.Customer  having cluster_ID=1 have very less Recency.
           
           3.Customer having cluster_ID=2 have moderate Recency.

![image](https://github.com/vaibhav-423/Customer_Segmentation_Machine_Learning/assets/109592379/da8167fc-4bd6-4935-8598-8ba123ea0f4a)

