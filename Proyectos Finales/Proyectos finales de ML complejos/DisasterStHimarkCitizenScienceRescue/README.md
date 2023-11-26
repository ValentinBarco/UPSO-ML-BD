# Disaster at St. Himark!: Citizen Science to the Rescue
## Background
St. Himark is a vibrant community located in the Oceanus Sea. Home to the world-renowned St. Himark Museum, beautiful beaches, and the Wilson Forest Nature Preserve, St. Himark is one of the region’s best cities for raising a family and provides employment across a number of industries including the Always Safe Nuclear Power Plant. Well, all that was true before the disastrous earthquake that hits the area during the course of this year’s challenge. Mayor Jordan, city officials, and emergency services are overwhelmed and are desperate for assistance in understanding the true situation on the ground and how best to deploy the limited resources available to this relatively small community.

One of St. Himark’s largest employers is the Always Safe nuclear power plant. The pride of the city, it produces power for St. Himark’s needs and exports the excess to the mainland providing a steady revenue stream. However, the plant was not compliant with international standards when it was constructed and is now aging. As part of its outreach to the broader community, Always Safe agreed to provide funding for a set of carefully calibrated professional radiation monitors at fixed locations throughout the city. Additionally, a group of citizen scientists led by the members of the Himark Science Society started an education initiative to build and deploy lower cost homemade sensors, which people can attach to their cars. The sensors upload data to the web by connecting through the user’s cell phone. The goal of the project was to engage the community and demonstrate that the nuclear plant’s operations were not significantly changing the region’s natural background levels of radiation.

When an earthquake strikes St. Himark, the nuclear power plant suffers damage resulting in a leak of radioactive contamination. Further, a coolant leak sprayed employees’ cars and contaminated them at varying levels. Now, the city’s government and emergency management officials are trying to understand if there is a risk to the public while also responding to other emerging crises related to the earthquake as well as satisfying the public’s concern over radiation.

*Note: reviewing the city description document may be helpful to understanding the landscape and character of the city.*

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/DisasterStHimarkCitizenScienceRescue/data/task2.zip)*

You will find two data files spanning the entire length of the events (12 am on April 6, 2020 to 11:59 pm on April 10, 2020), containing radiation measurements from mobile and static radiation sensors.  We also provide a set of supporting files. Be prepared for missing and corrupted data, skipped timesteps, and other issues. Both radiation measurements and movements may be affected by conditions in the city.

### Goals
Your task, as supported by data analytics that you apply, is to help St. Himark’s emergency management team combine data from the government-operated stationary monitors with data from citizen-operated mobile sensors to help them better understand conditions in the city and identify likely locations that will require further monitoring, cleanup, or even evacuation. Will data from citizen scientists clarify the situation or make it more uncertain? Use data and visual analytics to develop responses to the questions below. 

1. Visualize radiation measurements over time from both static and mobile sensors to identify areas where radiation over background is detected. Characterize changes over time.

2. Use data analytics to represent and analyze uncertainty in the measurement of radiation across the city.
    1. Compare uncertainty of the static sensors to the mobile sensors. What anomalies can you see? Are there sensors that are too uncertain to trust?
    2. Which regions of the city have greater uncertainty of radiation measurement? Use data analytics to explain your rationale.
    3. What effects do you see in the sensor readings after the earthquake and other major events? What effect do these events have on uncertainty?

3. Given the uncertainty you observed in question 2, are the radiation measurements reliable enough to locate areas of concern?
    1. Highlight potential locations of contamination, including the locations of contaminated cars. Should St. Himark officials be worried about contaminated cars moving around the city?
    2. Estimate how many cars may have been contaminated when coolant leaked from the Always Safe plant. Use data analysis of radiation measurements to determine if any have left the area.
    3. Indicated where you would deploy more sensors to improve radiation monitoring in the city. Would you recommend more static sensors or more mobile sensors or both? Use your analysis of radiation measurement uncertainty to justify your recommendation.

4. Summarize the state of radiation measurements at the end of the available period. Use your data analysis approaches to suggest a course of action for the city. Use analytics to compare the static sensor network to the mobile sensor network. What are the strengths and weaknesses of each approach? How do they support each other?

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
- description and data characterization 
- answer question 1
- answer question 2
- ...
