# Center for Global Cyber Strategy: Object of the Search
## Background
In response to an increase in malicious cyber-attacks, numerous “white hat” hacker organizations have taken it upon themselves to fight back to protect the global internet. As the attacks became more and more aggressive, one white hat group, who has so far stayed anonymous, accidentally launched a cyber event that took down the global Internet. The world’s experts are having difficulty understanding what happened and need to get in touch with the group so the effects on the internet can be neutralized and services restored. The only hope for a solution is a cyber think-tank – Center for Global Cyber Strategy, or CGCS – that may hold the key to identifying the group that caused the malfunction. The CGCS maintains awareness of various white-hat hacker groups. The CGCS maintains offline databases of anonymized data donated by the white hat community for research, including machine learning research and development, which makes it one of the few organizations with the resources to assist in this emergency. CGCS also has an ongoing project to explore the motivation, structure and infrastructure of white-hat hacker groups (one of which is responsible for the current situation). You are asked to use CGCS data to identify candidate groups that authorities could approach for assistance in restoring the internet.

With your help, the Center for Global Cyber Strategy (CGCS) searched the vast graph of offline records and narrowed its list of possible groups involved in the accidental cyber event. Further analysis of the cyber event has given a strong indication that a subgroup of eight individuals were behind the bug. The CGCS has received a tip that this group rarely meets in person and instead they use a special item—a totem—as a secret signal of their affiliation. This item is unremarkable to those who are not part of the group; it could easily be confused for a free item handed out at a conference. The CGCS gathered all records associated with the group from their offline archives including text and photos that potential group members posted on the Y* INT social media platform. Investigators at the CGCS need your help analyzing the contents of those records to look for clues to the identity of the eight individuals.

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/CenterGlobalCyberStrategyObjectSearch/data/task2.zip)*

You will be provided with the following:

- A set of training images for a set of many objects that have been distributed at conferences the group frequents. If you choose to train your own models, this training data will be useful.
- The primary data set for analysis. This data contains files for each of 40 different people who are considered potential members of the white hat group who accidentally caused the outage

The image data has been run through a basic machine learning model to identify objects contained in the image. Each image file has an associated data file that lists the objects the algorithm identified, the location within the image, and the confidence in that result. You may use this object recognition data if you wish, or you may use your own model. Some images are accompanied by text captions, and other entries may be text alone. This text has not undergone any special processing.

### Goals

Given the images, text, and audio files, as well as machine learning outputs, your goal is to identify, use data analytics to answer the questions below. Your tasks is to use visual analytics to improve and understand machine learning outputs and apply visual analytics to track provenance, uncertainty, and confidence in machine learning results. Ultimately, you must link multiple data types to identify the group CGCS is seeking.

1. Examine the outputs from the model – either from the detection results provided or the results from a model you chose. Which objects were identified well by the model and which were not?

2. Demonstrate your process for using visual analytics to correct for classification errors in the results. How do you represent confidence and uncertainty? How could the correction process be made more efficient? 

3. Characterize the distribution of objects across the forty people.

    1. Which people have which objects? 

    2. Identify groups of people that have object(s) in common. 

4. Which group do you think is the most likely group with the “totem”? What is your rationale for that assessment?

5. Process question: Did you choose to use the object recognition model results provided or use your own machine learning algorithm? Why did you make that choice? What was the biggest challenge you faced? 

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
- description and data characterization 
- answer question 1
- answer question 2
- ...
