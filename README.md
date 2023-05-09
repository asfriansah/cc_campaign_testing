# cc_campaign_testing
A bank is conducting a trial of the campaign being carried out whether it is successful in terms of using credit cards 
and whether there are differences in the use of credit cards between men and women.

Descripition of the dataset :
custid =  customer ID
sex = gender {0: Male, 1: Female}
AqChannel = Acquisition Channels Code
region = Residential area code
marital status = {1: Single, 2: Married}
segment = Segment/category code on the customer
pre_usage = the number of credit card usage before the campaign
Post_usage_1month = number of credit card usage 1 month after the campaign
Latest_mon_usage = number of credit card usage in the previous year
post_usage_2ndmonth = number of credit card usage 2 months after the campaign

Problems:
1. Do a hypothesis test whether the campaign was successful or not
2. Find out if there are differences in the use of credit cards between men and women.

Solutions:
1. Exploring data analysis
2. Do a hypothesis test.
3. Because the sample data used are two paired or dependent samples (both sample data are the same population data 
   but different treatments, where one is called control and the other is called treatment), and the number of data samples (n) > 30, 
   the hypothesis test can be done by Paired Two-Sample Z Test (but this method is not familiar).
