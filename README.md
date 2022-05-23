# Southern_Nevada_Restaurants_Inspection_Grading_Prediction
Prediction of the Health Inspection Grade of Southern Nevada Restaurants

Introduction:

What I set out to do in this exercise is to explore the data on restaurant inspections provided by the Las Vegas Open Data Portal and build a predictive model to predict the inspection grades of the restaurants. After the predictive exercise, I explored the concept of data drift using the dataset I downloaded after some time. I compared the original dataset against the more recent dataset and explored the data drift using the open source library Evidently, visualizing them in a dashboard. I made some assumptions about why the data has changed, which explain the changes that I consequently made to my model. 

Background: 

The Southern Nevada Health District enforces health code regulations for restaurants in the Southern Nevada region which includes cities Las Vegas and Henderson. The food inspectors use the food inspection guidelines to assign the number of demerits for each restaurant and sum them up to determine whether the restaurant is assigned grade A, B, or C. This particular dataset contains inspection results for over 15,000 restaurants, bars, and other facilities that serve food to the public. This exercise aims to use the features available in the dataset to predict the outcome of the restaurant’s next inspection, which is the column NEXT_GRADE_C_OR_BELOW. In real life, receiving the grade below C would require the restaurant to close due to ‘Imminent Health Hazard.’ 

Data Source: 

https://opendataportal-lasvegas.opendata.arcgis.com/datasets/restaurant-inspections-open-data/explore
