# Netflix
Netflix Content Analysis Dashboard
📊 Project Overview
This project is an interactive Netflix Content Analysis Dashboard developed using Microsoft Power BI.
The dashboard provides a visual analysis of Netflix titles, focusing on content volume, release years, ratings, content type, geographic distribution, and directors. It is designed to help users quickly understand the composition and historical growth of Netflix's movie and TV-show catalog.
🎯 Objectives
Analyze the overall number of Netflix titles and shows.
Compare Movies vs TV Shows.
Identify the start and end release years represented in the data.
Analyze the distribution of titles by rating.
Identify the top countries producing Netflix content.
Examine how the number of Movies and TV Shows changes by release year.
Identify directors associated with a high number of titles.
🛠️ Tools & Technologies
Microsoft Power BI
Power BI Data Model
Power BI Visualizations
Interactive dashboard design
Aggregation and categorical analysis
📌 Dashboard Contents
The current Power BI report contains a dashboard page named Page 2 with the following components:
KPI Cards
Total Titles – overall count of titles.
Total Shows – count based on the `show_id` field.
Start Year – minimum release year.
End Year – maximum release year.
Total Rating – count of records with a rating.
Visualizations
Visualization	Purpose
Treemap – Top 10 Countries by TV Shows and Movies	Shows the geographic distribution of Netflix content and highlights the leading countries.
Donut Chart – Total Movies and TV Shows	Compares the two major content types.
Area Chart – TV/Movies Count Per Year	Shows how Movies and TV Shows are distributed across release years.
Clustered Bar Chart – Ratings	Compares the number of titles across rating categories.
Clustered Column Chart – Directors	Shows title counts by director.
🗂️ Data Fields Used
The Power BI report references fields including:
`show_id`
`type`
`title`
`director`
`country`
`release_year`
`rating`
These fields are used directly in the dashboard's KPI cards and visualizations.
📈 Key Analytical Areas
1. Content Type Analysis
The dashboard separates Netflix content into:
Movies
TV Shows
This makes it possible to compare the relative contribution of each content type.
2. Geographic Analysis
The country treemap highlights the countries associated with the largest number of Netflix titles, providing a quick view of the geographic concentration of the catalog.
3. Release-Year Analysis
The yearly area chart allows users to observe changes in the number of Movies and TV Shows across release years.
4. Rating Analysis
The ratings visualization provides a comparison of the number of titles across different content-rating categories.
5. Director Analysis
The director chart highlights directors associated with larger numbers of titles in the dataset.
📁 Repository Structure
```text
Netflix-PowerBI-Analysis/
│
├── Netflix.pbix
├── README.md
└── .gitignore
```
🚀 How to Use
Download or clone this repository.
Open `Netflix.pbix` using Microsoft Power BI Desktop.
Interact with the dashboard visuals to explore the Netflix catalog.
Use Power BI's filtering, highlighting, and cross-interaction features where available.
> **Note:** The `.pbix` file is the main deliverable of this project. Power BI Desktop is required to open and edit it.
💡 Project Highlights
Designed an interactive Power BI dashboard.
Used KPI cards for high-level metrics.
Applied multiple visual types for categorical, geographic, and time-based analysis.
Compared Movies and TV Shows using a dedicated composition visual.
Analyzed country, rating, release-year, and director dimensions.
Structured the report as a portfolio-ready business intelligence project.
📷 Dashboard Preview
Add a screenshot of the Power BI dashboard here after publishing the repository:
```text
docs/netflix-dashboard.png
```
Then replace this section with:
```markdown
![Netflix Dashboard](docs/netflix-dashboard.png)
```
🔮 Possible Future Enhancements
Add slicers for content type, country, rating, and release year.
Add a dedicated genre/category analysis.
Add duration analysis for Movies and TV Shows.
Add trend KPIs and year-over-year comparisons.
Add drill-through pages for country, director, and title-level analysis.
Add a dedicated dashboard page for detailed title exploration.
Publish the dashboard to Power BI Service and embed a secure report link where appropriate.
👩‍💻 Author
Shyamily Kuriakose
Data Analyst | Digital Analyst | Power BI | Python | SQL
⭐ Portfolio Note
This project demonstrates practical skills in:
Data Analysis → Data Modeling → KPI Design → Data Visualization → Dashboard Development → Business Insights
If you find this project useful, consider giving the repository a ⭐ on GitHub.
