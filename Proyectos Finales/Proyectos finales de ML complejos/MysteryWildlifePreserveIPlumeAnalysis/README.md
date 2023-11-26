# Mystery at the Wildlife Preserve: Plume Analysis

## Background
Mistford is a mid-size city is located to the southwest of a large nature preserve. The city has a small industrial area with four light-manufacturing endeavors.  Mitch Vogel is a post-doc student studying ornithology at Mistford College and has been discovering signs that the number of nesting pairs of the Rose-Crested Blue Pipit, a popular local bird due to its attractive plumage and pleasant songs, is decreasing! The decrease is sufficiently significant that the Pangera Ornithology Conservation Society is sponsoring Mitch to undertake additional studies to identify the possible reasons. Mitch is gaining access to several datasets that may help him in his work, and he has asked you (and your colleagues) as experts in visual analytics to help him analyze these datasets.

The primary job for Mitch is to determine which (if any) of the factories may be contributing to the problems of the Rose-crested Blue Pipit. Often, air sampling analysis deals with a single chemical being emitted by a single factory. In this case, though, there are four factories, potentially each emitting four chemicals, being monitored by nine different sensors. Further, some chemicals being emitted are more hazardous than others. These factories were supposed to be compliant with recent years’ environmental regulations but Mitch had his doubts that the actual data has been closely reviewed. Substances of concern include:

* *Appluimonia* – In general, most substances that cause odors in the outdoor air are not at levels that can cause serious injury, long-term health effects, or death to humans or animals. However, odors may affect quality of life and sense of wellbeing. Several odor-producing substances, including Appluimonia, are monitored.
* *Chlorodinine* – Corrosives are materials that can attack and chemically destroy exposed body tissues. They might be hazardous in other ways too, depending on the particular corrosive material. An example is the chemical Chlorodinine which is harmful if inhaled or swallowed.
* *Methylosmolene* – This is a trade name for a family of volatile organic solvents. This chemical was strictly regulated in the manufacturing sector. Liquid forms of Methylosmolene are required by law to be chemically neutralized before disposal.
* *AGOC-3A* – New environmental regulations and consumer demand have led to the development of low-VOC (Volatile Organic Compounds) and zero-VOC solvents. Most manufacturers now use one or more low-VOC substances and Mistford’s plants have wholeheartedly signed on. These new solvents, including AGOC-3A, are less harmful to human and environmental health.

Your task, as supported by data analytics that you apply, is to detangle the data to help Mitch determine where problems may be. Use data analytics to explore the available data and develop responses to the questions below. 

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/MysteryWildlifePreserve/data/task2.zip)*

Mitch discovered that the state government has been monitoring the gaseous effluents from the factories through a set of sensors, distributed around the factories, and set between the smokestacks, the city of Mistford and the nature preserve. The state gave Mitch access to their air sampling data, meteorological data, and locations map. Data includes meteorological data that provided wind speed and direction for certain periods of time and sensor data for three months’ worth of readings with the chemical detected, the sensor id, the reading in parts per million, and the
date/time. 

### Goals

1. Characterize the sensors’ performance and operation. Are they all working properly at all times? Can you detect any unexpected behaviors of the sensors through analyzing the readings they capture?
2. Now turn your attention to the chemicals themselves. Which chemicals are being detected by the sensor group? What patterns of chemical releases do you see, as being reported in the data? 
3. Which factories are responsible for which chemical releases? Carefully describe how you determined this using all the data you have available. For the factories you identified, describe any observed patterns of operation revealed in the data.

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
    - description and data characterization 
    - answer question 1
    - answer question 2
    - ...

