# Airbnb-Listings-Analysis
####  Airbnb encourages users to share their experiences about their stay in the accommodations - that may include about the host, food, culture, behavior, nature etc. The objective of the project is to analyze Airbnb data to identify key factors which may help other travelers before making their final choice.
#### This involves data preprocessing, conducting exploratory data analysis, performing descriptive analysis with various data analysis and visualization techniques, predictions using statistical models, and machine learning models. Multiple tools such as Python, MySQL, Tableau, are used in the project.
# Data Description
#### Two separate datasets: one for France and one for Germany listings.
#### Both datasets had the same structure (same number of columns and matching column names), allowing seamless merging after cleaning.
#### Missing values were handled using multiple imputation techniques such as:
#### Mean/Median imputation for numerical features
#### Mode imputation for categorical features
#### Dropping rows/columns with excessive missingness
#### After preprocessing, the datasets were concatenated into a single combined dataset for unified analysis.
#### Dataset Access
##### Due to file size limitations on GitHub, the full Airbnb listings datasets for France and Germany are hosted externally.

📁 Download Link (Google Drive):
🔗 https://drive.google.com/drive/folders/18i5lVKD8Qj-IuDlC-C-wgvBGCo9zu6SR?usp=sharing

After downloading, please extract the files and place them inside a local /data directory before running the Jupyter notebooks or scripts.
# Data Preprocessing
#### Performed null value treatment using appropriate imputation strategies.
#### Merged both country datasets based on common schema.
#### Handled outliers using statistical techniques (e.g., IQR method) prior to model building.
#### Encoded categorical variables and scaled numerical features where required.
# Exploratory Data Analysis (EDA)
#### Visualized price distribution, review patterns, availability, and geographical trends.
#### Compared host activity, room types, and listing behaviors across both countries.
#### Identified correlations between key features like price, number of reviews, etc.
## Created interactive Tableau dashboards for:
#### Time series analysis of average listing price over time
#### Review scores ratings trends
#### Average price per night by country and city
#### Tableau visualizations helped uncover seasonality, pricing fluctuations, and regional trends.
# Machine Learning Models Applied
#### Linear Regression – for predicting listing prices based on numerical and categorical attributes.
#### Logistic Regression – for classifying listings as high-rated or low-rated based on ratings and other host attributes.
#### K-Means Clustering – for unsupervised segmentation of listings based on features like amenities and room-type.
# Key Insights
#### Regression models identify price influencers such as city, room type, review scores rating.
#### Entire home/apt is the most common and with the highest prices.
#### Cleaning fee, Security Deposit, and Amenities significantly influence listing categories and price brackets.
