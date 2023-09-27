# Real-Estate-Sales-2021-GL

### About App

The Office of Policy and Management maintains a listing of all real estate sales with a sales price of $2,000 or greater that occur between October 1 and September 30 of each year. For each sale record, the file includes; town, property address, date of sale, property type (residential, apartment, commercial, industrial or vacant land), sales price, and property assessment.

Data are collected in accordance with Connecticut General Statutes, section 10-261a and 10-261b: https://www.cga.ct.gov/current/pub/chap_172.htm#sec_10-261a and https://www.cga.ct.gov/current/pub/chap_172.htm#sec_10-261b. Annual real estate sales are reported by grand list year (October 1 through September 30 each year). For instance, sales from 2019 GL are from 10/01/2018 through 9/30/2019.

I wanted to explore the Real Estates sales performance and patterns, and traind ans select the best befitting model to predict a property sale amount given the available property features, using python based tools they turn out to a dependable language for most data science projects.

### How it works

The Real Estate Sales 2021 GL is a Streamlit App. The app is built on python code(main.py).

Its structure is as follow;

To the left side of the app is a sidebar which contains a header('Real Estate Sales GL'), and a selectbox which holds a title('Key Performance Indicators(KPI) and a menu which has 'About' as its default

The menu has four features;

'About', 'Sales Image', 'Data Analysis', and 'Machine Learning'.

### Main Features

### About

This feature displays a property image including a brief explanation of what the app  is about including the link to the data source


### Sales Image

This feature display the visuals. it also contains checkboxes which when clicked on display more visuals. The visuals in this feature include; 

A bar chart which represents the monthly property sales performance for year 2021

A scatter plot which establishes the relationship between the property Sale Amount and Assessed Value

A bar chart which represents sales by property type

And a pie Chart Sales by Residential Type.

### Data Analysis 

This feature displays the first five rows of the dataframe and two checkboxes

When you click on the first check box, it displays the shape of the dataframe(the number of rows and columns) and the descriptive statistics.

The second checkbox displays frequency tables for the Property and Residential types for financial year 2021

### Machine Learning

This feature displays a property image and predicted sales amount based on given property features.

### Main Libraries Used
  | # Tools/Libraries | # Purpose                                                     |
  |-------------------|---------------------------------------------------------------|
  | Streamlit         | Dashboard Design                                              |
  | Plotly            | Interactive graph                                             |
  | Numpy             | Performing mathematical Operations                            |
  | Pandas            | Analysis, cleaning, exploring and manipulation of data        |
  | Scikit Learn      | Modelling                                                     |
  | Pickle            | Saving model and loading saves model                          |
  | Image from PIL    | Loading Image                                                 |

### Models Trained and Tested

Random Forest Regressor. 

It gave me a score of 96.778% on the train set and 76.286% on the test set which turned out to be the best performing model. When i tried hyperparameter tuning it did not perform any better.

Bagging Regressor

This model gave me a 95.6% score on the train set and 74.3% on the test set which is slightly less the performance of the rando forest regressor.

Kernel Ridge Regressor

The Kernel Ridge Regressor gave me a memory error.

Linear regression model

Before normalizing the dataset, it gave me a train score of 73.8% and a test score 72.2%.

In conclusion I chose to work with the random forest regressor. 


### Challenges faced

My note book crashed thrice during the EDA and Preprocessing stages.

I hard to learn working with libraries am not familiar with the hard way. 

Being the first time in an online class I had to learn to be independent unlike the other classes where we would count on colleagues for discussions.

App deployment. During app deployment, i kept on recieving error which kind of got me frustrated. On researching i learned that i had to keep adjusting my reqirements.txt inluding upgrading and downgrading some libraries. Thanks to God it worked. 

Difficulty in accessing data from various organizations around for practicle learning
Limited resources and internet.

Memory error more so during modelling hence i had to trim the dataframe.

Being unemployed and depending on the informal sector for survival i have not had the opportunity to have enough practicle experience in a organised entity.

Pushing my folder to Github since some of them are bigger than 100MB

### Licensing 

This project is licensed under MIT Licence. see the License file for more details.

### Future Prospect

Looking foward to collect more data in order to boost model accuracy and to build more apps of this kind for more user satisfaction. Incase of any idea, suggestion or contribution please send me an email on joereblac@gmail.com

### Author

Okello Daniel

I am a data science enthusiast and a Business Statistics graduate from Makerere University. I picked more interest in python because of its vast pool of libraries for scientific computation.

