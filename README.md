# Job Market Intelligence Tracker (2026)

Author: Mukhtar Dualeh

Live Dashboard: [View Interactive Report](https://mukhtardualeh.github.io/job-market-intelligence-2026/)

## Project Overview
An automated data pipeline that tracks the "Data Analyst" job market in real-time. This project fetches live job postings via the Adzuna API, processes the data using Python/Pandas, and extracts key insights about salaries and in-demand skills.

Instead of a static report, this project generates a Live HTML Dashboard allowing stakeholders to explore salary distributions and skill requirements interactively.

## Key Findings (February 2026)
* Top Skill: SQL is the primary technical requirement, appearing in approximately 4.4% of all analyzed listings.
* Emerging Technologies: Azure and Power BI show significant demand in enterprise-level roles.
* Salary Insights: Preliminary data suggests high variability in compensation based on geographic location.

## Technical Architecture
* Data Collection: Python requests library interacting with the Adzuna API.
* Data Processing: Pandas for data cleaning, outlier detection, and categorization.
* Visualization: Plotly for interactive charts embedded in a custom HTML template.
* Environment: Google Colab (Cloud-based execution).

## Data Analysis & Limitations
During the analysis of "Highest Paying Cities," the data indicated that smaller municipalities (e.g., Portola Valley) ranked highest with salaries exceeding $200k.

Note on Statistical Outliers:
Upon deeper inspection, these averages were frequently based on a single job posting (job_count = 1). This indicates the data is skewed by individual high-paying outliers (likely Senior/Executive roles) rather than representing the true average market rate for that location.

## Installation & Usage
To reproduce this analysis:

1. Clone the repository.
2. Install dependencies:
   pip install pandas requests plotly python-dotenv
3. Obtain an API Key from the Adzuna Developer Portal.
4. Run the Jupyter Notebook `Job_Market_Intelligence.ipynb`.

## Contact
For questions or feedback regarding this project, please contact:
* mukhtardualeh1@gmail.com
