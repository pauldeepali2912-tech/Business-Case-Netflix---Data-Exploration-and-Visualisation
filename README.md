# Business-Case-Netflix---Data-Exploration-and-Visualisation
Netflix is a global subscription-based streaming service that provides entertainment, including movies, TV series, documentaries, and games, on internet-connected devices.
As a data analyst I have analyze the Company data. I have provided few insights and recommendations based on my analysis.

💡 What I Did:

🔹 Imported and explored Netflix dataset (8807 records, 12+ features) using Pandas for data analysis.

🔹 Performed data cleaning by handling missing values (director, cast, country, rating) and converting date columns into proper datetime format.

🔹 Created new time-based features like year, month, and week from the date_added column for temporal analysis.

🔹 Segmented data into Movies and TV Shows for separate analysis and comparison.

🔹 Used groupby, aggregation, and sorting techniques to analyze content distribution across countries, time, and categories.

🔹 Applied data transformation techniques like string splitting and exploding to analyze directors and cast frequency.

🔹 Built visualizations using Seaborn and Matplotlib (count plots, line plots) to identify trends and patterns.

🎯 What Has Been Done in This Project:

🔹 Data Collection & Cleaning: Imported Netflix dataset containing 8,800+ titles. Cleaned missing values by replacing nulls with placeholders (e.g., “unknown director”) and standardized date formats for consistency.

🔹 Feature Engineering: Extracted new features such as year, month, and week from the date to enable time-based trend analysis and improve data usability.

🔹 Data Segmentation: Split the dataset into Movies and TV Shows to perform focused analysis on each category independently.

🔹 Exploratory Data Analysis (EDA): Performed country-wise, time-wise, and category-wise analysis using groupby operations to understand content distribution and trends.

🔹 Content Analysis: Identified top countries, directors, and actors by frequency using advanced transformations like exploding multi-value columns (cast, director).

🔹 Trend Analysis: Analyzed yearly growth, monthly patterns, and weekly release trends for both movies and TV shows using line plots and aggregations.

🔹 Visualization: Created insightful visualizations (count plots, line charts) to represent ratings distribution, content trends, and production patterns

💡 Key Takeaways from the Dashboard:

🔹 Netflix content library consists of 8800+ titles, with a higher proportion of movies (~70%) compared to TV shows.

🔹 United States dominates content production, followed by India and the United Kingdom for movies, while Japan and South Korea contribute significantly to TV shows.

🔹 Content release trends show strong growth until 2019–2020, followed by a slight decline in 2021.

🔹 Best release timing insights:

Movies: Highest releases around December
TV Shows: Peak releases around July and specific high-performing weeks

🔹 Top actors like Anupam Kher, Shah Rukh Khan, and others appear frequently in movies, while anime voice actors dominate TV shows.

🔹 Ratings analysis shows TV-MA and TV-14 are the most common, indicating a focus on mature and teen audiences.

🔹 Shorter-duration content is more common, with most movies around 90–105 minutes and TV shows having 1–2 seasons.

🔹 Data quality limitation: A large portion of data had “unknown” values, which may slightly impact accuracy of insights.

Over all the analysis showing, Netflix content grew significantly, peaking in 2019–2020, with the United States leading production. Movies dominate the platform, while TV shows show rising global demand, especially in Asia. Content trends favor mature ratings and shorter durations, with seasonal release patterns observed. Despite missing data, insights reflect strong global expansion and evolving audience preferences.
