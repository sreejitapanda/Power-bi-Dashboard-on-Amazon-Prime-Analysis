**Amazon Prime TV Shows & Movies Analysis Dashboard**
---
 Project Overview
---
This project is an interactive Power BI dashboard designed to analyze the Amazon Prime content library, including movies and TV shows. The dashboard provides a clear view of the size, quality, release trends, audience certifications, content types, and cast/role distribution within the dataset.
The main goal is to transform the raw Amazon Prime dataset into an easy-to-understand visual dashboard that helps users explore content patterns and identify useful insights.
-----
## Objectives
------
* The dashboard was created to:

1.Understand the overall size of the Amazon Prime content catalog.
2.Compare movies and TV shows.
3.Identify highly rated titles based on IMDb score.
4.Analyze how the number of released titles has changed over the years.
5.Study the distribution of age certifications.
6.Compare the average IMDb scores of movies and shows.
7.Compare the average runtime of movies and shows.
8.Analyze the distribution of roles such as actors and directors.
9.Allow users to interactively filter the dashboard by content type, genre, and production country.
---
## Key Performance Indicators

The dashboard provides high-level summary cards for important metrics:
1.Total Titles
The dashboard contains 8,721 titles in the analyzed dataset.
2.Total Cast Members
The dashboard shows approximately 80.44K cast/people records associated with the content.
3.These KPI cards provide an immediate overview of the size of the content catalog and its associated cast information
---
## Dashboard Visualizations
---
* 1. Top 5 Titles by IMDb Score
A horizontal bar chart displays the top five titles based on IMDb score.
This visual helps identify the highest-rated content in the dataset and makes it easy to compare ratings between the leading titles.
The chart is interactive and can change based on applied dashboard filters.

* 2. Titles Released per Year
A time-series chart shows the number of titles released across different years.
The visual separates:Movies,Shows
It helps to identify changes in content production over time and highlights periods where the number of releases increased significantly.

* 3. Count of Roles – Actor vs Director
A donut chart presents the distribution of recorded roles.
The dashboard compares:Actor,Director
It shows overview of how the people associated with the content are distributed across major role categories.

* 4. Distribution of Age Certifications
A funnel-style/bar visualization shows the distribution of content across different age certifications.
Examples of certifications visible in the dashboard include: R,PG-13,PG,G etc.
This helps understand the audience categories targeted by the available content.

* 5. Average IMDb Score – Movies vs Shows
A column chart compares the average IMDb score between movies and shows.
This visual provides a quick way to understand how the two content types perform in terms of average viewer ratings.

* 6. Average Runtime – Movies vs Shows
A column chart compares the average runtime of movies and TV shows.
This helps identify differences in typical content length between the two formats.

* 7. Content Type Distribution
A chart is included to show the overall distribution of content types in the dataset.
The main categories are: Movies,Shows
This allows users to understand the composition of the Amazon Prime catalog.

* 8.Interactive Filters
The dashboard includes interactive slicers that allow users to explore the data dynamically.

* 9.Content Type
Users can filter the dashboard by: Movie,Show,Genre
---
## Key Insights
* Based on the dashboard:
1.The analyzed catalog contains 8,721 titles.
2.The dataset contains approximately 80.44K cast/people records.
3.The highest-rated titles can be quickly identified using the Top 5 IMDb Score visual.
4.Release activity varies considerably across years, with a noticeable increase in more recent periods.
5.Movies and shows can be compared directly using average IMDb score and average runtime.
6.Age certification analysis shows that content is distributed across a wide range of audience categories.
7.The role distribution is dominated by actor records compared with director records.
8.Interactive filters make it possible to analyze these patterns for particular content types, genres, and production countries.
---
## Tools & Technologies
1.Microsoft Power BI – Dashboard development and visualization
2.Power Query – Data preparation and transformation
3.DAX – Measures and calculations
4.Amazon Prime Movies & TV Shows Dataset – Source data
--
## Dashboard Design
The dashboard uses:
1.KPI cards for summary metrics
2.Bar charts for title rankings
3.Line charts for release trends
4.Donut charts for role/content distributions
5.Column charts for movie/show comparisons
6.Interactive slicers for filtering
7.A consistent dashboard layout for easy navigation and comparison
---
## Dataset Fields Used
* The dashboard works with fields such as:
.id
.title
.type
.release_year
.genres
.production_countries
.age_certification
.runtime
.imdb_score
.imdb_votes
.person_id
.role
.character
.name
---
## How to Use the Dashboard
1.Open the Power BI report.
2.Use the Movie/Show filter to select the required content type.
3.Select a genre to focus the analysis.
4.Select a production country to analyze regional content.
5.Hover over charts to view detailed values.
6.Compare IMDb scores, runtime, release trends, certifications, and role distributions.
7.Clear the filters to return to the complete dataset view.
---
## Conclusion

The Amazon Prime TV Shows & Movies Analysis Dashboard converts a large content dataset into an interactive visual analytics solution. It provides a quick overview of the catalog while also allowing deeper exploration through filters and comparative visualizations.
The dashboard can be useful for understanding content trends, audience certifications, ratings, runtime, content type distribution, and people/role information within the Amazon Prime dataset.

