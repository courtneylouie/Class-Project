# Final Project  

**Overview**  
I used the scholarly package to get publication titles, years, and number of citations from Google Scholar for animal science professors at 5 universities in the US. I cleaned the data by checking for outliers, non-English titles and present some summary statistics and word clouds. Then I used knn regression to predict the number of citations based on the text of the publication titles.

**Getting the data**  
Notebook: data_acquisition.ipynb  
Output dataset: data.txt  
In this notebook, I used the scholarly.search_author() function from scholarly package to get publication data for animal science professors at 5 universities. At the end, I also discuss the pros and cons of the data extraction method that I used.  

**Exploring and Cleaning the Data**  
Notebook: data_exploration.ipynb  
Input dataset: data.txt  
Output dataset: cleaned.txt  
This notebook is my favorite! In this notebook, I found some non-English publication titles, and checked for and removed erroneous observations and profiles. I also did some summary statistics including counting the number of publications per professor and exploring the relationship between age and number of publications. I also made word clouds to see what topics are popular at each university.  

**Modeling**  
Notebook: statistics.ipynb  
Input dataset: cleaned.txt  
