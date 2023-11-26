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

*Result:*
1. *Funding Stages Analysis:*
   - The Later stage emerges as the top-funded stage in the Indian ecosystem, securing an impressive $154.03 billion. This highlights a trend where more established companies with a clear product-market fit and proven revenue generation attract significant funding.

2. *Location Impact:*
   - Mumbai takes the lead as the top location, securing the highest funding amount of $237.16 billion, followed by Bangalore with $36.33 billion. Gurugram, New Delhi, and California also received varying amounts of funding.

3. *Null Hypothesis:*
   - The analysis fails to reject the Null Hypothesis, indicating that the sector in which a startup operates doesn't significantly impact its funding amount.

4. *Sector-Specific Insights:*
   - Fintech, Retail, E-commerce, and Tech companies stand out as the sectors with the highest funding amounts.

*Recommendations:*
1. *Diversify Funding Strategies:*
   - Explore diverse funding strategies to accommodate the varied needs of companies in different stages. Consider tailoring approaches for early-stage and later-stage businesses.

2. *Strategic Geographic Expansion:*
   - Focus on strategic geographic expansion, acknowledging the dominance of Mumbai, Bangalore, and Gurugram in attracting funding. Identify emerging locations for potential growth.

3. *Sector-Specific Investment Considerations:*
   - Given the top sectors receiving substantial funding, consider sector-specific investment strategies. Stay informed about trends and opportunities in Fintech, Retail, E-commerce, and Tech industries.

4. *Continuous Monitoring and Adaptation:*
   - Continuously monitor the fluctuating funding landscape, adapting strategies to capitalize on periods of substantial growth. Stay agile and responsive to market dynamics.

5. *Support for Early-Stage Startups:*
   - Recognize the need for increased attention and support for early-stage startups. Implement programs or initiatives to foster growth and innovation in this critical phase.

6. *Collaborative Ecosystem Building:*
   - Foster collaboration within the startup ecosystem. Encourage partnerships between startups, investors, and industry players to create a thriving environment for innovation.

These insights and recommendations aim to guide strategic decisions, foster growth, and position stakeholders for success within the dynamic landscape of the Indian startup ecosystem.

## Reference

The dataset used in this project is sourced from Flixable, a third-party Netflix search engine. Flixable provides comprehensive information about TV shows and movies available on Netflix up until 2021. The dataset is freely accessible on Kaggle, a platform for data science and machine learning enthusiasts. The data from Flixable serves as a valuable resource for exploring trends, patterns, and insights within the Netflix content landscape. The original dataset can be found on Kaggle, and credit goes to Flixable for compiling and making the data publicly available.







  
