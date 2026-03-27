<h1 align="center">Cyclistic Case Study — BigQuery (SQL) & Tableau</h1>

<p align="center">
Data analysis project exploring bike-share usage patterns using Google BigQuery (SQL) and Tableau to generate business insights and marketing recommendations.
</p>

<p align="center">
This project was completed as part of the Google Data Analytics Professional Certificate (2023).
</p>

<hr>

<h2>Project Overview</h2>

<p>
This project analyzes Cyclistic bike-share data to understand differences between casual riders and annual members. The objective is to identify behavioral patterns and provide data-driven recommendations to support marketing strategies aimed at converting casual riders into members.
</p>

<p>
Data was queried using Google BigQuery (SQL) and visualized in Tableau to analyze user behavior and ride patterns.
</p>

<hr>

<h2>Project Structure</h2>

<pre>
├── Cyclistic_Data_Analysis_SQL_BigQuery.ipynb
└── README.md
</pre>

<hr>

<h2>Data Source</h2>
<ul>
<li>
Cyclistic trip data (Divvy bike-share system, Chicago):
<a href="https://divvy-tripdata.s3.amazonaws.com/index.html">
Divvy Trip Data
</a>
</li>

<li>
Data license:
<a href="https://divvybikes.com/data-license-agreement">
Divvy Data License Agreement
</a>
</li>

<li>
Data was queried using Google BigQuery for large-scale analysis
</li>
</ul>

<hr>

<h2>Project Workflow</h2>

<h3>1. Data Extraction — Google BigQuery (SQL + Python)</h3>

<p>
Trip data was queried using Google BigQuery, a cloud-based data warehouse designed for large-scale data analysis. SQL queries were written and executed through Python using the BigQuery client library, and results were converted into pandas DataFrames.
</p>

<p>
The Jupyter Notebook included in this repository demonstrates how to connect to BigQuery, execute SQL queries, and retrieve results programmatically.
</p>

<p>
<strong>Reproducibility Note:</strong> The dataset is stored in a private Google Cloud project. To run this code, users must:
</p>

<ul>
<li>Create a Google Cloud project</li>
<li>Enable BigQuery</li>
<li>Authenticate using Google Cloud credentials</li>
<li>Update the <code>PROJECT_ID</code> and dataset references in the code</li>
</ul>

<p>
Note: Data extraction from BigQuery requires SQL queries, even when executed through Python.
</p>

<hr>

<h3>2. Data Visualization — Tableau</h3>
<p align="left">
  <a href="https://public.tableau.com/views/Cyclist_Case_Dashboard/Dashboard14?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">
    🔗 View Interactive Tableau Dashboard
  </a>
</p
<p>
The extracted data was used to create visualizations in Tableau. The BigQuery workflow was used to prepare and structure the data, which was then imported into Tableau for analysis.
</p>

<p>
The Tableau dashboard includes:
</p>

<ul>
<li>Number of Trips by Rider Type</li>
<li>Average Ride Length by Rider Type</li>
<li>Average Ride Distance by Rider Type</li>
<li>Map of 200 Most Frequent Routes for Casual Riders (Chicago)</li>
<li>Map of 200 Most Frequent Routes for Member Riders (Chicago)</li>
<li>Number of Trips by Day of the Week</li>
<li>Average Ride Length by Day of the Week</li>
<li>Trip Patterns by Hour of the Day</li>
</ul>

<p align="center">
  <a href="https://public.tableau.com/views/Top200MostFrequentRoutesforCasualRiders/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">
    <img src="https://public.tableau.com/static/images/To/Top200MostFrequentRoutesforCasualRiders/Dashboard1/1.png" width="700">
  </a>
</p>

<p align="center">
  <a href="https://public.tableau.com/views/Cyclist_Case_Dashboard/Dashboard14?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">
    🔗 View Interactive Tableau Dashboard
  </a>
</p>

<p>
Note: GitHub does not support embedded Tableau visualizations. The interactive dashboard can be accessed via the link above.
</p>

<hr>

<h2>Key Insights</h2>

<ul>
<li>Members account for 60% of all trips</li> 
<li>Casual riders tend to take longer rides compared to members</li>
<li>Members show more consistent usage patterns throughout the week</li>
<li>Casual riders are more active and take longer rides on weekends</li>
<li>Member activity peaks during commuting hours, while casual riders show a modest increase in the afternoon</li>
</ul>

<hr>

<h2>Recommendations</h2>

<ul>
<li>Target casual riders with membership incentives during peak leisure periods</li>
<li>Promote membership benefits for frequent riders to encourage conversion</li>
<li>Develop marketing campaigns focused on weekend and recreational users</li>
<li>Leverage behavioral insights to personalize messaging and offers</li>
</ul>

<hr>

<h2>Key Skills Demonstrated</h2>

<ul>
<li>SQL querying in Google BigQuery</li>
<li>Cloud data workflows</li>
<li>Python integration with BigQuery</li>
<li>Data transformation and preparation</li>
<li>Data visualization in Tableau</li>
<li>Business insight generation</li>
</ul>

<hr>

<h2>License</h2>

<p>
This project is licensed under the MIT License.
</p>

<hr>


