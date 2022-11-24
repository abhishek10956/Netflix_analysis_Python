# Netflix_analysis_Python
## Description
<br /> To analyse Netflix dataset and find some relations using Jupyter Notebook form PyCharm.
<br /> Imported dataset 'csv' file
<br />Imported Pandas and Seaborn libraries to carry out operations.
<br />Derived heat-maps and bar graphs.
<br />Used functions like 
<br />data.info()
<br />data.isnull().sum()  
<br />data.drop_duplicates(inplace = True)
<br />sns.heatmap(data.isnull())
<br />data[data['Title'].isin(['House of Cards'])]
<br />data['New_date']= pd.to_datetime(data['Release_Date'])
<br />data['New_date'].dt.year.value_counts()

<br />data['Category'].value_counts().plot(kind='bar')
<br />data[  (data['Category'] == 'Movie') & (data['Year'] == 2020 ) ]
<br />data[(data['Category'] == 'Movie') & ((data['Type'] == 'Comedies') | (data['Country'] == 'India'))]
<br />data_new = data.dropna() 
<br />data['Rating'].unique() 
<br />data[(data['Country'] == 'Canada') & (data['Category'] == 'Movie') & (data['Rating'] == 'TV-14')].shape
<br />data.sort_values(by='Year')



## Questions
<br />1. Is there any duplicate record in this dataset....?
<br />2. Is there any null value in dataset? Show with heat map.
<br />3. Seaborn library (heat-map)
<br />Q1. For 'Wake Up Sid',what is the show id and who is the director of this show?
<br />Q2. In which year highest no. of Series & Movies were released? Show with Bar graph.
<br />Bar graph
<br />Q3. How many TV shows & movies are in dataset
<br />Q4. Show all movies released in year 2020.
<br />Filtering
<br />Q5. Show Title of TV Shows released in India only.
<br />Filtering
<br />Q6. Show top 15 directors who gave highest number of TV Shows & Movies on Netflix
<br />Q7. Show all records where "Category is Movie" and "Type is Comedies or Country is India".
<br />Q8. In how many Shows/Movies, Tom Cruise was the cast.
<br />Q9.1 What are different Ratings defined by Netfix.
<br />Q9.2 How many TV Shows got 'R' Rating after year 2018?
<br />Q10. What is Maximum duration of Movie/Show on Netflix?
<br />Q11. Which individual country has the highest No. of TV Shows ?
<br />Q12. How can we sort data set by Year ?
<br />Q13. Find all the instances where :
Category is 'Movie' and Type is 'Dramas'
or
Category is 'TV Show' and Type is 'Kids TV' ?
