# YouTube Trending Videos Analysis

This repository contains a data analysis project developed as a **Jupyter Notebook**, focused on the analysis of YouTube trending videos across multiple countries.

The project has been developed according to the following instructions:
1. Create a single dataframe with the concatenation of all input csv files, adding a column called country
2. Extract all videos that have no tag.
3. For each channel, determine the total number of views
4. Save all rows with disabled comments and disabled ratings, or that have video_error_or_removed in a new dataframe called excluded, and remove those rows from the original dataframe.
5. Add a like_ratio column storing the ratio between the number of likes and of dislikes
6. Cluster the publish time into 10-minute intervals (e.g. from 02:20 to 02:30)
7. For each interval, determine the number of videos, average number of likes and of dislikes.
8. For each tag, determine the number of videos
Notice that tags contains a string with several tags.
9. Find the tags with the largest number of videos
10. For each (tag, country) pair, compute average ratio likes/dislikes
11. For each (trending_date, country) pair, the video with the largest number of views
12. Divide trending_date into three columns: year, month, day
13. For each (month, country) pair, the video with the largest number of views
14. Read all json files with the video categories
15. For each country, determine how many videos have a category that is not assignable.

---

##  Dataset Description

The dataset consists of YouTube trending videos collected for the following countries:

- CA – Canada  
- DE – Germany  
- FR – France  
- GB – United Kingdom  
- IN – India  
- JP – Japan  
- KR – South Korea  
- MX – Mexico  
- RU – Russia  
- US – United States  

For each country, the dataset includes:
- a CSV file with trending video information
- a JSON file containing the video category mapping

---

##  Technologies Used

- Python 3
- Jupyter Notebook
- pandas
- numpy
- json
