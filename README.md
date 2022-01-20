# Hotel Data: Cleaning and Vizualization

In this project we take real [data](https://www.kaggle.com/jessemostipak/hotel-booking-demand) from a hotel in order to make insightful vizualizations.
But first thing needs to be done is to clean the file hotel_booking_data.xlsx. You achieve it by running cleanup.ipynb, which yield the cleaned file cleaned.xlsx. Here´s what happen during the cleanup:

###### Replace the missing data in columns 'company' and 'agent' with 'Nonexistent'

![q1](https://github.com/Rodrigo663/hotel-data/blob/main/assets/change.png)

###### Dropping the rows where the value for column 'country' is missing

![q1](https://github.com/Rodrigo663/hotel-data/blob/main/assets/change2.png)

## The Vizualizations

After the cleanup you can run vizualization.ipynb to get the insights:

###### General Costumers Statistics 


![pie_chart](https://github.com/Rodrigo663/hotel-data/blob/main/figures/pie_chart.png)


###### How Different Countries Choose Their Meals


![count_plot](https://github.com/Rodrigo663/hotel-data/blob/main/figures/count_plot.png)


**THE MEALS**

- BB – Bed & Breakfast;
- HB – Half board (breakfast and one other meal – usually dinner);
- SC – no meal package;
- FB – Full board (breakfast, lunch and dinner);



###### Range of Values for ADR by country


![box_plot](https://github.com/Rodrigo663/hotel-data/blob/main/figures/box_plot.png)


And that´s basically it 😊
