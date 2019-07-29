# GooglePlayAnalysis
___Created by Eric Gong, Raian Rahman, Tony Li, Russel Tsang___

This statistical analysis is based on the Kaggle dataset ‘googleplaystore.csv’, which is a
collection of web-scraped data of 10000 Play Store apps. Our goal was to analyze this data in
order to generate interesting insights within the Android market. We decided to explore
relationships between different meaningful attributes such as App Category, User Ratings, # of
Reviews, Free vs Paid, and Content Ratings.

After removing duplicate App names, and categories with little to no apps, we were left with
8881 apps to analyze. One finding that is very visible is that the most popular app category is
almost twice as popular as the next most popular app category (Family: 1827 apps vs Game: 927
apps). Through our box plot that compares App Category and User Ratings, we also found a
range of median User Ratings across all app categories, spanning from 4.1 - 4.5. We continued to
evaluate various significant relationships through additional graphs.

Furthermore, we continued to analyze the Google Playstore by inspecting a sentiment analysis
data set through the dataset, ‘googleplaystore_user_reviews’. This dataset contained the first
“most relevant” 100 reviews for 1075 apps. It also contained many missing values and values
that read as “NaN”. After we cleaned this dataset, we were left with 35899 rows in the excel
sheet to further examine. Using python, this dataset was merged with the original dataset in order
to conduct an analysis on the amount of positive, neutral, and negative reviews. Lastly, we had
also examined the sentiment polarity across different categories.
