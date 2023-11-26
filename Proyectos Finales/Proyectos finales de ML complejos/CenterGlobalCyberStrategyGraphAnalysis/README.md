# Center for Global Cyber Strategy: Graph Analysis
## Background
In response to an increase in malicious cyber-attacks, numerous “white hat” hacker organizations have taken it upon themselves to fight back to protect the global internet. As the attacks became more and more aggressive, one white hat group, who has so far stayed anonymous, accidentally launched a cyber event that took down the global Internet. The world’s experts are having difficulty understanding what happened and need to get in touch with the group so the effects on the internet can be neutralized and services restored. The only hope for a solution is a cyber think-tank – Center for Global Cyber Strategy, or CGCS – that may hold the key to identifying the group that caused the malfunction. The CGCS maintains awareness of various white-hat hacker groups. The CGCS maintains offline databases of anonymized data donated by the white hat community for research, including machine learning research and development, which makes it one of the few organizations with the resources to assist in this emergency. CGCS also has an ongoing project to explore the motivation, structure and infrastructure of white-hat hacker groups (one of which is responsible for the current situation). You are asked to use CGCS data to identify candidate groups that authorities could approach for assistance in restoring the internet.

Center for Global Cyber Strategy (CGCS) researchers have used the data donated by the white hat groups to create anonymized profiles of the groups. One such profile has been identified by CGCS sociopsychologists as most likely to resemble the structure of the group who accidentally caused this internet outage. You have been asked to examine CGCS records and identify those groups who most closely resemble the identified profile.

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/CenterGlobalCyberStrategyGraphAnalysis/data/task1.zip)*

Data consists of the following:

- A subgraph template representing the structure of the group identified by CGCS, in CSV (comma-separated values) format.
- Several candidate subgraphs, in CSV format.
- A very large graph in CSV format. This graph is downloaded separately. Instructions for how to access it are available in the data description.
- A list of “seeds”, or IDs that can provide starting points for exploring the large graph.


### Goals
1. Using data analytics, compare the template subgraph with the potential match provided. Show where the two graphs agree and disagree. Use your tools to answer the following questions:
    1. Compare the five candidate subgraphs to the provided template. Show where the two graphs agree and disagree. Which subgraph matches the template the best?
    2. Which key parts of the best match help discriminate it from the other potential matches?
2. CGCS has a set of “seed” IDs that may be members of other potential networks that could have been involved. Take a look at the very large graph. Can you determine if those IDs lead to other networks that matches the template? 
3. Optional: Take a look at the very large graph. Can you find other subgraphs that match the template provided? 
4. Based on your answers to the question above, identify the group of people that you think is responsible for the outage. What is your rationale? 
5. What was the greatest challenge you had when working with the large graph data? How did you overcome that difficulty? What could make it easier to work with this kind of data?

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
- description and data characterization 
- answer question 1
- answer question 2
- ...
