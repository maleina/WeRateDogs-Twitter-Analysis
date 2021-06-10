# WeRateDogs-Twitter-Analysis

## Introduction
This project was initially created as part of Udacity's Data Analysis nanodegree program in order to practice data wrangling. Specifically, it was necessary to:
1. Gather the required data from disparate sources
2. Assess the data for quality and tidiness isses
3. Clean the data programatically
4. Explore, analyze and visualize the data
5. Report on project steps and findings

## Viewing the Results
The project includes the following files and directories:
- **/images**: Directory that contains images of graphs used in the *act_report.html* report
- **.gitignore**: Files that have not been included in this repository (not necessary to run the project)
- **act_report.html**: Report of findings and results from the data analysis
- **environment.yaml**: List of software required in order to run the project
- **image_predictions.tsv**: Image predictions for tweets in the WeRateDogs Twitter Archive
- **tweet_json.txt**: Additional WeRateDogs Twitter data downloaded from the Twitter API
- **twitter_archive_enhanced.csv**: Archive of WeRateDogs tweets from November 2015 to August 2017
- **twitter_archive_master.csv**: Final integrated and clean set of the WeRateDogs twitter data
- **wrangle_act.html**: Report of the entire work process that was done as part of this project including Python Code
- **wrangle_act.ipynb**: Jupyter Notebook in which the project work was completed
- **wrangle_report.html**: Report about steps undertaken to wrangle the required data

## Running the Jupyter Notebook
It is necessary install Jupyter Notebook in order to run the main project file, *wrangle_act.ipynb*. Addition required software is listed in the environment.yaml file. You will also need to download the *twitter_archive_enhanced.csv* file and place it in the same directory as the project's Jupyter Notebook.

## Next Steps:
The analysis can be expanded by investigating:
- the popularity of the account over time (based on retweet and favorite counts)
- mapping the volume of tweets over time
- adding additional data to the set using Twitter's API
