---
title: Loan Credit Risk + Default Modeling 
description: Using SQL Server 2016 with R Services, lenders can predict a borrower's credit risk and default probability to help issue fewer unprofitable loans.
author: adamboeglin
ms.date: 10/29/2018
---
# Loan Credit Risk + Default Modeling 
Scoring credit risk is a complex process. Lenders carefully weigh a variety of quantitative indicators to determine the probability of default and approve the best candidates based on the information available to them.
This solution acts as a credit-risk analyzer, helping you score credit risk and manage exposure using advanced analytics models. SQL Server 2016 with R Services equips you with predictive analytics that help assess credit or loan applications and accept only those that fall above certain criteria. For example, you might use the predicted scores to help determine whether to grant a loan, then easily visualize the guidance in a Power BI Dashboard.
Data-driven credit-risk modeling reduces the number of loans offered to borrowers who are likely to default, increasing the profitability of your loan portfolio.

## Architecture
<img src="media/loan-credit-risk-analyzer-and-default-modeling.svg" alt='architecture diagram' />

## Components
* [SQL Server R Services](https://www.microsoft.comhref="http://azure.microsoft.com/sql-server/sql-server-r-services): SQL Server stores the lender and borrower data. R-based analytics provide training and predicted models, as well as predicted results for consumption.
* [Machine Learning Studio](href="http://azure.microsoft.com/services/machine-learning-studio/): Machine Learning helps you easily design, test, operationalize, and manage predictive analytics solutions in the cloud.
* [Power BI](https://powerbi.microsoft.comhttp://azure.microsoft.com/) provides an interactive dashboard with visualization that uses data stored in SQL Server to drive decisions on the predictions.

## Next Steps
* [Get started with SQL Server R Services](https://docs.microsoft.com/sql/advanced-analytics/r/getting-started-with-sql-server-r-services)
* [Learn more about Machine Learning](https://docs.microsoft.com/azure/machine-learning/machine-learning-what-is-machine-learning)
* [Learn more about Power BI](https://powerbi.microsoft.com/documentation/powerbi-service-get-started/)