+++
author = "Cliff Chew Kuo Ting"
title = "Perspectives on Data Requests"
date = "2020-06-26"
description = "The love-hate relationship data analysts have with data requests"
tags = ["startup", "data science"]
+++

## Working with stakeholders
We commonly hear that data science is a team sport, but yet, I feel there is so little discussion on the nuances of how data analysts can better work with their stakeholders. While I don’t have clear answers for this topic, I want to share some experiences and perspectives as a data analyst, and hopefully invoke some discussions on the topic of working with stakeholders. I hope that this can also give aspiring data analysts a peek into this industry beyond the normal discussions on coding and statistics. **In this post, I will focus on the core job of a data analyst: data requests.**

## Data Requests
One thing about working with others is the importance of communications. Hence, when I get a data request, I will always try to understand these three things from my stakeholders: (1) how urgent is the request, (2) its purpose and (3) is this a one-time request or something that requires updating.

### Urgency
**I hope more stakeholders can appreciate that quality data queries require time, effort and a clear-mind.** When fulfilling data requests, data analysts need to perform an array of tasks, from checking data availability and in which table they reside in, the definitions of the data, to executing certain data operations like rolling window functions to get the top n-th result for each identified group. 

If I have a choice, I will always rather be slower but accurate, than fast but reckless. Data analysts are humans too, and a culture of frequent urgent data requests increases the odds of extracting erroneous data that business decisions are then based upon. Data analysts are key data assets of the company, and they must play the role of protecting the data quality and integrity of their work. In addition, I believe data analysts (I do at least) do get satisfaction from knowing that they are producing quality work and not having to hastily rush through a query that they are not confident of. 

Hence, while SQL is a prerequisite skill for any data analyst to perform data queries, data analysts must also strive to be data stewards of their company, by building a culture where everyone understands the effort required for data queries. **Data analysts need to be willing to push back on a culture of unreasonable urgent data requests**, so that the risk of hasty data requests leading to erroneous decisions is borne by the whole team.

I have heard and experienced firsthand toxic working environments where urgent data requests are commonplace. While the data analysts may try to accommodate such a culture, stakeholders may end up taking the efforts of the data analysts for granted, and feel that their urgent requests are normal. In the end, many data analysts end up feeling stressed and burned out, their overall quality of work may suffer, and some end up just leaving the company. In general, I would also be wary of the data quality and integrity in such organizations, and the decisions that are made from those data points.

### Purpose
Naturally, there will be requests where speed is more important than accuracy, and this depends on the purpose of the request. For example, stakeholders may just need a rough number to evaluate whether this problem requires a deeper analysis. In other instances, what the stakeholder needs could be answered by a past query instead. Clarifying such matters early can help prevent unnecessary work upfront. In addition, data analysts should also clarify any unclear definitions or nuances from the data request. It is common for different functions in a company to use the same terms differently, such as what defines a new, active or churn user. Ensuring that the team (data analysts and their stakeholders) are on the same page and asking the correct questions collectively will definitely help sharpen your analysis. 

Unfortunately for me, as my portfolio grew to support more stakeholders, such mis-communications have caused me a lot of wasted queries, unnecessary headaches and botched analyses. Definitely some painful personal lessons for me here as a data analyst.

### Frequency
Lastly, whether the data needs updating or not will affect how the data can be served to the stakeholders. For one-time data requests, one can always try to be fast and do a quick query. I myself do this often as well, as we always don’t have enough time. However, keeping track of all data requests properly can make it easier for the data analyst to reproduce his work in the future. There will always be a chance that the stakeholders will want to revisit this data with updated parameters. In addition, recording past queries can allow the data analyst to build up his data knowledge within the company, and allow him to cross reference his work with other colleagues for mutual learning. This can help reduce the efforts of reinventing the wheel, and can help improve the consistency of data queries across the company.

### Dashboards
A variant of data request is the request for dashboards to monitor metrics. Dashboards have built in mechanisms to update the data, and hence will relieve the data analyst effort to constantly update the data by themselves. However, dashboards also take more time and effort to build. **Hence, always confirm the rationale behind the dashboard request if it is unclear**. In particular, if stakeholders need to first explore the data, providing an exploratory analysis without a dashboard may be a leaner option. The data analyst can most likely provide the necessary data more quickly without the efforts of loading it into a dashboard, which allows the stakeholders faster access to the data, and generally allow quicker iterations and exploration work on the data. When the metrics is finalized, the data analyst can then create a dashboard with it.

## Conclusion
This has been one of the hardest posts to write and structure so far, because I feel there is so much I want to write about this. It feels weird to be writing about this to be honest, because I definitely don’t feel I am qualified to teach anyone about working with stakeholders, as I myself struggle in this aspect at times. However, I feel that this topic is so important and yet so under addressed that I want to write a post about it.

***Lastly, I hope that this post can help teams bridge the gaps in their views on data, or spark conversations about data between teams. So feel free to share this with anyone whom you think can benefit from this, or suggest topics relating to data that may interest you!***