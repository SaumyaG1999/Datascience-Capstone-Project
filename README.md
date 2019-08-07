# Datascience Capstone Project
This project is a part of the [Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025) by [Udacity](https://www.udacity.com/).

## Project Overview
The Starbucks Udacity Data Scientist Nanodegree Capstone challenge data set is a simulation of customer behavior on the Starbucks rewards mobile application. Periodically, Starbucks sends offers to users that may be an advertisement, discount, or buy one get one free (BOGO). An important characteristic regarding this dataset is that not all users receive the same offer and there is variety among these 3 offers.

The data set is divided in three files.The first file(portfolio.json) contains offer ids and meta data about each offer.The second file(profile.json) contains demographic data of each customer. The last one(transcript.json) contains records for transactions, offers received, offers viewed, and offers completed.

An offer is only successful when a customer both views an offer and completes it within the given period of time.

## Project Statement
In my capstone project, I aim to answer the following business problems:

1. What should be the target age_range of the customers.
2. Which offer to provide to a customer of a particular 'age group'.
3. Can we determine a channel/medium through which an offer shuld be sent to make it a successful one, given the demographic features of a customer. 

## Files Description
This repo contains 4 files. The report of my project is called 'Starbucks Capstone Challenge - Using Starbucks app user data to predict effective offers.ipynb'. The data used in the project is in the files portfolio.json, profile.json and transcript.json.

## Detailed Findings
For a post summarizing the most relevant results from this analysis, please refer the the [Story on Medium](https://medium.com/@saumyagarg2299/starbucks-hows-the-offer-a12525ca7fc6)

## Installations
* pandas 
* numpy 
* math
* json
* matplotlib.pyplot
* LabelBinarizer
* OneHotEncoder
* MultiLabelBinarizer
* % matplotlib inline

## License And Acknowledgement
This project uses data provided by Starbucks as part of Udaciy Capstone project.



