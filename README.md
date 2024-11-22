## Creator
This project is made by [Abdillah Ilham](https://github.com/ailham4321/) and [Rahmannuaji Satuhu](https://github.com/rahmannuaji).

## Backgrounder
A retail company (namely XYZ) wants to upsale their retail sales by doing targeted campaign.

## Findings
XYZ campaigns doesn't do much on their winnings. At most, only 5% of the total customer actually accepted the campaigns. Moreover, the behaviour of user tends to only accept one campaign out of 6 campaigns that has been done. So clearly this can be somehow optimized

## Methods
We propose an RFM analysis by categorizing Recency, Frequency, and Monetary.
1. Recency: we use binning with 3 categories.
2. Frequency: we use simple K-Means clustering with 4 clusters.
3. Monetary: we use simple K-Means clustering with 3 clusters.
Out of all this R, F, and M, we then categorize by subjectivity regarding our business understanding to 4 categories:
1. Champion, are customers with highest values.
2. Potential Loyalists, are customer that may be beneficial for company.
3. At Risk, are customers that is beneficial but at risk of churning.
4. Low Values, are the least beneficial for the company.

## Results
Ot of those segments, we suggest that:
1. For Champions: offer exclusive discounts, VIP access, or loyalty programs to maintain their loyalty.
2. For Potential Loyalists: offer incentives such as discounts on the next purchase or free shipping.
3. For At Risk: send reactivation emails with special offers, such as "We Miss You" campaigns and also showcase new products, updates, or services they might have missed.
4. For Low Values: offer low-barrier incentives like small discounts or free trials to re-engage.

## Additional
We also created dashboard to look at the big picture of this company as well as the RFM Segmentation results, accessible [here](https://app.powerbi.com/view?r=eyJrIjoiNTA4Y2VhNTctMWJlZS00MGUzLTk2ZTQtYWMwZmQ0OTVkNGRkIiwidCI6IjFkNTE2OWFjLWM3Y2ItNDI3NS05NzY0LWJmOGM5YzM2NGE0YyIsImMiOjEwfQ%3D%3D)

## Acknowledment
The dataset used in this project is derived from [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) and is publicly available. We like to thanks all the people that has provided the dataset.
