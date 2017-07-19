# The State Of DevOps Report 2017

The state of DevOps reports in general are a great statistical and analytical look at what is happening in the real world with regards to DevOps and the associated organizational cultures. This report can be found [here](https://puppet.com/resources/whitepaper/state-of-devops-report)

It covers a number of scenarios which include but are not limited to:

1. Private software companies
1. Not for profits
1. Government

This report is the latest in annual reports for the last 6 years including more than 27,000 DevOps survey responses in total.

## How is software quality measured and what was the effect of DevOps practice on this?

" Because quality is inherently difficult to measure, we used unplanned work and rework as proxies.  Last year we found that high-performing organizations spend 22 percent less time on unplanned work and rework. As a result, they are able to spend 29 percent more time on new work, such as new features or code.  This year, we are happy to report that high-performing organizations spend 21 percent less time on unplanned work and rework, and 44 percent more time on new work. "

## Demographics of this report

- This survey was of 3,200 people around the world. 
- 16% of respondents were on dev ops teams in 2014
- 27% are in DevOps teams in 2017


## How IT performance is measured

Two axis:

- Throughput of code - how frequently a team is able to deploy code, and how fast between commit and deploy
- Stability - downtime and how many changes succeed vs fail


## Transformational Leadership

A great focus of the report includes what is claims is often overlooked in DevOps **leadership** and what they call **transformational leadership**. The model dictates that the five characteristics of a transformational leaders are:

- Vision
- Inspirational communication
- Intellectual stimulation
- Supportive leadership
- Personal Recognition

### Notable stats

- Observed significant differences in leadership characteristics between high-, medium- and low performing IT teams. 
- High-performing teams reported having leaders with the strongest behaviors across all dimensions: vision, inspirational communication, intellectual stimulation, supportive leadership, and personal recognition
- Low-performing teams reported the lowest levels of these leadership characteristics.
- The bottom third on transformational leadership were half as likely to exhibit high IT performance
- Analysis also found that transformational leadership is highly correlated with employee Net Promoter Score (NPS). 
- Interestingly, we found evidence that the presence of leaders with transformational characteristics is not enough to achieve high DevOps outcomes


## IT performance & organizational performance


## Additional measures of organizational performance

Much of previous reports have looked at profitability, market share etc but this report they have looked and not-for-profit and government sectors and concluded similar findings in DevOps helping to reach their goals or desired outcomes faster and easier.

## Technical Practices

- Trunk based development
- Low coupling

    This is measure by:

    - Can do testing without requiring integrated environment
    - The applications can be deployed independent of other applications and services it depended on

    Findings:

    - High performing teams were more de-coupled
    - Teams allowed to use the tools of their choice did better at continuous delivery

### Systems architecture and communication bandwidth

There is a idea of Conways law that says:

"organizations which design systems ... are constrained to produce designs which are copies of the communication structures of these organizations." 

The report recommends that orgs should use "reverse conways law" in that organizations should architect around team boundaries to ensure that teams can get their work done without high-bandwidth communication between teams.

Often this requires an architectural approach to the software that includes bounded contexts and APIs as a way to decouple large domains resulting in smaller, more loosely coupled units. The key is service oriented architecture that allows for testing of the individual services independent of each other.

### Biggest contributors to continuous delivery

Even bigger than test and deployment automation is that teams can:

 - Make large-scale changes to the design of its system without permission from someone outside the team.
 - Make large-scale changes to the design of its system without depending on other teams to make changes in their own systems, or creating significant work for other teams. 
 - Complete its work without needing fine-grained communication and coordination with people outside the team. For example, not having to check 12 Google calendars to get feedback. 
 - Deploy and release its product or service on demand, independently of other services the product or service depends upon. 
 - Do most of its testing on demand, without requiring an integrated test environment. • Perform deployments during normal business hours with negligible downtime.

### Trunk-based development

Trunk based development means to that teams work in small batches and develop off of trunk or master. While this is not the industry norm and many do use branching strategies the report found the following contributed to higher software delivery performance:

- Merging code into trunk on daily bases
- Having branches or forks with very short lifetimes (less than a day)
- Having fewer than three active branches

This flies in the face of the excepted GitHub model but the report did some further analysis to see if there was a correlation with short lived branches or trunk development and found:

- High performers have the shortest integration times and branch lifetimes, with branch life and integration typically lasting hours. 
- Low performers have the longest integration times and branch lifetimes, with branch life and integration typically lasting days. -
- These differences are statistically significant.

## Lean project management

Lean product management compirese of two capababilties as investigated in this repport:

- Splitting work into small batches and making visible the flow of work through the delivery process. 
- Gathering, broadcasting and implementing customer feedback. 

## Futher reading

- [A typology of organizational cultures ](http://qualitysafety.bmj.com/content/13/suppl_2/ii22)
- [Trunk Based Development](https://trunkbaseddevelopment.com/)