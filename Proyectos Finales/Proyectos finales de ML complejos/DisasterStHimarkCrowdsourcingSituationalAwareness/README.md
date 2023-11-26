# Disaster at St. Himark!: Crowdsourcing for Situational Awareness

## Background
St. Himark is a vibrant community located in the Oceanus Sea. Home to the world-renowned St. Himark Museum, beautiful beaches, and the Wilson Forest Nature Preserve, St. Himark is one of the region’s best cities for raising a family and provides employment across a number of industries including the Always Safe Nuclear Power Plant. Well, all that was true before the disastrous earthquake that hits the area during the course of this year’s challenge. Mayor Jordan, city officials, and emergency services are overwhelmed and are desperate for assistance in understanding the true situation on the ground and how best to deploy the limited resources available to this relatively small community.

St. Himark has been hit by an earthquake, leaving officials scrambling to determine the extent of the damage and dispatch limited resources to the areas in most need. They quickly receive seismic readings and use those for an initial deployment but realize they need more information to make sure they have a realistic understanding of the true conditions throughout the city.

In a prescient move of community engagement, the city had released a new damage reporting mobile application shortly before the earthquake. This app allows citizens to provide more timely information to the city to help them understand damage and prioritize their response. In this mini-challenge, use app responses in conjunction with shake maps of the earthquake strength to identify areas of concern and advise emergency planners. Note: the shake maps are from April 6 and April 8 respectively.

With emergency services stretched thin, officials are relying on citizens to provide them with much needed information about the effects of the quake to help focus recovery efforts.

By combining seismic readings of the quake, responses from the app, and background knowledge of the city, help the city triage their efforts for rescue and recovery.

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/DisasterStHimarkCrowdsourcingSituationalAwareness/data/task1.zip)*

The data includes one (CSV) file spanning the entire length of the event, containing (categorical) individual reports of shaking/damage by neighborhood over time. Reports are made by citizens at any time, however, they are only recorded in 5-minute batches/increments due to the server configuration. Furthermore, delays in the receipt of reports may occur during power outages. Also included are two shakemap (PNG) files which indicate where the corresponding earthquakes' epicenters originate as well as how much shaking can be felt across the city.

### Goals
1. Emergency responders will base their initial response on the earthquake shake map. Use data analytics to determine how their response should change based on damage reports from citizens on the ground. How would you prioritize neighborhoods for response? Which parts of the city are hardest hit? 
2. Use data and visual analytics to show uncertainty in the data. Compare the reliability of neighborhood reports. Which neighborhoods are providing reliable reports? Provide a rationale for your response.
3. How do conditions change over time? How does uncertainty in change over time? 

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
- description and data characterization 
- answer question 1
- answer question 2
- ...
