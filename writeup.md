Opportunity
Impact
Data science solution path

## Metis Project III: 

LendingClub's business model promotes transparency among those who wish to invest their funds and borrowers in need of liquid funds. This structure means that the former are able to invest in their communities, but charge offs are more noticeable than a bank's shareholders would ordinarily notice. An opportunity exists to analyze data collected in the context of the region where the borrower lives. For example, is the borrower's income significantly more or less than the median recorded for the area? And do LendingClub's historical records support the concept that having an income outside the norm will impact repayment rates? 

The impact hypothesis of this project is: By identifying geographic trends among successful or non-successful debtors, LendingClub can enhance its standing as an independent lending service while ensuring reliable revenue flows.
Future data science steps would include multivariable analysis to create prediction models that could include microeconomic factors or natural disasters focused in certain areas. 

Future applications could include branching out from preventing charged off debt and focusing marketing efforts on communities that disproportionately utilize LendingClub with positive results. For example, in the sample analyzed the Orleans parish of New Orleans took out loans at significantly higher rates than its population would indicate, and showed very high repayment trends. 

### Design

The design of this project was intended to be exploratory and surface level. The charge-off rate was inaccurate for the latest two years of data available, as many of those loans would have still been current and borrowers still could have had time to default. The 2015 range was selected as the year closest to present day while having a majority of completed loans, either fully paid or charged off. 

### Data

1. LendingClub Accepted Loan Data, Q1 2007 to Q2 2018, [Kaggle](https://www.kaggle.com/wordsforthewise/lending-club)
2. Zip Code Characteristics: Median Household Income 2006-2010, [Michigan Population Studies Center](https://www.psc.isr.umich.edu/dis/census/Features/tract2zip/)

### Algorithms

Weighted average calculations were used to find accurate median incomes for three digit zip codes, as opposed to the standard five digit format. Populations were summed to create density estimates among the three-diit zip code regions. 


### Tools
Python was used to create a random sample of 20,000 loans issued in 2015 from LendingClub's accepted loan dataset. 
Google Sheets was used to organize and manipulate the data after download. Tableau Public was used to create visualizations of the data using 

[Google Drive](https://drive.google.com/drive/folders/1HmsVLN5KYqxKIZJHmSEU_p4LV_lUBu3P?usp=sharing)

### Communication

A PowerPoint was created to present on this topic 