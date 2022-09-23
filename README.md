# NYSE-Project-Analytics-Spreadsheets
Kaggle's New York Stock Exchange S&P 500 dataset
Introduction
In this project we will analyze real life data from the New York Stock Exchange. You will be drawing a subset of a large dataset provided by Kaggle that contains historical financial data from S&P 500 companies. We have created a smaller subset of the data that you will be using for the project.

What do I need to install?
You may use any spreadsheet application you like. This includes Google Sheets, Microsoft Excel, etc.

Why this Project?
In this project, you will go through the process of calculating summary statistics, drawing any inference from the statistics, calculating business metrics, and using models to forecast future growth prospects for the companies. The goal is for you to perform an analysis and also create visual tools to communicate the results in informative ways.

We have provided a clean data set for this project. Although in real-life scenarios, data sets often need to be cleaned and processed before analysis can proceed. This project allows you to see what a clean data set should look like.

Background:
We used the Fundamentals.csv and Securities.csv files provided by Kaggle. The Fundamentals file provides the fundamental financial data gathered from SEC 10K annual filings from 448 companies listed on the S&P 500 index. The Securities file provided the industry or sector information the companies are categorized under on the S&P 500 index.

What skills will I use?
The main goal of this project is for you to demonstrate your ability to:

interpret the measures of central tendency and spread (mean, median, standard deviation, range).
use a combination of Excel or Google Sheets functions (e.g., IF statements, INDEX, and MATCH, calculating descriptive statistics with the IF statement, dropdowns, data validation, VLOOKUP).
analyze and forecast financial business metrics using Excel or Google Sheets.
create visualizations of a business metric and use Excel or Google Sheets to create a financial forecast model.
Project Setup
This project is made of two parts. For each part, you will be using the same dataset, which you can find in the Supporting Materials as Projectdata NYSE.csv at the bottom of this page. If you are using Google Spreadsheets, you can access the link to the data here:

Goolge sheet data
Google Sheet File	Excel sheet data
Excel file
Take a moment to download the file and make sure it looks like one of the images above.

Part One:
The first part of the project is a set of 8 quiz questions, which you will find in the following 2 pages. These 'quizzes' are aimed to help you get familiar with the dataset and test that you have mastered the core concepts in the previous lessons. Correctly answering each of the quiz questions will assure you are on the right track before you dive into the second part of the project. This part of the project will not be submitted for review.
Part Two:
The second part of your project is the portion you will turn in for review. You will conduct your own data analysis and create a presentation file to share your findings. You will also create an Excel workbook that contains your calculations of the summary statistics, dashboard, and forecast scenarios. The details of this submission are provided on the last page of this lesson. Pay attention to the details of the Rubric to assure you have all deliverables.
Supporting Materials
Projectdata NYSE

Cleaning Up The Data
Although you do not need to follow these for setting up the dataset, these are some suggestions:

Change all the column names to have no spaces, but still be informative. This isn't necessary, but just a recommendation. Depending on what you do with the data in the future having spaces or special characters in the column names may not work nicely.
The following information is included in the Projectdata NYSE file:
Ticker symbol: Stock symbol
Years: Number of years for which data is provided
Period ending
Total revenue
Cost of goods sold
Sales, General, and Administrative expenses
Research and Development expenses
Other Operating expense items
Global Industry Classification Standard (GICS) Sector: The industry sector the company is categorized under (e.g., American Airlines with the ticker symbol AAL is categorized under Industrials.)
GICS Sub Industry: Sub-industry sector the company is categorized under (e.g., AAL is further categorized under the sub-category of the "Airlines" industry.)
In case you would like to review the material on the line items within the Income Statement, please review Lesson: Business Metrics - Profit & Loss Statement.

Helpful spreadsheet formulas
Quartiles
Quartiles often are used in sales and survey data to divide populations into groups.

