# data-analysis
this is data analysis apps data using python .
  

#  Analysis Questions
Which Google Play store app category has the greatest ratings?

Is there a significant difference in ratings between a Google Play store app that has either a restricted or non-restricted content rating?

Is there a significant difference in ratings between a Google Play store app that is either paid or free?

#  Installations
The required libraries for running the code within Jupiter notebook are part of the Anaconda distribution for Python 3.6.2. Following libraries were used:
pandas numpy collections datetime sklearn matplotlib csv

#  Dataset
The dataset for this project was found on Kaggle, and the information was collected through web scraping around 10,000 Play Store apps. Since Google Play uses modern-day techniques like dynamic page load using JQuery, this made scraping more challenging. Each app has values for category, rating, size, installs, and other app specifications. Although Google Play acts as a digital media store as well, the data covers only mobile applications. The program R was used in the analysis. To address the first question, an ANOVA test was used to observe whether there was a statistically significant difference between the ratings of each of categories. To address the second and third question, two Welch two-sample t-test were used to observe whether there was a statistically significant difference between the two different content ratings and the cost of the app. The assumptions made for all tests were met by the datasets.
