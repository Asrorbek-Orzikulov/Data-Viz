# Yelp Dashboard - Best States for Dining and Doing Sports

![image](https://user-images.githubusercontent.com/77324692/161134884-62c249ba-8cc4-4693-9216-ae4ecc2c68bf.png)

### Introduction
In this project, we created a Tableau Public interactive dashboard which allows users to visualize all the restaurants and gyms throughout United States of America,
and explore all the accessibility options available categorized by states, and also provides the evolution of reviews throughout the months for the year 2021. 
This dashboard can help business entrepreneurs to spot inadequecy of gyms/restaurants business places which can open up new business opportunities, it can also act
as a guide to people looking for highly accessible restraurants and gyms near the place of interest while searching for an accommodation, and many others. 

### Preprocessing
We've preprocessed the JSON data taken from https://www.yelp.com/dataset inorder to create a processed excel file which can be integreated easily with Tableau Public.
If interested in the preprocessing steps, you can checkout preprocessing.ipynb for more info. Some of the preprocessing steps include, choosing a time window to study, 
removing unneccessary columns to reduce the massive dataset size, create new feature columns to indicate accessibility options for each of the business places.

### Creating dashboard
Utilizing Tableau Public software, we were able to recreate our sketch by creating worksheets for each of the charts, and later combining them into a dashboard which 
we've published on the Tableau public database. Please visit the link https://public.tableau.com/app/profile/asrorbek/viz/YelpReviews_16487524305780/MapFull?publish=yes
to access the dashboard created. You can also find the tableau workbook in this repo for offline viewing of the dashboard.

### Future Scope
In the future, we wish to include more categories of business places to the dashboard which will provide users with more options to choose, and visualize from. 

![Yelp_Logo svg](https://user-images.githubusercontent.com/77324692/161137048-6d28c2a4-ab30-4215-bba1-b9248d371b77.png)