QUARTILE.INC(data, quartile_number) (Excel)
data - The array or range containing the dataset to consider.
quartile_number - Which quartile value to return.
Returns the quartile of a data set, based on percentile values from 0..1, inclusive.
QUARTILE.EXE(data, quartile_number) (Excel)
data - The array or range containing the dataset to consider.
quartile_number - Which quartile value to return.
Returns the quartile of the data set, based on percentile values from 0..1, exclusive.
QUARTILE(data, quartile_number) (Google Slides)
data - The array or range containing the dataset to consider.
quartile_number - Which quartile value to return.
Returns a value nearest to a specified quartile of a dataset.
Statistical formulas
Mean(Returns the average of a data set)
average(data)
mode(Returns the most common number in a data set)
mode(data)
median(Returns the middle number in a data set)
median(data)
Introduction to the project
For the final project, you will conduct three Tasks:

Complete your own data analysis and create a presentation to share your findings,
Develop a dashboard for a Profit and Loss Statement.
Create a Financial Forecasting Model using three scenarios.
You should start by taking a look at your dataset and brainstorming which sub-category and company you want to focus your data analysis on - the questions leading to this page should have assisted in this process! Then you should use spreadsheets or another Excel-like software to conduct your analysis and choose a sub-category and company you are most interested in. This project is open-ended in that there is no one right answer.

Project Details


Planning ahead
These files listed here are what you will be working on in the project:

The presentation with the visuals and summary
A copy of the spreadsheet workbook you will use to do the analysis for your report contains the following tabs:
Data file
Summary statistics
P&L Statement Dashboard
Forecast scenarios
Here are the three tasks that you will complete in the final project.

Task 1:
a. Identify the question about the data that you will answer based on your data analysis and include this in your slide presentation.

Your question should include at least one categorical variable (GICS Sector or GICS Sub Industry) and one quantitative variable (one of the financial metrics) and require the use of at least one of the summary statistics.
A tab within the Excel spreadsheet that you submit should include the summary statistics [measures of central tendency (e.g., mean, median) and measures of spread (standard deviation and range)] you used to answer your question.
Deliverable:
Slide presentation
Spreadsheet with tab for Summary statistics
b. Your slide presentation should provide at least one visualization to help support your answer.

Make a copy of the submission template to complete your project. We suggest you use the layout provided, though it is not a requirement. You can find the MS Powerpoint version of the Project Submission template under the Resources.
Once you have finished analyzing the data, in the submission template provided, create your presentation that shares the visual and summary information.
The summary information paragraph clearly communicates your findings based on your analysis and provides visual or numeric values associated with your summary.
The visualization(s) might be a bar chart, histogram, scatterplot, box-plot, or other visual that you learned to make. Include your insights from the measures of center and spread and at least one numeric summary statistic in the summary description.
Deliverable: Slide presentation (includes visualization)
Task 2:
Create a dashboard for a Profit and Loss Statement that calculates the Gross Profit, Operating Profit, or EBIT for a company selected from a drop-down list. Include all companies from the raw data.
Your drop-down list should pull historical fundamentals data to create the P&L Statement.
The P&L statement should include the Gross Profit, Operating Profit, or EBIT values for all the years there is historical data available for that company in the dataset.
Deliverable: Spreadsheet with tab for Dynamic P&L statement
Task 3:
Create a financial model for a company (different from Task 2) of your choice that forecasts out the Gross Profit, Operating Profit, or EBIT for two more years using three scenarios (Best case, Weak case, and Base case).
Your assumptions for revenue growth, gross margin, and operating margin should change for each scenario.
The forecasting model should be dynamic for the selection of the case (Weak, Base, Strong). However, the forecasting model can be static for the chosen company sticker symbol.
Deliverable: Spreadsheet with tab for Forecasting Model
Check the Rubric
Use the Project Rubric located here. If you see room for improvement, keep working to improve your project.

Assemble your folder ready for submission
If you are checked the rubric and are satisfied with your submission, then you're ready to submit your project. Include your presentation and all spreadsheet workbooks in a folder and zip it. Then submit the zipped folder for your project.

