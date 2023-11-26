# Return to Kronos

## Background

After the successful resolution of the [kidnapping at GAStech’s Abila](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/TheKronosIncident), Kronos office, GAStech officials determined that Abila offices needed a significant upgrade. At the end of 2015, the growing company moved into a new, state-of-the-art three-story building near their previous location. Even though the employee morale rose somewhat with the excitement of the new building, there are still a few disgruntled employees in the company.

The new office is built to the highest energy efficiency standard, but as with any new building, there are still several HVAC issues to work out. The building is divided into several HVAC (heating, ventilation, and air conditioning) zones. Each zone is instrumented with sensors that report building temperatures, heating and cooling system status values, and concentration levels of various chemicals such as carbon dioxide (abbreviated CO2) and hazium (abbreviated Haz), a recently discovered and possibly dangerous chemical. CEO Sten Sanjorge Jr. has read about hazium and requested that these sensors be included. However, they are very new and very expensive, so GAStech can afford only a small number of sensors.

With their move into the new building, GAStech also introduced new security procedures, which staff members are not necessarily adopting consistently. Staff members are now required to wear proximity (prox) cards while in the building.

The building is instrumented with passive prox card readers that cover individual building zones. The prox card zones do not generally correspond with the HVAC zones. When a prox card passes into a new zone, it is detected and recorded. Most, but not all, areas are still open to staff members even if they forget their prox cards. People are somewhat careless with their prox cards, but some diligent staff members will go to the security desk and pick up a new prox card if their old one is mislaid.

As part of the deal to entice GAStech to move into this new building, the builders included a free robotic mail delivery system. This robot, nicknamed Rosie, travels the halls periodically, moving between floors in a specially designed chute. Rosie is equipped with a mobile prox sensor, which identifies the prox cards in the areas she travels through.

As an expert in data analytics, you have been hired to help GAStech understand its operations data. In this task, you are given two weeks of building and prox sensor data. Can you identify typical patterns  and issues of concern? 

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/ReturntoKronos/data/task1.zip)*

In addition to the static sensor data, the data includes lectures from a mobile sensor known as *Rosie the Robot*. Rosie was a mail-delivering robot that traversed the entire building twice a day. Employees only knew her as a mail delivery system, but the GAStech management had installed an on-board prox card reader, so that she recorded prox cards that appeared within 5 meters of the reader. Data from Rosie, combined with other data, allowed contestants to hypothesize the insider threat employee, as well as how and when inappropriate activities were occurring.  The following data was provided for this task:

* A building layout for the GAStech offices, including the maps of the prox zones and the HVAC zones
* A current list of employees, roles, and office assignments
* A description of the data formats and fields provided
* Proximity sensor data for each of the prox zone regions
* Proximity sensor data from Rosie the mobile robot
* HVAC sensor readings and status information from each of the building’s HVAC zones
* *Hazium* readings from four sensors (hazium is a fictitious chemical that has become a recent concern on the island of Kronos. Not much is known about its effects, but it is suspected that Hazium is not good for people).

### Goals

You will be asked to answer the following types of questions:

1. What are the typical patterns in the prox card data? What does a typical day look like for GAStech employees?
2. Describe up to ten of the most interesting patterns that appear in the building data. Describe what is notable about the pattern and explain its possible significance.
3. Describe up to ten notable anomalies or unusual events you see in the data. Prioritize those issues that are most likely to represent a danger or a serious issue for building operations.
4. Describe up to five observed relationships between the proximity card data and building data elements. If you find a causal relationship (for example, a building event or condition leading to personnel behavior changes or personnel activity leading to building operations changes), describe your discovered cause and effect, the evidence you found to support it, and your level of confidence in your assessment of the relationship.

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
- description and data characterization 
- answer question 1
- answer question 2
- ...

