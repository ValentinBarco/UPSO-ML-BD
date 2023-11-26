# Suspense at the Wildlife Preserve: “Organized” Crime?

## Background
Mistford is a mid-size city located to the southwest of the Boonsong Lekagul Wildlife Preserve. The city has a small industrial area with four light-manufacturing endeavors. Mistford and the wildlife preserve are struggling with the possible endangerment of the Rose-Crested Blue Pipit, a locally loved bird. The bird’s nesting pairs seem to have decreased alarmingly, prompting an investigation last year implicating Kasios Office Furniture, a Mistford manufacturing firm. Since the initial investigation, the situation has evolved: Kasios insists that they have done nothing wrong! They assert that grad student Mitch Vogel and his professors are mere media-seekers trying to draw attention away from their lackadaisical research. Kasios presents itself as an extremely eco-friendly organization. They have launched their own very public investigation into the issues raised last year and are reporting very different results! It’s time to apply your data analytics expertise to help illuminate the path to good science.

Mitch Vogel left his work at Mistford College but has not forgotten the Rose-Crested Blue Pipit. Soon after arriving in the small town of Sulev in Northern Europe, Mitch started to see the telltale signs of Methylosmolene damage at the nearby Panteleimon Aviary Sanctuary. Mitch hears from local bird watchers that populations of the Greater Eurasian Red-Throated Pipit have been affected.

Since arriving in Sulev, Mitch also noticed that the local university’s office furniture was built in a nearby EuroKasios factory. Sure enough, EuroKasios is a subsidiary of Kasios International, Inc. – a huge multinational conglomerate that is also the parent company of Kasios Office Furniture back in Mitch’s hometown of Mistford. Mitch is immediately suspicious that EuroKasios is contaminating the aviary Sanctuary and endangering the Greater Eurasian Red-Throated Pipit. Worse yet, Mitch wonders if Kasios International may be contaminating pipit habitats around the world.

Mitch spends weeks reviewing press coverage of Kasios International and public statements made by the company’s CEO. Many of the articles tout the company’s environmentally friendly practices and even talk about recent scientific research that proves the safety of AGOC-3A, an environmentally friendly replacement for Methylosmolene. Mitch is skeptical that the company has halted production and use of Methylosmolene so he contacts the company and asks to meet with representatives from their environmental compliance division.

To his disappointment Mitch is not granted a meeting. Then Mitch receives an anonymous letter from someone who’s willing to help. A fellow pipit lover who works at Kasios International has gathered up a variety of company data and identified a suspicious group within the company. Attached to the letter Mitch receives is a USB drive with phone, email, meeting, and procurement records for Kasios International over the past 2 1/2 years. Mitch wonders if the fate of the Eurasian Pipit lies somewhere in that data. Mitch intends to put this data together to see if the problems with Kasios are much larger than he initially suspected.

Your task, as supported by data analytics that you apply, is to help Mitch determine the organizational structure of the group within Kasios that was referenced by the insider providing Mitch the data. How is it internally connected and is anyone else involved? Use data analytics to explore the available data and develop responses to the questions below. 

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/SuspenseWildlifePreserveOrganizedCrime/data/task3.zip)*

You will find phone, email, meeting, and procurement records for Kasios International over the past 2 1/2 years. The data includes the source of each transaction, the recipient (destination), and the time of the transaction, but the contents of emails or phone calls are not available. There is also a company index that shows the name of all 642,631
individuals in the company and their associated ID numbers. Many of these transactions have been already flagged as suspicious. 

### Goals

1. Using the four large Kasios International data sets, combine the different sources to create a single picture of the company. Characterize changes in the company over time. According to the company’s communications and purchase habits, is the company growing? 
2. Combine the four data sources for group that the insider has identified as being suspicious and locate the group in the larger dataset. Determine if anyone else appears to be closely associated with this group. Highlight which employees are making suspicious purchases, according to the insider’s data.
3. Using the combined group of suspected bad actors you created in question 2, show the interactions within the group over time.
    1. Characterize the group’s organizational structure and show a full picture of communications within the group.
    2. Does the group composition change during the course of their activities?
    3. How do the group’s interactions change over time?
4. The insider has provided a list of purchases that might indicate illicit activity elsewhere in the company. Using the structure of the first group noted by the insider as a model can you find any other instances of suspicious activities in the company? Are there other groups that have structure and activity similar to this one? Who are they? Each of the suspicious purchases could be a starting point for your search. Provide examples of up to two other groups you find that appear suspicious and compare their structure with the structure of the first group. The structures should be presented as temporal not just structural (i.e., the sequence of events—A is followed by B one or two days later—will be important). 

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
    - description and data characterization 
    - answer question 1
    - answer question 2
    - ...

