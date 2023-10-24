
# Uber Rides Data Analysis

This project involves the analysis of Uber ride data to understand peak service times, availability, and the ratio of cancellations with respect to time. The analysis was conducted using Python, Pandas, and Matplotlib.

## Data

The dataset used in this analysis was obtained from Kaggle and is named "Uber Request Data." The dataset contains information about Uber rides, including the status of the ride, pickup points, pickup and drop-off timestamps, and driver information.

## Analysis

### Data Cleaning

- The dataset was loaded using Pandas, and basic information about the columns was inspected.
- Null values were identified, primarily in the "Driver id" and "Drop timestamp" columns, which occur when rides were either canceled or cars were unavailable.
- The timestamp columns were converted to proper datetime format for further analysis.
- Unnecessary columns such as "year" and "Request timestamp" were removed.

### Data Visualization

- The data was visualized to gain insights into the following aspects:
  - The status of rides based on pickup point (City or Airport).
  - The distribution of ride requests and cancellations by hour of the day.
  - The unavailability of cars at different times, categorized by pickup point.
  - The number of completed trips at different hours, also categorized by pickup point.
  - The comparison of the number of completed trips, cancellations, and unavailability of cars.
  - The identification of drivers with the highest and lowest numbers of cancellations and completed trips.

## Results

- Most ride requests occur during the morning and evening rush hours.
- Cars are often unavailable late at night after 9:00 PM.
- The unavailability of cars at the airport is more prominent in the evening, while in the city, it is more common in the morning.
- The majority of cancellations happen between 4:00 AM and 9:00 AM.

## Conclusion

This analysis provides valuable insights into Uber ride patterns, helping us understand peak service times, unavailability periods, and cancellation trends. The data visualizations make it easier to comprehend the findings.

## Usage

To reproduce the analysis, you can follow the code snippets provided in the Jupyter notebook.

## License

This project is licensed under the [MIT License](LICENSE).
