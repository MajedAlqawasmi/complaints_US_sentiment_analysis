# Financial Product Complaint Handling Optimization
by [Majed Alqawasmi](https://github.com/MajedAlqawasmi) July 2021
<br/><br/>
##  Insights for financial supervisory authorities, consumer & banks 
![Consumer Complaints](Customer-Complaints.jpg)

## Table of content

- [Project Description](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/README.md#project-description)
- [Data](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/README.md#data)
- [Process & Tools](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/README.md#process--tools)
- [Key Take Aways & Final Product](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/README.md#key-take-aways)

## Project Description
This project shall aim to both, highlight important findings, and provided Data analysis with a comprehensive dashboard on consumer complaint about banking products in the U.S from 2013 to 2019. It aims to raise consumer awareness, helps the regulator in decision making and prompts financial institutions to optimize their both their complaint handling process as well as their products. 

## Data
Four datasets: 
- [Consumer Complaints database from Consumer Financial Protection Bureau, USA](https://www.consumerfinance.gov/data-research/consumer-complaints/) 
- [Consumer Complaints database from data.world](https://data.world/cfpb/consumer-complaints/workspace/file?filename=complaint_data.csv)
- [U.S bank rank according to total assets](https://www.usbanklocations.com/bank-rank/total-assets.html?d=2021-03-31)
- [U.S Zipcode database](https://simplemaps.com/data/us-zips)

## Process & Tools

**Process**
My ways of working included an iterative/agile approach circling through the following steps:

- **Github:** set up our Github repo to collaborate on or to simply use for this project. <br/>
- **Project management:** [Trello](https://trello.com/b/UOn2CIdn/ironhack-final-project)
- **WorldWideWeb:** find datasets<br/>
- **Coding:** [Jupyter notebook](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/final_project.ipynb)
- **EDA:** assessment of dataframe to prepare for cleaning<br/>
- **Data cleaning & wrangling in Python:** using Pandas / numpy to drop columns, join tables, drop null values, convert some uppercase to lower<br/>
- **Web Scraping:** using BeautifulSoup<br/>
- **Text Analysis:** NLP using TextBlob to achieve a Sentiment score for each customer narrative<br/>
- **Querying:** using MySQL & Tableau<br/>
- **Answering question & Visualization:** using [Tableau](https://public.tableau.com/views/final_project_ironhack/GeneralComplaintsDashboards?:language=en-US&:display_count=n&:origin=viz_share_link)<br/>
- **Finalizing a full dashboard:** using [Tableau](https://public.tableau.com/views/final_project_ironhack/GeneralComplaintsDashboards?:language=en-US&:display_count=n&:origin=viz_share_link)<br/>
- **Presentation:** [google slides](https://docs.google.com/presentation/d/1rhUcAz9iLyuiL-HABICM4ZkHcmgFSo7NMqwrWDgCZaU/edit?usp=sharing)

## Key Take Aways & Final Product

- **Complaints trend over the years:** ![Trend](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/complaints_over_years.PNG) Trend is pointing upward therefore some action might be needed
- **Top 5 products in terms of numbers of complaints:** ![Top 5 products](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/top5product20banks.PNG) Number of complaints for each product is proportionate to companies' sizes
- **Top Companies Compaints Wise & Their Bank Rank (Assets):** ![Top Companies Compaints Wise](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/top_bank_compliants-wise.PNG) Some organisations that might need some scrutiny
- **Consumer's sentiment:** ![Consumer's sentiment](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/consumer_sentiment.PNG) American consumer seems to have mainatained acceptable sentiment score over the years therefore objectivity and lack of polarity are to be generally assumed in all complaints
- **Map & Cultural Considerations:** ![Cultural Considerations](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/sentiment_map.PNG) Extra training may be provided to employees in the orange-colored states
- **Products Susceptible to Fraud:** ![Fraud](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/products_susceptible_fraud.PNG) From 2013 to 2019, we see a sharp increase in cryptocurrency related activity comparing to previous years. This can be of interest to Federal AML regulatory body
- **Sentiment VS number of complaints:** ![scatter plot](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/Sentiment%20vs%20%23%20of%20complaints%20per%20state.PNG) The scatter plot proves no correlation between customer sentiment and the number of complaints in all the states therefore confirming the sentiment analysis can be used only for cultural training

For many more insight, please do check out these dashboards:
- [General Complaints Dashboard](https://public.tableau.com/views/final_project_ironhack/GeneralComplaintsDashboards?:language=en-US&:display_count=n&:origin=viz_share_link)<br/>
- [Products, Demographics & Compliants Dashboard](https://public.tableau.com/views/final_project_ironhack/ProductsDemographicsCompliantsDashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)<br/>
