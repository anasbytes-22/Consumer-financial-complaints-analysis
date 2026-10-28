# Consumer Financial Complaints Analysis

Project Overview

This project analyzes approximately 65,499 historical consumer financial complaints recorded between 2013 and 2015. Using PostgreSQL, SQL, and Power BI, the project explores complaint patterns across financial products, companies, response outcomes, and geographic locations.

The goal is to transform raw complaint data into meaningful insights through data analysis and interactive visualizations.

Objectives

- Analyze complaint volumes across financial products and issues.
- Explore complaint trends over time.
- Compare complaint volumes across financial companies.
- Examine company response outcomes and response timeliness.
- Identify geographic patterns in complaints across states.
- Build an interactive dashboard to communicate findings clearly.

Tools and Technologies

- PostgreSQL: Database storage and data querying.
- SQL: Data exploration, aggregation, and analysis.
- Power BI Desktop: Dashboard development and data visualization.
- GitHub: Project documentation and version control.

Dataset

- Records: Approximately 65,499 complaints.
- Time period: 2013–2015.
- Data domain: Consumer financial complaints.
- Key fields: Complaint ID, date received, financial product, issue, company, state, submission method, company response, and timely response.

The analysis focuses on historical data. The findings should not be interpreted as a description of current complaint patterns.

Dashboard Pages

The Power BI report is organized into four analytical pages:

1. Executive Overview

Provides a high-level summary of complaint volumes and major patterns in the dataset.

2. Product & Issue Analysis

Explores complaints by financial product, issue category, and trends over time.

3. Company Response Analysis

Examines complaint volumes by company, response timeliness, and company response outcomes.

4. Geographic Complaint Analysis

Explores the distribution of complaints across states and identifies geographic patterns.

Analytical Approach

1. Stored and accessed complaint data using PostgreSQL.
2. Connected Power BI Desktop to the PostgreSQL database.
3. Explored complaint counts and categorical distributions.
4. Built visualizations to compare products, companies, responses, and states.
5. Designed a multi-page dashboard using a consistent dark theme with cyan and blue highlights.
6. Reviewed chart titles, aggregations, sorting, and readability to improve the report.

Key Findings

Key findings will be documented after validating the final dashboard visuals and their underlying data. The analysis will distinguish complaint volume from company performance and avoid unsupported conclusions.

How to Use This Project

1. Download "Consumer Financial Complaints Analysis.pbix" from this repository.
2. Open the file using Power BI Desktop.
3. Explore the four report pages and interact with the available visuals.
4. To reproduce the analysis, configure an appropriate PostgreSQL environment and obtain the dataset from its authorized source.

The report may require access to the original database or updates to its data connection before all features can be refreshed.

Limitations

- The dataset covers 2013–2015 and does not represent current complaint activity.
- Complaint counts alone do not measure company quality or customer satisfaction.
- Findings depend on the completeness and accuracy of the source data.
- Comparisons between companies should account for differences in company size and customer base.
