# Project Milestone 3

## Title

Optimization of Home Improvements for Satisfaction and Maternal Mental Health


## Abstract

The Piso Firme program aims to improve the quality of life of Mexican people by proposing the installation of free cement floors in households. It has been proven to be a successful operation in the paper “Housing, Health and Happiness”. However, the implementation of such programs implies a high cost for the government authorities, and if the reach of a social program is to be increased, an optimization in the cost is needed. In this project, we will try to determine what housing improvements are the most important for the mentioned benefits. Our results would allow the government to adapt the offer of the program to take cost-effective actions to prioritize the well-being of the families. Households could also be informed on the most efficient housing improvement that they could invest in to improve their well-being without relying on actions from the government.


## Research questions

1) If we want to advise households on what improvement they should invest in, we need to make sure that households who invested by themselves in cement floors received similar benefits than households who were proposed Piso Firme. Therefore we will verify that households from the control group that decided to implement cement floors without aid from the government (variable S_instcement) also show the same benefits.

2) What housing improvements have the greatest effect on the mental health and well-being of the house caretaker? How can the Piso Firme program be more cost-effective?

## Methods

### Methods for part 1:

- Define a new treatment group with the variable S_instcement, for all the households that did not receive Piso Firme.
- Find relevant variables to build a propensity score to match the control group with the new treatment group.
- Match the groups using the aforementioned propensity score, this will balance the dataset and correct for various variables like income, hours worked by household members per capita, etcetera.
- Assess the efficiency of matching using visualization methods. Is it a successful matching?
- Make a similar regression as in table 6 by replacing dpisofirme by S_instcement (indicating the installation of cement)
- Comparison between obtained results in the paper and in 5)
- Visualization

### Methods for part 2:

- Match the control and treatment datasets over the dpisofirme variable.
- Perform regressions on variables indicating mental health (stress, depression, satisfaction features), by using indicators of the presence of cement floors in different rooms and the different renovation instances to determine which variable has the most influence in overall satisfaction.
- Check the significance of results.
- Make conclusions on how the Piso Firme program can be the most cost-effective to be implemented in other develping regions.

## Proposed timeline

- Week 1: Make experiments with the data to find the most relevant variables to do a propensity score. Make the propensity scores with chosen variables and use those to match the control and treatment group. 
- Week 2: Do all the regressions for all the variables proposed in the methodology, and test for robustness and significance. Start working on the visualizations and the conclusions.
- Week 3: Reach conclusions and great visuals for the data story. Record the video and finish the data story.

## Team organization

- Victor: Building the propensity scores and matching the treatment and control groups.

- Jingran: Doing the regressions and analysing the results. Compare them to the results of the paper.

- Daniel: Doing the visualizations, writting down the conclusions and writting the data story.

- All: Record and edit the video.

## Question for TAs

We wondered if regression was the best option to check the influence of several variables on dependent variables or is there a better method?
