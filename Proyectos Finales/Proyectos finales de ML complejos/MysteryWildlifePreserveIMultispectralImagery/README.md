# Mystery at the Wildlife Preserve: Multispectral Imagery

## Background
Mistford is a mid-size city is located to the southwest of a large nature preserve. The city has a small industrial area with four light-manufacturing endeavors.  Mitch Vogel is a post-doc student studying ornithology at Mistford College and has been discovering signs that the number of nesting pairs of the Rose-Crested Blue Pipit, a popular local bird due to its attractive plumage and pleasant songs, is decreasing! The decrease is sufficiently significant that the Pangera Ornithology Conservation Society is sponsoring Mitch to undertake additional studies to identify the possible reasons. Mitch is gaining access to several datasets that may help him in his work, and he has asked you (and your colleagues) as experts in visual analytics to help him analyze these datasets.

Mitch Vogel, the ornithology student who is most concerned about the plight of the Rose-crested Blue Pipit, is able to get around some of the nature preserve to study the bird, but because of the terrain and the vegetation he is not able to cover the entire preserve with a car or on foot. Drones and air vehicles would scare the birds making it difficult to assess the extent of the possible problem. While he puzzles out how to get a more complete picture, he talked with one of his professors at Mistford College who suggested he look at imagery over the area over the past few years.

Perhaps, the professor mused, there have been changes in the flora that are related to issues with fauna. Mitch thought this kind of associated study may be informative, so the professor provided him with some images of the preserve collected by the National Space Service. However, they are multi-spectral image files, which Mitch had never dealt with before. The image analysis packages he found online were very complicated to work with, so he has asked you, a data analytics expert, to help him view and understand this data. Use data analytics to explore the available data and develop responses to the questions below.

### Data - *[Download](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/7_FinalProjects/MysteryWildlifePreserveIMultispectralImagery/data/task3.zip)*

A challenging component of this image dataset is that it is multispectral, that is, there are three other wavelength channels included beyond red, green, and blue. As mentioned, we provide a multispectral analysis primer to assist you with the analysis. We are specifically looking for you to go beyond simple displays of the image data and that employ interesting data and visual analytics to support investigation into the changes in the area over time. 

### Goals

1. Boonsong Lake resides within the preserve and has a length of about 3000 feet (see the Boonsong Lake image file). The image of Boonsong Lake is oriented north-south and is an RGB image (not six channels as in the supplied satellite data). Using the Boonsong Lake image as your guide, analyze and report on the scale and orientation of the supplied satellite images. How much area is covered by a pixel in these images? 
2. Identify features you can discern in the Preserve area as captured in the imagery. Focus on image features that you are reasonably confident that you can identify (e.g., a town full of houses may be identified with a high confidence level). 
3. There are most likely many features in the images that you cannot identify without additional information about the geography, human activity, and so on. Mitch is interested in changes that are occurring that may provide him with clues to the problems with the Pipit bird. Identify features that change over time in these images, using all channels of the images. Changes may be obvious or subtle, but try not to be distracted by easily explained phenomena like cloud cover. 

## Deliverables

Please prepare __a single python notebook__ with the answers. However, feel free to use more than a single python file to solve tasks. If necessary, some results may be pre-computed and stored in separate files. Notebooks must clearly explain the answers to each question, supported by evidence derived from the data and visualized using the tools seen in the course. Describe the characteristics of the data you were given as well as your reasoning process leading to each answer. Use the following structure template for the answers notebook:

- project title, task name
    - description and data characterization 
    - answer question 1
    - answer question 2
    - ...

