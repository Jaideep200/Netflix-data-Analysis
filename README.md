# Netflix-data-Analysis
Netflix Data Analysis using Python

This project performs a detailed Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset, revealing key business insights, content strategies, and production trends using Python.

🧠 Project Objective

To analyze Netflix’s catalog of content to answer strategic questions like:

What is the ratio of Movies vs TV Shows on Netflix?

Which genres and countries dominate the content library?

What are the most common ratings and release trends?

Which directors and actors appear most frequently?

How has Netflix’s focus shifted over the years?

🧰 Tools & Libraries Used

Python 3

pandas – Data loading and cleaning

numpy – Numerical computation

matplotlib – Data visualization

seaborn – Advanced visualizations

Google Colab – Environment for execution

📂 Dataset Information

File: netflix.csv
Total Records: 8807
Columns:

show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

This dataset contains details about all Netflix Movies and TV Shows available up to the data collection date.

🧩 Data Preprocessing Steps

Imported the dataset using pandas

Checked missing values and duplicates

Converted date_added to datetime format

Extracted new columns: year_added and month_added

Cleaned and prepared data for visualization

🔎 Exploratory Data Analysis
1️⃣ Content Strategy

Movies vs TV Shows: 70% Movies, 30% TV Shows

Top Genres: Drama, Comedy, Documentaries

Top Release Years: 2017–2020

Top Content-Producing Countries: USA, India, UK

Content Growth: Sharp increase from 2015–2020

2️⃣ User Demographics & Targeting

Most Frequent Ratings: TV-MA dominates, targeting mature audiences

Countries Producing Mature Content: USA and India lead

TV Shows vs Movies Genre Split: Drama/Reality dominate TV, Action/Comedy lead Movies

3️⃣ Talent & Partnerships

Top Directors: Rajiv Chilaka, Raul Campos, Suhas Kadav

Frequent Actors: Featured mostly in Netflix Originals or local productions

Director-Genre Patterns: Raul Campos → Comedy, Jay Karas → Stand-Up

4️⃣ Duration & Engagement

Average Movie Duration: ~100 minutes

Most Common TV Show Length: 1 Season

Duration Trends: Slight decline in average movie duration in recent years

5️⃣ Content Launch Strategy

Months with Most Content Additions: July, September, and December

Best Time to Launch a TV Show: December

Recent Focus: Increased number of TV Shows post-2016

📈 Visualizations

Count Plots: Type and Rating distribution

Bar Charts: Top genres, countries, directors, and actors

Line Graphs: Yearly trends in content addition

Area Charts: Genre distribution over years

💡 Key Insights Summary
Category	Insight
Content Ratio	Movies dominate (≈70%)
Top Genres	Drama, Comedy, Documentaries
Top Countries	USA, India, UK
Ratings	TV-MA most common
Duration	Avg. 100 minutes
Growth	Major expansion 2015–2020
Best Launch Month	December
Strategic Shift	Post-2016, focus moved toward TV Shows
🚀 Future Scope

Integrate with Machine Learning for recommendation insights

Build interactive dashboards using Power BI or Streamlit

Conduct Sentiment Analysis on show descriptions

🧾 Author

Name : Jaideep Singh
Mail : jaideepwork1@gmail.com
