# AppleStoreEDA
The give project perform exploratory data analysis on Apple Stores dataset collected from Kaggle using SQL and use Python Matplotlib for data visualizations. For this purpose, VS Code IDE platform is used.
Firstly the required CSV files are downloaded from Kaggle and the data is imported into Microsoft SQL Server Management Studio. The given data is saved in respective tables i.e. Apple Store and AppleStore Description tables.

To connect SSMS with VSCode, pyodbc library was used that helped in making the initital connection. The SQL queries are read using Pandas dataframe and their respective results are stored either in a variable or in dataframe where the visualization is implemented. The given project explores following questions:
i. What are the unique apps in given tables
ii. What are the top 5 genre based on number of apps
iii. What is minimum, maximum and average ratings
iv. What are popular apps classified into Paid & Free based on average ratings
v. If higher number of languages support helps in making an app receive higher ratings.
vi. Which 5 genres has recevied lower ratings
vii. If length of app's description correlates with its popularity in receiving higher ratings
viii. What are top tracks in top 5 genres that received maximum ratings
ix. What are 5 popular tracks that receive highest ratings
x. What are top 5 tracks based on price?
xi. What are top 5 tracks based on revenue they generate?
xii. What are top 5 tracks which are user favorties?
xiii. Which content is more popular?
xiv. Which app version(s) are favortie versions.

