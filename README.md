<iframe width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiNzk3YmU4ZDAtNjJkYS00YTY0LWJiYWQtMWVlOTUyOTNjNDY4IiwidCI6ImFmODk4MTBhLTdkNWUtNGRjYS05MThiLTMyY2NlYmUzMTdlMSJ9&pageName=ReportSection" frameborder="0" allowFullScreen="true"></iframe>
<p align="center">
  <img width="700" src="https://app.powerbi.com/view?r=eyJrIjoiNzk3YmU4ZDAtNjJkYS00YTY0LWJiYWQtMWVlOTUyOTNjNDY4IiwidCI6ImFmODk4MTBhLTdkNWUtNGRjYS05MThiLTMyY2NlYmUzMTdlMSJ9&pageName=ReportSection">
</p>

# QuickJab - Data Analysis

This is a data analysis community driven project, where one member posed as fictitious client (QuickJab), who contracted a data analytics consulting firm (T7 - Consulting) to investigate their future plans. The mock client QuickJab rolls out vaccinations and was asking for a data driven decision to the following question: <i>In which country should QuickJab distribute a vaccination next?</i> In this project a team of 3 members tried to solve the problem using a dataset provided by the client, which included data about covid19 vaccinations in 126 countries. In the end, the team had to present their findings in a 15 minute presentation to the client. 


The following jupyter notebook includes my data exploration and cleaning
nbviewer.com


<i>Quick summary of our thoughts and decisions:</i>

Based on the provided and external data we came up with 3 metrics to rank the countries and investigate which one could be a potential target. Those 3 metrics were a population score, a global health security index and an efficiency score. The population score is calculated by taking the arithmetic mean of a median age score and a population score, benchmarked at a population of 10 million. The global health security index is a comprehensive assessment and benchmarking of health security and related capabilites by the JHU. Further, the efficiency score describes how well a country will distribute the provided vaccinations. 

<p align="center">
  <img width="700" src="https://github.com/CMWVD/testrep/blob/main/scoring.png">
</p>


After scoring the countries based on the 3 metrics, the best performing country was Sweden. 
To further back up this decision with client data, we then looked at the number of vaccinations per hundred inhabitants per country after 30 days of their initial vaccination programm start. We were looking for a country with a lower number of vaccinations/hundred, to increase the impact of future vaccinations. Again Sweden took a place at the top of the new benchmark, thus we decided to propose Sweden as the next target for their vaccinations rollout. 


<p align="center">
  <img width="700" src="https://github.com/CMWVD/testrep/blob/main/recommendation.png">
</p>
