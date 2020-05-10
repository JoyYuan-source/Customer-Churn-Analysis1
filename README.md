# Customer-Churn-Analysis1
In this project, our goal is to estimate a BG (Beta Geometric) Model and predict active customers using customer data of GetFit, a company that runs outdoor health ﬁtness classes.

# Company Introduation 
GetFit is a company that runs outdoor health ﬁtness classes. The classes run on a monthly cycle that begins on the ﬁrst day of each month. New customers are “booked” at the beginning of the month, and decide to renew or cancel just before the beginning of the next month. For example, a cohort that is acquired initially on January 1 will be active for all of January. Just before February 1, some members of the January cohort will renew (and will be active in February), while others will cancel. By deﬁnition, those who cancel have been active for one month, while those who renew are active for at least two months. At the end of February, some members of the January cohort will renew for March (active for at least three months), while others will cancel (active for exactly two months), and so forth.

It is now early September, and eligible customers have already made their renewal decisions for the month. The data set I have provided to you contains some information about 2,132 customers who were acquired in January, February, March, or April (i.e., four diﬀerent cohorts), and may or may not have churned through August. These customers can be considered to be a random sample from the population of potential GetFit customers, and there is no substantive diﬀerence across cohorts.

# Data 
For each of these customers, we observe a customer ID number, the index of the month in which the customer was acquired (the first month in which the customer was active), and the index of the month after which the customer canceled service (i.e., the last month of the customer relationship). If last is missing (denoted by NA), it means the customer is still active in September (and thus must have been active in August).

For example, a customer for whom first is 3 and last is 8 was active for 6 months (March through August), but decided to not renew for September. Another customer with first=3 and a missing last value has been active for 6 months so far, but remains active in September. Put another way, the ﬁrst customer churned at the 6th renewal opportunity, while the second customer has survived all 6 renewal opportunities. Note that the duration of the survival time depends on when the customer was ﬁrst acquired.


