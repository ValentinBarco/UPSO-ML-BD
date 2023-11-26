#  The Kronos Incident: Geospatial-Temporal Patterns of Life Analysis

## Background
In January, 2014, the leaders of GAStech are celebrating their new-found fortune as a result of the initial public offering of their very successful company. In the midst of this celebration, several employees of GAStech go missing. An organization known as the Protectors of Kronos (POK) is suspected in the disappearance, but things may not be what they seem.

Many of the Abila, Kronos-based employees of GAStech have company cars which are approved for both personal and business use. Those who do not have company cars have the ability to check out company trucks for business use, but these trucks cannot be used for personal business. Employees with company cars are happy to have these vehicles, because the company cars are generally much higher quality than the cars they would be able to afford otherwise. However, GAStech does not trust their employees. Without the employees’ knowledge, GAStech has installed geospatial tracking software in the company vehicles. The vehicles are tracked periodically as long as they are moving.

This vehicle tracking data has been made available to law enforcement to support their investigation. Unfortunately, data is not available for the day the GAStech employees went missing. Data is only available for the two weeks prior to the disappearance. In addition to the vehicle data, law enforcement has been given access to the personal and business credit and debit card transactions for the local GAStech employees for the two weeks preceding the kidnapping. Many of the GAStech employees also use loyalty cards to gain discounts or extra benefits at the businesses they patronize, and law enforcement has been given access to two weeks of this loyalty card data as well.

As a data scientist expert assisting law enforcement, your mission is to make sense of this data to identify suspicious patterns of behavior and to prioritize which of these may be related to the missing staff members. You must cope with uncertainties that result from missing, conflicting, and imperfect data to make recommendations for further investigation.

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/TheKronosIncidentGeospatial/data/task2.zip)*
As an analyst, you have the following data at your disposal:

1. A list of vehicle assignments by employee, in CSV format (`car-assignments.csv`)
1. Employee Last Name
2. Employee First Name
3. Car ID (integer)
4. Current Employment Type (Department; categorical)
5. Current Employment Title (job title; categorical)
2. ESRI shapefiles of Abila and Kronos (in the Geospatial folder)
1. A CSV file of vehicle tracking data (`gps.csv`)
2. Timestamp
3. Car ID (integer)
4. Latitude
5. Longitude
3. A CSV file containing loyalty card transaction data (`loyalty_data.csv`)
1. Timestamp
2. Location (name of the business)
3. Price (real)
4. FirstName (first name of the card holder)
5. LastName (last name of the card holder)
4. A CSV file containing credit and debit card transaction data (`cc_data.csv`)
1. Timestamp
2. Location (name of the business)
3. Price (real)
4. FirstName (first name of the card holder)
5. LastName (last name of the card holder)
A tourist map of Abila with locations of interest identified, in JPEG format (`map-tourist.jpg`)

### Goals

1.  Describe common daily routines for GAStech employees. What does a day in the life of a typical GAStech employee look like? 

2. Identify up to twelve unusual events or patterns that you see in the data. If you identify more than twelve patterns during your analysis, focus your answer on the patterns you consider to be most important for further investigation to help find the missing staff members. For each pattern or event you identify, describe
1. What is the pattern or event you observe?
2. Who is involved?
3. What locations are involved?
4. When does the pattern or event take place?
5. Why is this pattern or event significant?
6. What is your level of confidence about this pattern or event? Why?

3. Like most datasets, the data you were provided is imperfect, with possible issues such as missing data, conflicting data, data of varying resolutions, outliers, or other kinds of confusing data. Considering data is primarily spatiotemporal, describe how you identified and addressed the uncertainties and conflicts inherent in this data to reach your conclusions in questions 1 and 2.

In order to use this data, you will require skills in geospatial-temporal analysis, along with the ability to combine various types of data in sensible ways. The GPS data was extracted from the cars for the two weeks period prior to the kidnapping, but not including the kidnapping day itself.  GASTech also issued company debit/credit cards that could be used for personal spending, and many employees had loyalty cards for restaurants and shops around Abila city. Analyzing the combined data sources could reveal clues about the kidnapping and the GASTech employees who may have participated in this activity.  You need to be aware that some GPS readings may be skewed for some vehicles. In addition, particular locations may exhibit deviations in the times at which they post their card transactions. Similarly, in some cases, the transactions were logged in batches once per day; in some locations transactions may be delayed, creating the appearance of individuals shopping in the middle of the night. 

Focus your work on identifying regular patterns. For example, credit card data may contain typical charges like GASTech employees preferring to use their debit and loyalty cards at coffee houses. Deviations from these patterns might indicate suspicious activities or just non-conforming patterns by individuals. Hypotheses about suspicious activities need to be supported by evidence and/or reasoning from data. Look for anomalies such as a credit card charge occurring for an employee while the GPS track indicates a different location for their assigned vehicle. 

Map data, including shape files of Abila city streets and a visitor’s map of the city sites and shops, are provided to you as an additional support to understand patterns of life. For example, even though employees’ home addresses were not provided, patterns of life analysis may reveal where they spent their evening hours, typically indicating their home address. Regular gatherings at what appeared to be residences, but not corresponding to any employee’s home address could suggest different hypotheses.

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
- description and data characterization 
- answer question 1
- answer question 2
- ...
