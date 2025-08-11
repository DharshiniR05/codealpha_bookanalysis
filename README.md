#📊 CodeAlpha Internship Project
#Internship Domain: Data Analytics
#Tasks Completed:

✅ Task 1: Web Scraping
✅ Task 2: Exploratory Data Analysis (EDA)
✅ Task 3: Data Visualization


#🧩 Task 1: Web Scraping.

#🔍 Objective:
Extract book-related data from an online website (http://books.toscrape.com/) using Python.

#🛠 Tools Used:

Requests: To access web pages

BeautifulSoup: To parse HTML data

Pandas: To store and save data in tabular format

#📝 Steps Followed:

Used requests to access each page (total 70 pages).

Parsed HTML using BeautifulSoup to extract:

Title of the book

Price in GBP

Star rating (as text)

Genre

Stored all records in a list of dictionaries.

Converted the data into a DataFrame using pandas.

Saved the dataset to CSV file: scraped_bookdata.csv

#🎯 Output:
A structured dataset with ~1000 rows and the following columns:

Title

Price (GBP)

Rating (text format)


#📊 Task 2: Exploratory Data Analysis (EDA)
#🔍 Objective:
Understand the structure, pattern, and insights within the scraped data.

#🛠 Tools Used:

pandas: For data exploration

seaborn, matplotlib: For visual inspection

#📝 Key Actions Performed:

Loaded scraped_bookdata.csv

Checked data types and null values

Converted Rating (One, Two...) to numeric values (1, 2...)

Identified:

Most frequent genres

Min, Max, Mean book prices

Most common ratings

Top expensive books

Checked for any anomalies or missing data

#🧠 Key Insights:

Most books were rated between 3 and 4 stars.

Book prices ranged from below £10 to above £50.

Certain genres had higher counts and higher-priced books.

#🎯 Output:
Cleaned and enriched dataset ready for visualization and decision-making.


#📉 Task 3: Data Visualization
#🔍 Objective:
Present insights from the dataset in the form of clear and meaningful visualizations.

#🛠 Tools Used:

seaborn

matplotlib

pandas

#📈 Charts Created:

📊 Bar Plot — Top 10 Book Genres by Count

📉 Histogram — Distribution of Book Prices

🧊 Heatmap — Count of Books per Genre vs Rating

🟦 Countplot — Ratings grouped by Top 5 Genres

💰 Barplot — Top 10 Most Expensive Books by Price

🥧 Pie Chart — Share of Top 7 Genres

#🧠 Key Insights:

Fiction and Children’s books were among the most frequent genres.

Rating distribution showed customer bias toward higher-rated books.

Expensive books were found in genres like Art and Nonfiction.

Genre vs Rating heatmaps showed where high-quality content is concentrated.

#🎯 Output:
A series of colorful and insightful graphs that tell a compelling data story.

🗃 Project Files Structure
File Name	Description

📊task1_scraping.ipynb - Code for scraping book data
📊task2_eda.ipynb	- Exploratory Data Analysis on scraped data
📊task3_visualization.ipynb	- Visual charts and insights from data
scraped_bookdata.csv - Final dataset used across all tasks
README.md	- Project overview and documentation

Genre

