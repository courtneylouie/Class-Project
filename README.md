# Faculty Research in Animal Science

**Overview**  
This is a project for my Data & Web Technologies for Data Analysis class. Skills learned include data wrangling using pandas, plotting using seaborn, word clouds, natural language processing using scikitlearn and TfidfVectorizer, knn regression, knn classification, and kmeans clustering.

I used the scholarly package to get publication titles, years, and number of citations from Google Scholar for animal science professors at 5 universities in the US. One goal was to see whether research topics vary a lot by university. For this, I made word clouds. Another goal was to make predictions based on the text of the titles.

**Getting the data**  
- Notebook: data_acquisition.ipynb  
- Output dataset: data.txt  

In this notebook, I used the scholarly.search_author() function from scholarly package to get publication data for animal science professors at 5 universities. At the end, I also discuss the pros and cons of the data extraction method that I used.  

**Exploring and Cleaning the Data**  
- Notebook: data_exploration.ipynb  
- Input dataset: data.txt  
- Output dataset: cleaned.txt  

This notebook is my favorite! In this notebook, I found some non-English publication titles, and checked for and removed erroneous observations and profiles. I also did some summary statistics including counting the number of publications per professor and exploring the relationship between age and number of publications. I also made word clouds to see what topics are popular at each university.  

**Modeling**  
- Notebook: statistics.ipynb  
- Input dataset: cleaned.txt  

In this notebook, I wanted to see what kinds of things I could predict using the text of the titles. One thing I tried was predicting the number of citations based on the title. For this, I used knn regression and that didn't give a very effective prediction. I then used a knn classifier to predict the author based on the title. I also used a separate knn classifier to predict the school based on the title. 
