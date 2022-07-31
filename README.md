### Covid-19 Dataset Cleaned and Explored in PostgreSQL, Dashboard in Tableau using Custom Queries.
#### This project was built from exploratory questions about how many individuals have died from covid as defined, to determine the total death count by continent(interesting to see), to determine the current death percentage and how it has adjusted with vaccinations rates, and finally to look at percent of population infected by country.  I have selected only a few countries to examine for clarity including Canada, China, France, India, Italy, Mexico, Spain, UK, and the United States.  I chose these to look at as they were major countries in the news for deaths and infections.


##### In the dataset were roughly 85,000 rows of information on Nashville Housing.  I have included a screenshot of the data prior to cleaning. Things like date formats were not standardized, property addresses included the city and state, there were several null property addresses that needed to be populated as these were different from the owner address. There were several duplicates in the data as well, of which I was able to clean out using a Common Expression Table represented as a subquery in Postgres. 

![ScreenShot](https://github.com/ignizioj/NashvilleHousingDataCleaning-PostgreSQL/blob/main/UncleanedHousing.png) 

##### Below is a screenshot of the cleaned data.  A lot more could be done with this data to prep for analysis, but for the purposes of this project, I only did a few different things to make this data more usable.


![ScreenShot](https://github.com/ignizioj/NashvilleHousingDataCleaning-PostgreSQL/blob/main/CleanedHousing.png)

##### In addtion, I have included the PostgreSQL script in this repo for reference or information. Feel free to browse any files found in the repository.  The only contributer in this project was myself.  Thanks!
