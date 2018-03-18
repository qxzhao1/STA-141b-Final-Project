## PART 2 Analysis about the potential influence features that may account for the difference in Box Office

After finding out those 7 movies that are produced domestically while having higher Chinese Box Office, we focus on finding the reason behind it. Based on common potential possibilities that may influence the Box Office of a specific movies, we decide to focus on director effect, leading cast effect, popularity effect and social media effect. 

### Fetching data:
First step is getting needed data from the corresponding websites. Folder named "DATA fetching for different feature studies for those 7 movies" contains notebooks about the methods of fetching each feature data set. There are total three notebooks where the methods of getting actor and director data are in the same notebook basically because the structure of the web pages of the actor data and director data are similar. 

### csv file: 
The output csv files for this part are under the file “CSV file for feature analysis data”. Each feature is a separate file and the file “actordata” and “directordata” are the detailed data of those features.

### Analysis:
The data visualization steps and comments are under file ANALYSIS, we use the regular plots as well as interactive plots because for director analysis and actor analysis, individual differences are huge and can not be modified and therefore, the use of interactive plots is necessary of readers to get a right handle of the data and even making their own inference!

### Conclusion:
After this study, we actually find out that the popularity and social media rating features are not so related to the Box Office while the director and actor effects can not be ignored.  

## STA-141b Final Project instructions

**Description**: You should work in a group of no more than 4 people on a final data science project.  The purpose of the project is to provide you with real data science experience, including posing questions, finding data, exploring and visualizing the data, analyzing the data, and summarizing your findings.  As a group you should begin with a certain curiosity, for example, in my lecture 'What happened in Ohio?' I looked at the presidential election in OH.  Then we processed the data, visualized it, and asked specific questions.

**Data Sources**: Based on what you have learned you can extract data from pretty much anywhere, but for inspiration you can look at the following links:
- [This big list of datasets](https://github.com/awesomedata/awesome-public-datasets)
- [Data.gov](http://data.gov)
- The internet

**Grading criteria**
- Code: we will grade the code according to the rubric
- Exploratory data analysis: Did you explore the data before moving on with your analysis?  Looking at the data can mean summary statistics, dealing with missingness, visualization, etc.
- Question and summaries: Are there clear research questions that you asked, and did you address these in an orderly fashion?  Do you make well justified conclusions?
- Statistics: is your use of statistics and machine learning valid?  Did you choose appropriate methods based on your questions, the data, and your assumptions?
- Visualization: do your visualizations follow the principles of graphical excellence?  Do your visualizations support your conclusions?
- Data extraction: does your project display novel ways of extracting data (via web scrapping, etc.) and do you use multiple data sources?
- Data munging and storage: do you process the data in an clear, efficient, and organized way?  Do you join multiple data sources appropriately?  Do you store your processed data in an efficient way, using databases or well thought out data structures?
- Organization: Is your github repo organized?  Are your notebooks clear, with a natural flow, and easy to follow presentation?  Is your writing clear and edited?

We will grade each of these according to a scale, with the highest grades going to only the best examples of these categories.  Then we will drop the lowest 2 of these scores, so that we will promote excellence without necessarily requiring that the you hit all of these bases.  We will also add grades to smaller groups, and penalize larger groups.  You should roughly have material proportional to the number of people in your group.

Feel free to remove this README or cache it as another file, then add you own README describing your project.  It should be clear what notebook the reader should be looking at.
