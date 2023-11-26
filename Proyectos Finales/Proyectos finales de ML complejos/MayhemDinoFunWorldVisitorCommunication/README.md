# Mayhem at DinoFun World: Visitor Communication

## Background
DinoFun World is a typical modest-sized amusement park, sitting on about 215 hectares and hosting thousands of visitors each day. It has a small town feel, but it is well known for its exciting rides and events.

One event last year was a weekend tribute to Scott Jones, internationally renowned football (“soccer,” in US terminology) star. Scott Jones is from a town nearby DinoFun World. He was a classic hometown hero, with thousands of fans who cheered his success as if he were a beloved family member. To celebrate his years of stardom in international play, DinoFun World declared *“Scott Jones Weekend”*, where Scott was scheduled to appear in two stage shows each on Friday, Saturday, and Sunday to talk about his life and career. In addition, a show of memorabilia related to his illustrious career would be displayed in the park’s Pavilion.

However, the event did not go as planned. Scott’s weekend was marred by crime and mayhem perpetrated by a poor, misguided and disgruntled figure from Scott’s past.

While the crimes were rapidly solved, park officials and law enforcement figures are interested in understanding just what happened during that weekend to better prepare themselves for future events. They are interested in understanding how people move and communicate in the park, as well as how patterns changes and evolve over time, and what can be understood about motivations for changing patterns.

You have access to the in-app communication data over the three days of the Scott Jones celebration. This includes communications between the paying park visitors, as well as communications between the visitors and park services. In addition, the data also contains records indicating if and when the user sent a text to an external party. Use analytics to explore and analyze the available data and develop responses to the questions below. 

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/MayhemDinoFunWorldVisitorCommunication/data/task2.zip)*

The data for this task consists of three days worth of communications from Friday through Sunday. The data fields were a timestamp, the originator’s ID, the recipient’s ID, and the park area from which the message was sent. As can be seen in the shading of the map, the park is broken up into five themed areas: the Entry Corridor, Kiddie Land, Tundra Land, Wet Land, and Coaster Alley. So, while these locations were not precise, they indicate general geo-coordinate information for the analyses. There is also some auxiliar information that provide extra context (i.e. map, park website, news article).

### Goals

You are asked to characterize dominant communication IDs, interesting communication patterns, and suspicious patterns that could contribute to the analysis of the crime. Specifically: 

1. Identify groups that stand out for their large volumes of communication. 
    1. Characterize the communication patterns you see.
    2. Based on these patterns, what do you hypothesize about these IDs?

2. Describe up to 10 communications patterns in the data. Characterize who is communicating, with whom, when and where. If you have more than 10 patterns to report, please prioritize those patterns that are most likely to relate to the crime.

3. From this data, can you hypothesize when the vandalism was discovered? Describe your rationale.

To characterize users of the communications facility pay attention to revealing patterns other than IDs. We do not specify any characteristics for patterns we want you to report, but be aware that patterns related to the incident __are present__ in the data. Some innocuous patterns include group leaders sending bulk messages to their groups to request meetups or to communicate an interesting bit of information. Some of the message recipients responded. 

The pattern was repeated at other times during the day. When people were standing in a ride queue or at a food and drink attraction, they had an increased possibility of making new friends with people nearby who did not accompany them to the park. They could communicate with new friends during the rest of their time in the park. There was an increased likelihood that people would send external messages when Scott Jones was in the park (8:45-11:35 each day and 13:45- 16:30 on Friday and Saturday), specifically if they were near Scott as he traveled through the park. Some communications patterns were associated with the crime. For example, there was an increase in messages among group members, to the help desk, and to external contacts when the Scott Jones memorabilia vandalism was discovered.

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
- description and data characterization 
- answer question 1
- answer question 2
- ...

