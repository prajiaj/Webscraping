
## Project Overview ##
This project focuses on web scraping, data cleaning, and interactive visualization of the Fortune India Companies (2024) companies' financial data. The main objective was to extract structured information from the official website, clean and refine the dataset, and create insightful business dashboards using Power BI.

## Technologies Used
  - Python (Jupyter Notebook)
  - BeautifulSoup (Web Scraping)
  - Requests (HTTP Requests)
  - Pandas (Data Analysis)
  - Power BI (Data Visualization, Data Cleaning, Data Modeling)

## Project Workflow ##
**1️⃣ Importing Libraries**
Used BeautifulSoup, Requests, and Pandas for web scraping and data handling.

<img width="1490" height="537" alt="Importing Libraries" src="https://github.com/user-attachments/assets/d184398c-dfab-4fa9-97bd-f79dacabc308" />


<br>
<br>
<br>

**2️⃣ Extracting Data from Website**
Scraped company financials from Fortune India Comapnies - 2024 using HTML parsing.
Retrieved key financial metrics like Revenue, Profit, ROCE, RONW, TSR%, Employees, Debt, and Assets.

<img width="1490" height="560" alt="Extract and clean table headers" src="https://github.com/user-attachments/assets/9b40b374-9e83-4230-8281-730ddfed5e11" />

<br>
<br>
<br>

**3️⃣ Building and Cleaning Data**
Removed unwanted HTML tags and formatted extracted tables into a clean DataFrame.
Cleaned headers, removed redundant columns, and converted numeric text columns for analysis.

<img width="1491" height="691" alt="Building dt from cleaned table rows" src="https://github.com/user-attachments/assets/1724f595-d437-420b-b115-04f8c2cde274" />

<img width="1492" height="670" alt="Renaing and refining table columns" src="https://github.com/user-attachments/assets/66fde6a0-3e22-4ed2-898d-5b609fec434c" />

<br>
<br>
<br>

**4️⃣ Data Export**
Saved the cleaned dataset as CSV for further analysis in Power BI.

<img width="1495" height="521" alt="converting data into csv file" src="https://github.com/user-attachments/assets/35fe190b-72d0-490e-986c-761a70ae3f3d" />

<br>
<br>
<br>

**5️⃣ Data Visualization in Power BI**
Created business dashboards with slicers, KPIs, charts, and treemaps.

Linked with a secondary table containing sector classifications (15+ sectors).

Used measures like Total Income, Net Profit, Assets, TSR%, and ROCE% for insights.

<img width="1330" height="785" alt="Report page" src="https://github.com/user-attachments/assets/35e0f92c-3efb-4850-b7e8-835a4b8b1d85" />

<img width="1332" height="768" alt="Overview page" src="https://github.com/user-attachments/assets/04c2873a-0bfb-49e5-8c6b-6b3b318c464d" />

<br>
<br>
<br>

**Key Dashboard Features**

**Page	Features**
**Report Page:** Bar Charts, Pie Charts, Donuts, KPIs for Total Income, Profit, ROCE, TSR
**Overview Page:** Treemaps by Sector, Sector-wise Income, Profit, Debt, Cash Balance, Market Cap Analysis



**Objective**
To provide actionable insights into the financial performance of India’s top companies, segmented by industry, while demonstrating a complete data pipeline — from extraction to visualization.

