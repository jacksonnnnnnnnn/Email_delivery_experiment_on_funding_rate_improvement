CREATED BY 👀
Zhuoming Yang(zy2364@nyu.edu)
## Email_delivery_experiment_on_funding_rate_improvement

Our goal is to discover the best Email to deliver and verify the effectiveness on various groups of users. To get there we’ll have to provide the following configuration for teams to adjust. 
-	Message(s). 
-	User-segments, 
-	Sequence and frequency. 
-	Metrics - target metrics and counter metrics. 

### Hypothesis
Email is the best way to reach the approved and unfunded users. The category and inventory of messages are exhaustive and addresses the concerns that hold users back from funding the account.

We expect the impact to users behavior, including Email open rate, funtding rate, comes from the following sources:
- User Segmnet
- Email Template Content, including subject tittle, GIF, text content
- The order to sned email message
- The Frequence of sending Emails

### GOALS
- Increase Email opening rate
- Increase Funding rate
- Confirm different funding and activation rates across unfund segments
- Confirm different funding and activation tates across variance setup combinations to send out Emails

### Metrics
- Email click through rates, app opens
- Funding Rate VS Control
- Activation: % of users that links their bank account, funds, complete 1 trades, complete 2+ trades

## Experiment
### General Approach
- Create a large pool of messages across differet catgories, 10 in total
- Send message to undertand relationship and engagement rate amoung message and user segment(12 user segments with 2 delivery frequencies, 24 treatments in total)

### Users segmentation
The segmentation to choose users samples is rule-based. In control and variants, we perform stratified sample of the user from each of the following segment:
- Account approved within 6 months: True/False
- Bank linked: True/False
- If there is any activity in the past 20 days: True/False
- If there is any trade activty in the past 5 days: True/False
