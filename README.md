# Introduction
- This dataset has information of 100k orders from 2016 to 2018 made at an e-commerce webiste in Brazil. 
- Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers.
- After a detailed analysis using SQL (Bigquery) here are the insights and recommendations : 

# Actionable Insights 
- The dataset consists of ~1 Lakh customers who have made orders from Sep’16 to Oct’18 coming from 27 different states of Brazil.
- Brazil has seen a steep increase in e-commerce activity since 2016, showing strong month on month growth till 2018. 
- The e-commerce growth fits inline with global trends which was made possible in the 2010s due to the widespread availability of smartphones, internet and social media.
- Nov’17 saw the highest volume, making a significant increase from the previous month (Oct’17). This can be explained by the festive purchases made by Brazillians for Christmas.
- Brazillians shop the most on afternoons (12PM-6PM) and least in dawn (12AM-6AM) 
- Brazillians shop more on weekdays than on weekends on average.
- The 3 top performing states across all months in terms of order volume  : SP, RJ, MG
- The 3 top performing cities across all months in terms of order volume  : Sao Paulo, Rio de Janeiro, Belo Horizonte
- The % increase in cost of orders from 2017 to 2018 was a whopping 139%
- State with highest total order price is SP (~5.2M)
- State with highest average order price is PB (~175)
- Avg time to delivery across the country is 12 days
- Avg difference between estimated and delivery date is 11 days
- Average freight value :
Highest 5 States : RR, PB, RO, AC, PI
Lowest 5  States : SP, PR, MG, DF, RJ
- Average time to delivery :
Highest 5 States : RR, AP, AM, AL, PA
Lowest 5  States : SP, PR, MG, DF, SC
- Average delivery time compared to estimated date :
Highest 5 States : AC, AM, RO, AP, RR
Lowest 5  States : AL, MA, SE, CE, MS
- Brazillians choice of payments is dominated by credit cards followed by UPIs as a distant second.
# Recommendations
- Festive season is marked by increased consumer spending across the globe. And so is seen in Brazil (Nov’17). I would recommend the e-commerce vendor to come up with lucrative festival deals, special discounts days, credit card offers in months leading up to Christmas (Oct, Nov, Dec)  and back it up with a strong marketing campaign especially in states with lower market penetration like RS, PR, SC.
- Since the e-commerce vendor’s order volume is low on weekends and dawn,it can provide special offers like midnight weekends discounts. They can also prioritise non-festive months for this scheme to keep the order volume high throughout the year.
- Even though PB has the highest average order price (~175) i.e. most premium customers, the time to deliver to this state is not even in the top 5. The e-commerce vendor can look into increasing its distribution channels into such states with premium customers. 
- The average difference between estimated and delivery date is 11 days. Although this tells that the e-commerce vendor has a dense and robust distribution channel, it is not able to give a good estimate to the consumer on when to expect the delivery. This can drive away those customers who need their orders delivered urgently and are unaware of the vendor’s optimistic estimates.The  vendor should look into this and calibrate its estimated delivery date by ~11 days accordingly. 
- Average time to deliver in states like RR and AP are 28 days! The vendor must increase its distribution channel efficiency  in these states if they want to increase market cap. If delivery is an issue due to remote location, the  e-commerce vendor can even think of building new godowns near these remote states.
- Credit cards are the primary choice of payment taken by customers. To capture a bigger market including those who do not have a credit card or a good CIBIL score to get one, the e-commerce vendor can offer special discounts on UPI transactions.
