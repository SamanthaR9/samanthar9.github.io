# :wave: Hi, I’m Samantha

I’m learning data analytics and building projects in Python, SQL, and visualisation tools to develop practical, job-ready skills. My background is in Literature and Cinema, combining storytelling with data to turn insights into meaningful narratives. The following projects were completed during a Data Analysis short course which lasted around 7 weeks. 

## 👉 Skills Summary
- Python (pandas, data cleaning, EDA)
- SQL (joins, aggregation, subqueries)
- Excel (pivot tables, charts)
- Tableau (dashboards, storytelling)
- Power BI (DAX, reporting)


# :file_folder: Projects
## :bar_chart: Excel and data basics
![Pivot Table and Visualisation Chart 1](Bike-Sales-Excel5.png)
<br> ![Visualisation Chart 2](Bike-Sales-Excel4.png)
<br>With the given dataset which shows KPIs from bike sales, my analysis through pivot tables and stacked bar charts shows where the company should focus sale efforts. The results show that the most profitable market is Australia, with a total of 63 sales, and that there are consistent sales within each age group and gender. Across all countries and age groups, female customers purchase more than male customers. The youth age category (under 25) have the least amount of sales. 

## :snake: Python / Google Colab 
Full notebook (including code, cleaning steps, and visualisations): [link](student.ipynb)<br>
This project demonstrates my use of Python for data analysis within a Jupyter Notebook environment (Google Colab). I worked with datasets to clean, explore, and analyse data, applying core data analysis techniques in Python. For this project, I loaded a dataset with student information to explore and understand the structure, cleaned missing or inconsistent data, and extracted meaningful insights through the visualisations. By grouping and filtering the data, I was able to add a column for 'Grades' and analyse even further. <br>
The Pie Chart, Histogram and Bar Charts show that Grade A is the most frequent grade overall, with most classes scoring on average between 70 and 80. Class Nine is an outlier, with a lower average of around 40. This significant performance gap requires attention, and if this were used in a school then it would indicate the need for different teaching methods, or extra resources.

## :card_file_box: SQL / MySQL Workbench 
My objective was to analyse a relational dataset to extract insights about countries, cities, and population trends using structured queries. I approached this by querying the MySQL World dataset using joins to combine tables, aggregations (such as COUNT and AVG), subqueries for deeper analysis, and filtering and grouping.<br>
<br>
**Example Query:**
<br>Identify countries with the highest average city population to compare urban density across regions and population distribution patterns across cities and countries.

```sql
SELECT
  country.Name AS country_name,
  AVG(city.Population) AS average_city_population
FROM city
JOIN country
  ON city.CountryCode = country.Code
GROUP BY country.Name
ORDER BY average_city_population DESC;
```


**Key Insights:**
- Countries like Singapore and Hong Kong have the highest average due to highly concentrated urban populations.
- Larger countries show lower averages due to a wider distribution of smaller cities.
- This is important to note as it highlights how averages are influenced by the number of cities and population distribution, rather than size or wealth.
- High urban concentration may refelct economic centralisation, where population and resources are clustered into a few major cities, which can distort comparisons and relationships between countries if not addressed. 
<br>[View my full SQL script here](queries.sql)
<br>

**Database Schema ERD Diagram**
<br> ![ERD Diagram](Country-ERD.png)
<br> This diagram shows the relationships between the tables in the MySQL World dataset, including country, city, and countrylanguage. The ERD helped me understand how tables are connected through primary and foreign keys, which allowed me to write more accurate JOIN queries and analyse relational data effectively.

## :bar_chart: Tableau
![Tableau Dashboard](GapMinder-Tableau.png)
<br>The GapMinder dataset contains health statistics from around the world. I was tasked with analysing trends and key information that an organisation would find useful, such as being able to quickly understand health trends and disparities across different countries and continents, visualising how health metrics vary, and how life expectancy has changed over time.
<br><br>![Population Growth by Continent Over Time](GapMinder-Prompt-Deliverable.png)
<br>This is an example of a single optional worksheet, but one I found especially important as the data gives insight into how organisations may need to implement planning in the future based on trends. 

## :chart_with_upwards_trend: Power BI
This project demonstrates a full Power BI workflow completed through Skillable labs. The aim was to develop practical skills in data preparation, modelling, visualisation, and dashboard design using Power BI Desktop.
<br><br>![Getting Data](PowerBI-Getting-Data.png)<br>In this lab I imported data from an SQL database (AdventureWorks) and added the raw data into Power Query. I reviewed the initial structure and fields before moving to the next step.
<br><br>![Load and Transform Data](PowerBI-Transforming-Data.png)<br>This lab focused on cleaning and preparing the dataset using PowerQuery, ready for reporting and analysis. Data types were corrected, column headers were standardised, and data quality was validated using built-in profiling tools to ensure accuracy before analysis.
<br><br>![Design a Report](PowerBI-Design-Report.png)<br>In this lab I focused on creating visual reports, resulting in an interactive dashboard that presents data clearly. For this task I focused on finding the running total (DAX), showed multiple measures on one chart, and conducted time-based analysis.
<br><br>![Create a Power BI Dashboard](PowerBI-Dashboard.png)<br>This lab involved assembling visuals into a final cohesive dashboard, providing a high level report and summary of insights. Used a combination of visuals such as combo charts, stacked bar charts, and horizontal bar charts alongside slicers to give a well-rounded analysis.

## :handshake: Contact
- 📧 Email: samanthaross1@hotmail.co.uk
- 🔗 LinkedIn: [View my profile](https://www.linkedin.com/in/samantha-ross/)
