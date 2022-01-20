# Hotel Data: Cleaning and Vizualization

In this project we take real [data](https://www.kaggle.com/jessemostipak/hotel-booking-demand) from a hotel in order to make insightful vizualizations.
Before we clean the file [hotel_booking_data.xlsx](https://github.com/Rodrigo663/hotel-data/blob/main/hotel_booking_data.xlsx) by running [cleanup.ipynb](https://github.com/Rodrigo663/hotel-data/blob/main/cleanup.ipynb), this way generating a fresh file: [cleaned_data.xlsx](https://github.com/Rodrigo663/hotel-data/blob/main/cleaned_data.xlsx). The cleanup process can be read bellow.

## Replace the missing data in columns 'company' and 'agent' with 'Nonexistent'

![q1](https://github.com/Rodrigo663/hotel-data/blob/main/assets/change.png)

## Dropping the rows where the value for column 'country' is missing

![q1](https://github.com/Rodrigo663/hotel-data/blob/main/assets/change2.png)

## The Visualizations

Now we can run [visualizations.ipynb](https://github.com/Rodrigo663/hotel-data/blob/main/visualizations.ipynb) to get the insights.

## General Costumers Statistics 


![pie_chart](https://github.com/Rodrigo663/hotel-data/blob/main/figures/pie_chart.png)


## How Different Countries Choose Their Meals


**THE MEALS**

- BB – Bed & Breakfast;
- HB – Half board (breakfast and one other meal – usually dinner);
- SC – no meal package;
- FB – Full board (breakfast, lunch and dinner);


![count_plot](https://github.com/Rodrigo663/hotel-data/blob/main/figures/count_plot.png)


## Range of Values for ADR by country


![box_plot](https://github.com/Rodrigo663/hotel-data/blob/main/figures/box_plot.png)


That´s basically it 😊
