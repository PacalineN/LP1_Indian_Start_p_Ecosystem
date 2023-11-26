![My Image](https://www.mercy.edu/sites/default/files/2020-07/iStock-1150199386.jpg)

# Exploring Trends in the Indian  Startup Funding ecosystem: A Data Analysis (2018-2021)

## Table of Content 
- [Project Overview](#project-overview)
- [Data sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning/Preparation](#data-cleaning)

- [Exporatory Data Analysis](#exporatory-data-analysis)
- [Results/Findings](#results)
- [Recommendation](#recommendation)
- [Reference](#reference)
  
   


## Project Overview
Welcome to our project, "Exploring Trends in the Indian Startup Funding Ecosystem." Here, we delve deep into the Indian startup landscape, conducting a thorough analysis of data spanning from 2019 to 2021. Leveraging the power of Python and data visualization through Power BI, we, as data analysts in this venture, aspire to uncover captivating trends within the expansive funding landscape of Indian startups. Join us on this exploration as we unravel the story behind the numbers, shedding light on the intricate patterns that have shaped the financial journey of startups in India during this critical period. 
## Data sources 
The data sources for this project are attributed to aAzubi Africa, providing access to information in three distinct parts. The initial dataset, encompassing data for 2020 and 2021, was securely stored in a database, accessible remotely. The second dataset, pertaining to the year 2019, was obtained from OneDrive. The final dataset, covering the year 2018, was sourced from a GitHub repository and was available in CSV format.

## Tools Used
- Python 
- Pandas   
- Matplotlib and Seaborn
- PowerBI for crafting data visualizations and constructing dashboards


## Data Cleaning


In the initial phase of data preparation, I undertook the following tasks:

1. *Data Loading and Inspection:*
   - Loaded the data from various sources and conducted a thorough inspection year by year.

2. *Renaming Columns:*
   - Renamed some columns to align with other dataset columns, for example, changing "Amount" to "Amount($)".

3. *Concatenating Datasets:*
   - Combined datasets from different sources to create a unified dataset.

4. *Inspecting the Combined Dataset:*
   - Reviewed the combined dataset column by column.

5. *Handling Missing Values and Inconsistent Labels:*
   - Managed missing values and addressed inconsistent labels to ensure data integrity.

6. *Handling Currency Conversion:*
   - Converted Indian Rupees (₹) to US Dollars ($).

7. *Dropping Unnecessary Columns:*
   - Removed some columns that were not going to be used.

8. *Data Cleaning and Formatting:*
   - Cleaned and formatted the data by connecting and categorizing related information.

This comprehensive data cleaning and preparation process ensures the dataset's reliability and sets the stage for meaningful analysis and insights.

## Exporatory Data Analysis

## Exploratory Data Analysis (EDA) Overview

The Exploratory Data Analysis (EDA) stage plays a crucial role in unlocking the secrets of the Indian startup dataset. Here, I dig into the data to uncover patterns, trends, and valuable insights. This exploration focuses on answering key questions:

1. **Which Industry Got the Most Funding?**
   - Figuring out which industry scored the big bucks in terms of funding.

2. **Top Location for Funding:**
   - Pinpointing the location that bagged the most funding.

3. **Annual Companies with Funding:**
   - Checking out how many companies snagged funding each year.

4. **Yearly Total Funding Amount:**
   - Adding up the total funding received each year to understand the financial landscape.

5. **Most Funded Company:**
   - Identifying the top dog that raked in the most funds.

This deep dive isn't just about answering questions but setting the stage for a deeper understanding of the data. It's all about turning raw numbers into meaningful insights that guide the next steps in our analysis. Let's uncover the stories behind the data!
## Results 

The Netflix dataset analysis reveals significant trends. The year 2019 stands out with the most releases, marking a pivotal moment in Netflix content production. Raúl Campos, Jan Suter, and Marcus Raboy lead in directorial contributions, emphasizing their impact on Netflix's diverse content landscape. The dataset's ratings, encompassing 'TV-MA,' 'R,' 'PG-13,' etc., showcase the platform's commitment to varied content suitability. The United States dominates TV show contributions, emphasizing its global influence. A concise bar graph illustrates the distribution of movies and TV shows, highlighting insights into content diversity. 
![Bar graph](https://github.com/PacalineN/Netflix-Data-Analysis-with-Python-Unveiling-Insights-and-Trends/assets/149051166/7cf723dc-8a28-4437-8ca3-189ec759e756)

## Recommendation
For those intrigued by the dynamics of Netflix content, this project offers a compelling exploration of key facets. The detailed analyses and visualizations provide a nuanced understanding of release patterns and directorial contributions. The inclusion of content ratings and a focus on top directors enhance the depth of insights. The project's use of a bar graph to represent distribution adds clarity. Overall, this analysis serves as a valuable reference for individuals interested in content consumption trends on streaming platforms, providing a comprehensive overview of Netflix's evolving content landscape.

## Reference

The dataset used in this project is sourced from Flixable, a third-party Netflix search engine. Flixable provides comprehensive information about TV shows and movies available on Netflix up until 2021. The dataset is freely accessible on Kaggle, a platform for data science and machine learning enthusiasts. The data from Flixable serves as a valuable resource for exploring trends, patterns, and insights within the Netflix content landscape. The original dataset can be found on Kaggle, and credit goes to Flixable for compiling and making the data publicly available.







  
