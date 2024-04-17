# Coursera-Final-Project

IBM-Capstone
In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage.
Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

Task One: Introduction
We will be provided with an overview of the problem and the tools we need to complete the course.
Data Collecting
1.	Connect API
2.	Get data part 1 csv file
3.	Web - Scraping: We will be performing web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled List of Falcon 9 and Falcon Heavy launches
4.	Get spacex_web_scraped.csv


Data Wrangling
1.	We will perform some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.
2.	In this part we will mainly convert those outcomes into Training Labels with 1 means the booster successfully landed 0 means it was unsuccessful.
3.	Get data part 2. csv file

   
Task Two: Exploratory Data Analysis
Exploratory Analysis Using SQL
Load the dataset into the corresponding table in a Db2 database
Exploratory Analysis Using Pands and Matplotlib
1.	Visualization by using Panads and Matplotlib
2.	Get data part 3 csv


Task Three: Interactive Visual Analytics and Dashboard
Launch Sites Locations Analysis with Folium
The launch success rate may depend on many factors such as payload mass, orbit type, and so on. It may also depend on the location and proximities of a launch site
Goal: Finding an optimal location for building a launch site certainly involves many factors and hopefully we could discover some of the factors by analyzing the existing launch site locations.
1.	Plot each launch site on the site map
2.	Mark the success/failed launches for each site on the map
3.	Calculate the distances between a launch site to its proximities


Dashboard
1.	Add a Launch Site Drop-down Input Component
2.	Add a callback function to render success-pie-chart based on selected site dropdown
3.	Add a Range Slider to Select Payload
4.	Add a callback function to render the success-payload-scatter-chart scatter plot


Task Four: Predictive Analysis (Classification)
Perform exploratory Data Analysis and determine Training Labels
•	create a column for the class
•	Standardize the data
•	Split into training data and test data
Find best Hyperparameter for SVM, Classification Trees and Logistic Regression
•	Find the method performs best using test data
