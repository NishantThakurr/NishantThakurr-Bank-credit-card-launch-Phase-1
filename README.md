
# AB testing for Credit card customer analysis(Phase 2)

Description:After finalizing on the target group 
(18-25 age group), we wanted to check that our decision was right or not. For this we will do campaign planning, AB testing and 2 sample Z test.
We will do a trials run for our new credit card. We will sample out two group of customers. Control group will get an old credit card to use whereas target group will get our new credit card to use for a specific time.

## Roadmap

### Step 1: Campaign planning
Deciding target and control group:
For our trial of new credit card, we need to figure out how many customers do we require for our AB testing according to the power and effect size that we aspire and gives us realistic numbers also.We used significance level of 0.05 and power=0.8 and effect size of 0.4 .
We decided to randomly target 100 customers for both control and test group and estimated that 40% customers will use the credit cards. So at last, we will have 40 customers in control group and test group as well.

### Step 2: Launch Campaign for 2 months

### Step 3: Collecting transactional data from the Campaign


### Step 4: Hypothesis testing
Based on the transactional data, we wanted to test that average transaction of customers using our new credit card were higher than average transaction of customers using old credit card
Null hypothesis: test_group_avg_tran is not significantly more than control_group_avg_tran
Alternate hypothesis: test_group_avg_tran is significantly more than control_group_avg_tran

### Step 5: Final decision
The Zscore was 15.1 and p values was 0 indicating that we have to reject the null hypothesis.
So, test_group_avg_tran is significantly more than control_group_avg_tran



## Outcomes

So according to the two sample Z test in our A/B testing, we decided that since our new credit card has better transaction value than the old credit card, it can be launced with success.

