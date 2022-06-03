## Overview

We are looking to provide Microsoft with actionable information regarding high ROI studio projects for Microsoft's new streaming service. The analysis of variables such as budget level, gross box office, ROI, ROI/profit by genre, movie ratings and IMDB ratings by director should help us in deducing useful insights. 

## Business Understanding

Some of the insights we hope to discover for Microsoft are optimal budget levels, suggested genres that have a lower risk profile, and optimal directors and writers for this piece of work. Our questions of interest include: what is the optimal budget level for our film?, what genre of film has the best ROI despite ratings level?, and what director has high ratings ratings while also displaying a large audience reach?

## Data Understanding and Analysis

## Source of data

We are sourcing our data from several difference database vendors including: IMDB database, Rotten Tomatoes, Box Office Mojo, The MovieDB, and The Numbers. We received the data files in CSV, TSV and Zipped SQLite format. The IMDB SQLite file includes eight different tables, with each table having from two to eight columns. The CSV files incorporated data from The Movie Database, Box Office Mojo, and The Numbers. These files have anywhere from six to eleven columns and include key data such as gross box office, budget, and movie titles. The TSV files covers the Rotten Tomato data, having between nine to thirteen columns.

Our presentation, where we analyze our dataset can be found at:
["Win the Streaming Wars By Minimizing Production Risk"](AMA_Productions__Microsoft_Streaming_Service.pdf)



## Description of data

Three visualizations (the same visualizations presented in the slides and notebook)

visualization_images/Ratings_and_Vote_unfiltered.png



![Profit and Ratings Correlation](visualization_images\Profit\and\rating\correlation.png) 

![Budget Tier and Adjusted ROI](visualization_images/Budget_Tier_and_Adjusted_ROI.png)

![Proposed Microsoft Budget Allocation By Budget Tier](visualization_images/Proposed_Microsoft_Films_Budget_Allocation_by_Budget_Tier.png)

![Proposed Microsoft Films By Budget Tier](visualization_images/Proposed_Microsoft_Films_by_Budget_Tier.png)

![Ratings and Vote Totals By Director](visualization_images/Ratings_and_Vote_unfiltered.png)

![Ratings and Vote Totals By Director](visualization_images/Ratings_and_Vote_filtered.png)



## Conclusion

We found that investments in blockbusters produce a higher risk adjusted ROI than lower budget films. Romance is the most derisked genre, as even the failures (measured bu ratings) generate a profit. Choose the best rated directors that produce the highest number of votes (or "buzz"). A Christopher Nolan romance blockbuster coming soon to theaters near you!


## Repository Structure

├── 2.0-Microsoft-Movie-Analysis-AMA-Productions
│   ├── final_notebook.ipynb
│   ├── AMA_Productions__Microsoft_Streaming_Service.pdf
│   ├── README.md
│   └── .gitignore
├── movie_data_erd.jpeg
├── visualization_images
├── CONTRIBUTING.md
├── LICENSE.md
├── zippedData/
├──awesome.gif
└── im.db


