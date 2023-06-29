# Exploratory Data Analysis using Python Pandas

<img src = "Corr_heatmap.png" width="300"> <img src = "Corr_matrix.png" width="600">

I used Python Pandas to perform exploratory data analysis on a publicly available Amazon Delivery dataset on Kaggle. 
In this dataset I 
1. explored Nulls: finding out how many nulls every column had.
2. created another dataframe where null values from numeric columns were replaced with 0 and null values from categoricalv values were replaced with 'no_record'
3. calcualted skewness of every int and float numeric column 
4. used Seaborn to visualize the distribution of the following skewed variables: Delivery_person_Age and Delivery_person_Ratings
5. used '.describe()' to quickly asses which variables have outliers by means of exmamining the distance between minimum / maximum values and the mean.
6. used a correlation heatmap to uncover any linear relationships between variables

Data Source: https://www.kaggle.com/datasets/vikramxd/amazon-business-research-analyst-dataset


# Data Visualization using Tableau

Data Visualization link: https://public.tableau.com/views/AmazonDeliveryExploratoryDataAnalysis/AmazonExploratoryDataAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link

<img src = "Amazon_EDA_dashboard.png" width="800">

