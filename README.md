# Exploring the Impact of Autovabaduse puiestee on Tartu's Smart Bike Usage

**Computer Science, University of Tartu, Tartu, Estonia**

**Sadig Hasanzade**

+372 5380 3703, sadig.hasanzade@ut.ee

---

## Introduction

Urban events and initiatives often aim to encourage sustainable transportation modes, such as cycling, to reduce traffic congestion and promote healthier lifestyles. One such initiative is the "Autovabaduse puiestee" (Car-Free Avenue) event held in Tartu, which temporarily transforms a central street into a pedestrian-friendly zone. This study explores the impact of this event on the usage of Tartu's smart bike-sharing system. The event is held from 29th June until 6th August 2023.

The map below illustrates the central street in Tartu that is transformed into a pedestrian-friendly zone during the 'Autovabaduse puiestee' event. This area becomes car-free, encouraging cycling and other sustainable modes of transportation.

## Objectives

The primary objective of this project is to analyze the change in trip counts from different bike stations before and after the event month. Specifically, the analysis focuses on ten stations closest to the event location. By examining these stations, the study aims to understand whether the event influenced biking behavior differently nearer to the event venue.

## Dataset

The dataset from Tartu's smart bike-sharing system captures detailed records of bike trips, including route codes, cycle numbers, user IDs, and timestamps for unlocking and locking bikes. It also includes start and end stations, trip lengths in kilometers, durations in minutes, cycle types, and membership details. Demographic information such as the user's year of birth is included while maintaining anonymity.

The dataset spans 12 months, covering periods before, during, and after the "Autovabaduse puiestee" event. Preprocessing steps ensure data accuracy by cleaning duplicates, filtering relevant trips from key stations, and aggregating trip counts and durations by month and start station. This processed data enables a thorough analysis of changes in bike usage patterns, assessing the event's impact on smart bike utilization in Tartu.

## Methods

This study employed a detailed analytical approach to evaluate the impact of the "Autovabaduse puiestee" event on Tartu's smart bike-sharing system. The analysis covered a period from May to September, focusing on trip counts and durations across various stations to determine any significant changes in usage patterns before, during, and after the event.

### Preprocessing

The initial dataset included route codes, cycle numbers, user IDs, timestamps, station names, trip durations, and user demographics. The first step involved converting the time fields from string format to datetime format to ensure accurate time-based calculations and comparisons. Additional columns were created, such as combined datetime columns for both the start and end of each trip, enabling precise duration calculations. Rows with missing or invalid data, such as negative trip durations or inconsistent timestamps, were identified and removed to maintain data integrity.

### Analysis

The analysis was conducted in two main parts, focusing on different aspects of bike usage across various stations and time periods from May to September.

#### Analysis of Nearest Stations to Event Location

The second part focused on stations nearest to the "Autovabaduse puiestee" event location. Ten stations closest to the event site were selected to determine whether their proximity influenced bike usage patterns. Monthly trip counts for these nearest stations were calculated and compared, grouping the data by station and month. This analysis aimed to understand the localized impact of the event on bike usage.

#### Analysis of Trip Durations for Nearest Stations

The third part examined how trip durations changed at stations near the event location over the specified months. For the ten nearest stations, the total duration of all trips was summed for each month, providing a measure of bike usage duration. The data was grouped by station and month, with trip durations aggregated. Monthly sums of total durations for all ten stations were compared to identify significant changes in trip durations associated with the event. This analysis provided insights into whether the event influenced the frequency and duration of bike usage.

### Detailed Steps

To ensure a robust analysis, the dataset was meticulously prepared. Time fields were converted to datetime format, and invalid rows were removed. The ten stations nearest to the event location were selected, and their monthly trip counts and durations were analyzed to determine any significant changes.

This structured methodology enabled a comprehensive examination of changes in bike usage patterns before, during, and after the "Autovabaduse puiestee" event. By focusing on trip counts and durations across different sets of stations, the study provided valuable insights into the event's impact on Tartu's smart bike-sharing system, contributing to a better understanding of how urban events can influence sustainable transportation initiatives.

## Results

This section presents the findings from the analysis of Tartu's smart bike-sharing data before, during, and after the "Autovabaduse puiestee" event, focusing on trip counts and durations across different stations. The analysis compares data from May to September and evaluates changes in bike usage patterns.

This experiment takes 10 nearest stations and analyzes how traffic changes before, during and after the event. (Figure 2 June to July, Figure 3 July to August, Figure 4 May to July, Figure 5 July to September)

From the above graphs, we can say that there is not any exact pattern that we can say the event has an effect on. Visit counts at nearest stations change differently; any Ups and Downs are not observed before and after event time.

To see how metrics are affected by the event, data is grouped by station name and average of trip duration is calculated. The result of the experiment was similar to previous ones, not any exact pattern was found.

## Conclusion

This study aimed to explore the impact of the "Autovabaduse puiestee" event on Tartu's smart bike-sharing system by analyzing trip counts and durations from May to September. The analysis focused on the ten most visited stations and the ten stations nearest to the event location.

The findings indicate that the event had a limited impact on bike usage. Both trip counts and durations showed minor variations across the months, with no consistent pattern of increased usage attributable to the event. The highest trip counts were observed in June and July, likely due to seasonal factors rather than the event itself. For the most visited stations and those nearest to the event, the data did not show significant changes in bike usage patterns.

These results suggest that while "Autovabaduse puiestee" may have temporarily enhanced the cycling environment, it did not substantially increase overall bike usage. The absence of a clear pattern indicates that short-term events alone may not be sufficient to promote sustainable transportation.

Future efforts to increase bike usage should consider long-term strategies, including infrastructure improvements, public awareness campaigns, and incentives. While the event was a positive step towards creating a bike-friendly environment, more sustained efforts are needed to achieve significant impacts on bike-sharing system usage.

In conclusion, the "Autovabaduse puiestee" event has minimal impact on Tartu's smart bike usage, highlighting the need for ongoing and integrated approaches to foster sustainable transportation habits.

## Links

- [GitHub Repo](https://github.com/sadighasanzade/Autovabaduse-puiestee-effects-research-on-Tartu-smart-bike/tree/main)
- [Event Information](https://tartu.ee/et/autovabaduse-puiestee)
- [Course Information](https://courses.cs.ut.ee/2024/MM/spring)
