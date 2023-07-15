# hawaii_airbnb
# Airbnb Data Analysis Project

![](https://static.trip101.com/main_pics/185485/medium.jpg)

This project focuses on performing basic data analysis and science on the Airbnb data from Hawaii. The goal is to gain insights and extract useful information from the dataset.

### Question we will ask:
- what can we learn about different hosts and areas?
- what can we learn from predictions? (ex. locations, price, reviews, etc.)
- which hosts are the busiest and why?
- is there any noticable different of traffice among different areas and what could be the reason for it?

### KPIs we want to show:
- **Occupancy Rate**: divide the total number of occupied nights by the total number of available nights and multiply by 100.
- **Average Daily Rate (ADR)**: divide the total revenue generated by the total number of occupied nights.
- **Revenue**: Multiply the ADR by the number of occupied nights to calculate the revenue.
- **Guest Satisfaction**: You can calculate average review scores for aspects like cleanliness, communication, check-in, location, and value. Average these scores to determine the overall guest satisfaction rating.
- **Booking Lead Time**: Calculate the difference between the booking date and the check-in date for each booking and determine the average lead time.
- **Return on Investment(ROI)**: subtracting the total expenses (such as maintenance, cleaning fees, and utilities) from the total revenue and dividing the result by the total expenses. Multiply by 100 to get the ROI percentage.
- **Average Length of Stay**: Calculate this by dividing the total number of occupied nights by the total number of bookings.
- **Cancellation Rate**: Divide the number of canceled bookings by the total number of bookings and multiply by 100 to calculate the cancellation rate.
- **Net Promoter Score (NPS)**:Calculate NPS by subtracting the percentage of detractors (those unlikely to recommend) from the percentage of promoters (those likely to recommend).


## Dataset

The dataset used in this project consists of Airbnb listings and related information for Hawaii. It includes details such as property information, host information, pricing, availability, and guest reviews.

The dataset can be obtained from [this link.](http://insideairbnb.com/get-the-data/).

press control + f and look for 'hawaii'

## Requirements

To run the project and reproduce the analysis, you need the following dependencies:

Data Manipulation:
- Python (version 3.11.4)
- Jupyter Notebook
- Pandas
- NumPy

Visualisation Applications:
- Power BI
- Tableau
- etc.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Jack-Merrett/airbnb-data.git
