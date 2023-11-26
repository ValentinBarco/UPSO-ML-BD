# Mayhem at DinoFun World: Visitor Movement

## Background
DinoFun World is a typical modest-sized amusement park, sitting on about 215 hectares and hosting thousands of visitors each day. It has a small town feel, but it is well known for its exciting rides and events.

One event last year was a weekend tribute to Scott Jones, internationally renowned football (“soccer,” in US terminology) star. Scott Jones is from a town nearby DinoFun World. He was a classic hometown hero, with thousands of fans who cheered his success as if he were a beloved family member. To celebrate his years of stardom in international play, DinoFun World declared *“Scott Jones Weekend”*, where Scott was scheduled to appear in two stage shows each on Friday, Saturday, and Sunday to talk about his life and career. In addition, a show of memorabilia related to his illustrious career would be displayed in the park’s Pavilion.

However, the event did not go as planned. Scott’s weekend was marred by crime and mayhem perpetrated by a poor, misguided and disgruntled figure from Scott’s past.

While the crimes were rapidly solved, park officials and law enforcement figures are interested in understanding just what happened during that weekend to better prepare themselves for future events. They are interested in understanding how people move and communicate in the park, as well as how patterns changes and evolve over time, and what can be understood about motivations for changing patterns.

You have access to movement tracking information for all of the paying park visitors over the three days of the Scott Jones celebration. This data contains many patterns that are useful for planning park operations. On this particular weekend a crime occurred and the data likely contains information pertinent to that crime. Analyze the available data and develop responses to the questions below. 

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/MayhemDinoFunWorldVisitorMovement/data/task1.zip)*

This task is focused on movement of people around the park.  We provide you with access to movement tracking information for all paying park visitors over the three days of the celebration. The datasets are `.csv` files for Friday, Saturday, and Sunday, containing a date-time stamp, a visitor ID, a tag as to whether the record referred to a movement within the park grid or a “check-in” to an amusement park ride, and a grid location (x,y coordinates). There is also some auxiliar information that provide extra context (i.e. map, park website, news article).

### Goals

You are asked to characterize the movement of groups and individuals, with a special emphasis on what might be relevant to better understanding the incident that occurred during the "Scott Jones Weekend” event.

1. Characterize the attendance at the park on this weekend. Describe up to twelve different types of groups at the park on this weekend.
    1. How big is the group type?
    2. Where does this type of group like to go in the park?
    3. How common is this type of group?
    4. What are your other observations about this type of group?
    5. What can you infer about the group?
    6. If you were to make one improvement to the park to better meet this group’s needs, what would it be?

2. Are there notable differences in the patterns of activity on in the park across the three days? Please describe the notable differences you found.

3. What anomalies or unusual patterns do you see? Describe no more than 10 anomalies, and prioritize those unusual patterns that you think are most likely to be relevant to the crime.

The definition of *group* is intentionally left to you to determine, so you can best formulate it within the context of your working hypotheses and evidence. For example, a large family group may have between 1-2 adults and 1-5 children. They would visit shopping stalls in the evenings. They would arrive around 08:00 and exit around 23:00. There is also a possibility that at some point during the day, groups would split up according to people-types; the adults and children (e.g., independent teens) would travel around the park in different ways.
Park operations may also impact groups. For example, when a thrill ride shut down for repairs, it would affect the agendas for the teens mentioned above, more than for parents and very young children focused on kiddie rides. In order to answer 2. and 3. look for major/minor disruptions to the movement patterns of park guests. 

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
- description and data characterization 
- answer question 1
- answer question 2
- ...

