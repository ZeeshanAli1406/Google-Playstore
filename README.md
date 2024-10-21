Google Play Store Apps EDA
Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a dataset of apps available on the Google Play Store. 
The goal is to understand the key factors that drive app success, user engagement, and popularity. 
We analyze various features of the apps, such as ratings, downloads, categories, and monetization strategies, 
and uncover insights that can benefit app developers, marketers, and product managers.

Key Features:
App Ratings Distribution: Analyzing the distribution of user ratings to identify trends and outliers.
Category Performance: Studying the performance of different app categories to see which types of apps have higher popularity and user engagement.
Monetization Strategies: Comparing free vs. paid apps and how these strategies impact downloads and user adoption.
Impact of Reviews and Installs: Investigating the correlation between the number of reviews, installs, and app ratings to measure app success.
Dataset
The dataset used in this analysis contains various attributes of apps available on the Google Play Store, such as:

App: The name of the app.
Category: The category to which the app belongs.
Rating: The average user rating of the app.
Reviews: The number of user reviews.
Installs: The number of installs/downloads of the app.
Type: Whether the app is free or paid.
Price: The price of the app (if applicable).
Content Rating: The target audience of the app.
Genres: The genre(s) of the app.
Last Updated: The last date the app was updated.
Current Ver: The current version of the app.
Android Ver: The minimum Android version required to run the app.
Installation
To run this project locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/google-playstore-eda.git
Navigate to the project directory:
bash
Copy code
cd google-playstore-eda
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
After setting up the environment, you can explore the dataset and run the analysis by executing the Jupyter notebooks provided in the repository.

Running the Analysis
To execute the project:

Open Jupyter Notebook:
bash
Copy code
jupyter notebook
Open and run the provided notebooks to explore the dataset and visualize the findings.
Results
Key insights gathered from the analysis:

Ratings Distribution: Most apps have average ratings between 4.0 and 4.5.
Category Performance: Categories such as "Games" and "Entertainment" have the highest download counts.
Free vs. Paid Apps: Free apps generally receive more downloads, but paid apps show higher user engagement in specific niches.
Correlation between Reviews and Installs: Apps with a high number of installs also tend to have more reviews, indicating popularity and user interaction.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Contributing:
Contributions are welcome! Feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.
