# Data analysis

Throughout the investigation, I have analysed different data / Different data sets have informed my reporting. 

I have looked at the number of hospital admissions, delayed discharges from hospital, available mental health beds and bed occupancy, and the accommodation status of mental health patients. 

## Delayed discharges 

The [Mental Health Services Monhtly Statistics](https://digital.nhs.uk/data-and-information/publications/statistical/mental-health-services-monthly-statistics), published by NHS Digital, contains data on delayed discharges. Delayed discharges occur when a patient, despite being medically fit to be discharged, cannot be discharged from hospital. This can happen for a number of different reasons.

Mental Health Services Monhtly Statistics include data on monthly delayed discharge days, who the delayed discharge days are attributed to and the reasons for the delayed discharge days. 

At first, I downloaded the CSVs from April 2019 to January 2021 (latest available data) and merged them using the command line 
  *(cat *.csv > MHSDS2019to2020.csv)*
  after navigating with “cd” to the folder containing the CSVs. 

I then analysed the data in R. The script can be found [here](https://github.com/vfillis/mental-health-housing/blob/main/Data%20analysis/MHSDS-admissions-delayed-discharges.Rmd). 

I analysed the data over time, but whenenver there was no change (which was mostly the case) I only used the latest available data in my reporting instead of looking at the figures over time. 

[This is the final data I have used in my article](https://github.com/vfillis/mental-health-housing/blob/main/Data%20analysis/MHSDS-delayed-discharge-reasons.xlsx).

Additionally, the Mental Health Services Monhtly Statistics include data on [monthly hospital admissions](https://github.com/vfillis/mental-health-housing/blob/main/Data%20analysis/MHSDS-England-admissions-discharges.xlsx).

## Number of mental health beds and bed occupancy 

Quarterly bed availability and occupancy data is [published by NHS England](https://www.england.nhs.uk/statistics/statistical-work-areas/bed-availability-and-occupancy/bed-data-overnight/). 

The **Beds Time Series – 1987-88 to 2009-10** and **Beds Time-series 2010-11 onwards** show the development of available mental health beds over time. They were in different formats (one was yearly data and one was quarterly). 

Because of this, I calculated the yearly average out of the quarterly bed statistics. 

Bed availability data is available from 1987/88 and bed occupancy data is available from 2010/11. 

The data can be found [here](https://github.com/vfillis/mental-health-housing/blob/main/Data%20analysis/mental-health-beds-and-occupancy.xlsx). 

## Accommodation status of mental health patients 

I have obtained national data on the accommodation status of patients who are in contact with adult mental health services [through Freedom of Information requests](https://github.com/vfillis/mental-health-housing/tree/main/FOIs/Accommodation%20Code). 

The cleaned data can be found [here](https://github.com/vfillis/mental-health-housing/blob/main/Data%20analysis/FOI-accommodation-status-England.xlsx). 
