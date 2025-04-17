**Big Data Predictive Analytics**  
**Regression & Clustering**

---

The report on "Big Data Predictive Analytics" focuses on predicting Manhattan real estate sales prices using a dataset that spans from August 2012 to August 2013\. This dataset includes various attributes such as square footage, building type, neighborhood, and sale prices.

The research aims to build a predictive model for house selling prices based on relevant dataset attributes. The dataset includes 21 columns detailing aspects like borough, neighborhood, building class, tax class, block, lot, address, and sale details, among others. 

In the initial phase of data cleaning and transformation, the researchers pre-processed the data by handling missing values and converting columns into appropriate formats. The sale prices had non-numeric characters removed, and zero values in critical columns were replaced with NaN. After cleaning, the dataset consisted of 27,395 rows.

During the exploratory phase, the data was analyzed using summary statistics, visualizations, and correlation analysis. Key findings revealed that the average sale price in Manhattan was noteworthy, with Midtown CBD being the most expensive neighborhood and Inwood being the least expensive. The average square footage of homes was around 9,572 sq ft, and the most common property types included luxury hotels and elevator apartments. The correlation matrix indicated strong relationships between certain features, such as GROSS SQUARE FEET and YEAR BUILT, with the sale price.  
![][image1]

![][image2]  
![][image3]  
![][image4]  
![][image5]  
![][image6]  
![][image7]  
![][image8]

In the model-building phase, the researchers developed a linear regression model to predict selling prices. They split the dataset into training and testing sets and evaluated the model using Root Mean Square Error (RMSE) and cross-validation. The initial model showed an R-squared value of 0.163, suggesting it explained only a small portion of the variance in sale prices.  
![][image9]

To enhance the model's performance, the researchers transitioned to a RandomForestRegression model, addressing missing values rather than discarding them. The improved model achieved an R-squared value of 86.8% and an RMSE of 73.54%. Additionally, K-means clustering was employed to create housing clusters, which improved regression model performance. The elbow method determined that four clusters were optimal for the dataset.  
![][image10]  
![][image11]  
![][image12]

Overall, the analysis provided insights into the factors influencing Manhattan's real estate prices and demonstrated the effectiveness of machine learning techniques in predicting housing prices.  
