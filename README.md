# Profit-Analysis-DB-Excel

## Problem Statement
This dynamic and highly intuitive DAX-based eCommerce dashboard offers a real-time snapshot of the financial position of a business and facilitates future planning by highlighting metrics that directly impact the business's bottom line.

When used as part of good business practices in a Financial Planning & Analysis (FP&A) department, financial dashboards improve its executives’ ability to always keep an eye on the essential KPIs, as well as, reduce the chances that important decisions are delayed because executives don’t have easy, self-service insight to performance.

## Dataset Used
- The dataset utilized in this dashboard has its origins in the Sales data folder, and it contains data from 2019 to 2021.
- The data in this folder is termed the Fact Table; a table that contains transaction details such as purchases, quantities, order dates, and certain crucial IDs that will link the Dim (Dimension) Tables.
- Five or six Dim Tables utilize Power Pivot to manage and construct associations, allowing us to generate our analysis with a free flow of data.

## Analyses derived from the dataset
- An appraisal of the cumulative profit from the start of the transactional year in 2019 to the end of the transactional year in 2021.

<p align="center"><img width="234" alt="image" src="https://user-images.githubusercontent.com/71536311/194792887-72820639-3f5c-496c-b8a6-395df1c60746.png">
</p>

- Discovery of who is aiding our company's growth by identifying the top three most lucrative customers inside our organization.

<p align="center"><img width="215" alt="image" src="https://user-images.githubusercontent.com/71536311/194795161-48a512ba-deb6-4a06-8d60-1b1376891c42.png"></p>   
 
 - An analysis of the top three unremunerative clients inside our business can assist us in determining why and what we need to do to entice them to purchase more from us in the future.
 
<p align="center"><img width="214" alt="image" src="https://user-images.githubusercontent.com/71536311/194795113-4b9cc66b-eede-4e3e-9810-2041cba47316.png"></p>  
 
 - Profit trends for the firm on an annual, monthly, and quarterly basis.
 
<p align="center"><img width="200" alt="image" src="https://user-images.githubusercontent.com/71536311/194795513-2341e081-c665-407a-ac35-681697393242.png"></p>
<p align="center"><img width="446" alt="image" src="https://user-images.githubusercontent.com/71536311/194795943-fd7393b5-1a86-433d-b5e6-3ea09bc1db3b.png"></p>
<p align="center"><img width="446" alt="image" src="https://user-images.githubusercontent.com/71536311/194795986-1eef4787-767f-43db-bd35-0ceb3c864442.png"></p>

- Easy-to-read cards for smart and rapid decision-making, visualize critical KPIs such as the number of transactions, total customers, current items, COGS, revenue, profit, quantity sold and regions the company sells to.

<p align="center"><img width="760" alt="image" src="https://user-images.githubusercontent.com/71536311/194795805-457e140d-3f10-4d8e-a326-910804e73bc0.png"></p>
<p align="center"><img width="760" alt="image" src="https://user-images.githubusercontent.com/71536311/194879316-d6ca0bfd-35b8-4357-9bf8-8efc765e97cc.png"></p>


### Active filters needed to interact with the data and the dashboard 
Country, products, and months

<p align="center"><img width="130" alt="image" src="https://user-images.githubusercontent.com/71536311/194792337-e51e0748-9cb3-47ad-b054-4b3ae6589d29.png"></p>
</br><p align="center"><img width="133.5" alt="image" src="https://user-images.githubusercontent.com/71536311/194792373-ca50668c-6270-40d6-a475-b0c2fe703dca.png"></p>
</br><p align="center"><img width="700" alt="image" src="https://user-images.githubusercontent.com/71536311/194792391-4589de39-4cb2-4358-97f8-7f69b94c95ac.png"></p>

## Tools Used
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

- Utilized Power Query to extract and transform the data, then transferred the data to Power Pivot for further analysis.
- Power Pivot is used to store our data for further exploration in the future, if the number of rows increases into the millions.
- Implemented OFFSET and COUNTA functions to prepare reports that interpret transaction, order, COGS, revenue, and net profit on a monthly and quarterly basis, by sales channel, by sales regions and by item types sold over time.

## Overview

<p align="center"><img width="950" alt="image" src="https://user-images.githubusercontent.com/71536311/194843769-c0f97704-4bd3-46a6-a5ef-20dff877fd62.png"></p>

![db](https://user-images.githubusercontent.com/71536311/194878977-c8320e43-6305-41b3-87fa-f540ebcf241c.gif)


