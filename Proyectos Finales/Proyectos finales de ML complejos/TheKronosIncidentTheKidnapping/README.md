#  The Kronos Incident: The Kidnapping and a Historical Analysis of the Protectors of Kronos

## Background
In January, 2014, the leaders of GAStech are celebrating their new-found fortune as a result of the initial public offering of their very successful company. In the midst of this celebration, several employees of GAStech go missing. An organization known as the Protectors of Kronos (POK) is suspected in the disappearance, but things may not be what they seem.

Your task is to bring law enforcement up to date on the current organization of the POK and how that organization has changed over time, as well as to characterize the events surrounding the disappearance. You are provided with a set of current and historical news reports at your disposal, as well as resumes of numerous GAStech employees and email headers from two weeks of internal GAStech company email. You are being
counted on to bring law enforcement up to date on the current organization of the POK and how that organization has changed over time, as well as to characterize the events surrounding the disappearance.

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/TheKronosIncidentTheKidnapping/data/task1.zip)*

The data provided consists of a collection of text-based files dealing with the kidnapping of the GASTech employees by members of the social movement group POK.  As an analyst, you have the following data at your disposal:

* A map of Kronos
* A chart describing the local GAStech organization, in PDF format.
* A spreadsheet of GAStech employee records, in Microsoft Excel format. The primary worksheet contains the data; the index worksheet contains the data dictionary
* Email headers from two weeks of internal GAStech company email, in comma-separated values (CSV) format
* Resumes and short biographies of many, but not all, of the GAStech employees, in Microsoft Word format
* Historical reports and descriptions of the countries involved, in Microsoft Word format
* Relevant current and historical news reports from multiple domestic and translated foreign sources, in text file format. Because these articles have come from multiple sources and original formats, some of the them may contain corrupted characters, which is typical for this type of data. These corrupted characters should not interfere with your ability to analyze the data.

### Goals

1. Provide a clear analysis of the structure of the Protectors of Kronos network, with supporting evidence.
    1. Who are the leaders?
    2. Who is part of the extended network?
    3. How has the group structure and organization changed over time?
    4. Where are the potential connections between the POK and GAStech?
2. Describe the events of January 20-21, 2014. What is the timeline of events? 
3. Provide at least two possible explanations why the GAStech employees may be missing. What evidence do you have to support each of these explanations?

In order to explore this data, you will need to perform several kinds of data integration activities and analyses to generate hypotheses
about the __missing employees__. The main structure of the POK is described in the two historical reports dated five and ten years ago. Updates can be found in news articles and in some of the other datasets. Your investigation into this text data can be supported by text analytic tools. When analysing emails headers (containing *To*, *From*, *Date*, and *Subject* fields) try to reconstruct some sort of a communication network within the GASTech organization during the period for which data was provided. You should find clues to POK members or sympathizers plus hints at socialization patterns among employees. 

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
    - description and data characterization 
    - answer question 1
    - answer question 2
    - ...
