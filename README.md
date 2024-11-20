# Flight-Delay-Dashboard
# Flight Delay and Cancellation Dataset Analysis (2019–2023)

This project analyzes flight delay and cancellation data from August 2019 to August 2023, sourced from the U.S. Department of Transportation, Bureau of Transportation Statistics. The dataset consists of approximately 29 million flight records and offers a comprehensive look into patterns of delays, cancellations, and operational disruptions across the U.S. airline industry.

## Dataset Overview

The dataset contains flight-level data on delays, cancellations, and various operational metrics for U.S. airlines. The analysis focuses on identifying trends, predicting disruptions, and providing insights into airline performance and operational efficiency.

### Sample Data

The dataset contains 29 million records, with a subset of 3 million rows available for analysis. Each record represents a single flight and includes the following key variables:

### Key Variables

#### 1. Flight Information:
- `FL_DATE`: Flight date
- `AIRLINE`, `AIRLINE_CODE`: Airline name and code
- `FL_NUMBER`: Unique flight number

#### 2. Route Details:
- `ORIGIN`, `ORIGIN_CITY`: Departure airport and city
- `DEST`, `DEST_CITY`: Arrival airport and city
- `DISTANCE`: Distance between origin and destination (miles)

#### 3. Time Metrics:
- `CRS_DEP_TIME`: Scheduled departure time
- `DEP_TIME`: Actual departure time
- `DEP_DELAY`: Departure delay (minutes)
- `WHEELS_OFF`: Time when the plane left the ground
- `WHEELS_ON`: Time when the plane landed
- `CRS_ARR_TIME`, `ARR_TIME`: Scheduled and actual arrival times
- `ARR_DELAY`: Arrival delay (minutes)
- `CRS_ELAPSED_TIME`, `ELAPSED_TIME`: Scheduled and actual flight duration

#### 4. Disruption Information:
- `CANCELLED`: Whether the flight was canceled
- `CANCELLATION_CODE`: Reason for cancellation (e.g., weather, carrier issues)
- `DIVERTED`: Whether the flight was diverted

#### 5. Delay Attributions:
- `DELAY_DUE_CARRIER`: Delay caused by the airline
- `DELAY_DUE_WEATHER`: Weather-related delay
- `DELAY_DUE_NAS`: Delay caused by the National Aviation System (NAS)
- `DELAY_DUE_SECURITY`: Security-related delays
- `DELAY_DUE_LATE_AIRCRAFT`: Delays due to late-arriving aircraft

## Purpose and Applications

This dataset is intended for structured data analysis with applications including:

- **Exploratory Analysis**: Understanding trends in delays, cancellations, and disruptions over time.
- **Time-Series Analysis**: Investigating seasonal or annual fluctuations in delays.
- **Predictive Modeling**: Building machine learning models to predict delays or cancellations.
- **Operational Insights**: Identifying bottlenecks and inefficiencies in flight operations.

## Key Analytical Questions

- How does weather-related delay vary across different flight times (elapsed time)?
- How are airlines distributed in the dataset? Which airlines have the largest share of flights?
- Which airlines have the most delays attributed to carrier-related issues?
- What is the average departure delay for each airline, and which airlines perform best and worst?
- How does arrival delay change with the distance of a flight?
- Which airlines have the highest number of flight cancellations, and how does this compare across the industry?
- How does the cumulative departure delay change over time? Are there identifiable trends?

## Dashboard

The project includes an interactive dashboard that provides:

- **Operational Efficiency**: Insights into carrier-related delays, weather mitigation strategies, and NAS-related disruptions.
- **Weather Mitigation**: Key weather-related delays and their impact on flight operations.
- **Infrastructure & Operational Bottlenecks**: Areas of inefficiency in the National Aviation System (NAS) and airport infrastructure.
- **Flight Performance**: Airlines' performance metrics, including on-time performance and delays.
- **Customer Satisfaction**: Insights into how delays and cancellations affect customer experience and airline reputations.
- **Environmental Impact**: Visualizing how inefficiencies in flight operations impact fuel consumption and contribute to sustainability goals.

### Dashboard Features

- **Visualizations** of delays, cancellations, and attributions by airline, city, and date.
- **Trends** showing seasonal and yearly variations in delays and cancellations.
- **Comparison tools** for airlines to benchmark their performance and operational efficiency.
- **Resource Allocation Insights**: Identifying areas where airlines can optimize schedules, crew deployment, and infrastructure investments.

## Operational Insights

1. **Carrier-related Issues**: A key driver of cancellations, highlighting the need for better operational processes, maintenance, and crew management.
2. **Weather-Related Delays**: Demonstrates the importance of investing in weather forecasting tools and adaptable scheduling to minimize weather impacts.
3. **Infrastructure Bottlenecks**: Shows the need for improved air traffic control and airport facility management to reduce NAS-related delays.
4. **Flight-Specific Trends**: Identifies specific flight numbers and routes that consistently experience delays, enabling airlines to target problem areas.
5. **Seasonal & Time-based Trends**: Understanding how delays change over the course of the year and across different times of day.
6. **Market Dynamics**: Provides insights into the competitive positioning of airlines based on performance and network size.



