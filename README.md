# Project Milestone 3

## 1) Title

Optimization of Home Improvements for Satisfaction and Maternal Mental Health


## 2) Abstract

The Piso Firme program aims to improve the quality of life of Mexican people by proposing the installation of free cement floors in households. It has been proven to be a successful operation in the paper “Housing, Health and Happiness”. However, the implementation of such programs implies a high cost for the government authorities, and if the reach of a social program is to be increased, an optimization in the cost is needed. In this project, we will try to determine what housing improvements are the most important for the mentioned benefits. Our results would allow the government to adapt the offer of the program to take cost-effective actions to prioritize the well-being of the families. Households could also be informed on the most efficient housing improvement that they could invest in to improve their well-being without relying on actions from the government.


## 3) Research questions

1) If we want to advise households on what improvement they should invest in: Do households that invested themselves (without aid from the government) in cement floors also received similar impacts in terms of mental health and happiness?

2) What rooms have the greatest effect on the mental health and well-being of the house caretaker, when upgraded with cement floors? How can the Piso Firme program be more cost-effective?

3) What other house improvements could have a positive impact on the happiness scale? Should they also be considered in governamental programs?

## 4) Datasets
For this project we will use the original data set from the paper.

## 5) Methods

### Methods for part 1:

- Define a new treatment group with the variable S_instcement, for all the households that did not receive Piso Firme.
- Find relevant variables to build a propensity score to match the control group with the new treatment group.
- Match the groups using the aforementioned propensity score, this will balance the dataset and correct for various variables like income, hours worked by household members per capita, etcetera.
- Assess the efficiency of matching using visualization methods. Is it a successful matching?
- Make a similar regression as in table 6 by replacing dpisofirme by S_instcement (indicating the installation of cement)
- Visualization

### Methods for part 2:

- Perform regressions on variables indicating mental health (stress, depression, satisfaction features), by using indicators of the presence of cement floors in different rooms (kitchen, dining room, bedroom, bathroom) to determine which variable has the most influence in overall satisfaction.
- Check the significance of results.
- Make conclusions on how the Piso Firme program can be the most cost-effective to be implemented in other develping regions.

### Methods for part 3:
- Perform regressions on variables indicating mental health (stress, depression, satisfaction features), by using indicators of the different renovation instances (cement floors, construction adn restoration of sanitary facilities, construction of ceiling, restoration of walls) to determine which variable has the most influence in overall satisfaction.
- Check the significance of results.
- Make conclusions on whether or not Piso Firme program should include other types of house improvements for future instances.

## 6) Proposed timeline

- Week 1: Make experiments with the data to find the most relevant variables to do a propensity score. Make the propensity scores with chosen variables and use those to match the control and treatment group. 
- Week 2: Do all the regressions for all the variables proposed in the methodology, and test for robustness and significance. Start working on the visualizations and the conclusions.
- Week 3: Reach conclusions and great visuals for the data story. Record the video and finish the data story.

## 7) Contribution from the team members

- Victor Taburet: Building the propensity scores and matching the treatment and control groups, performing the regressions for research question 1, interpretation and visualization for results. Data story: original draft and design.

- Su Jingran: Data visualization, map construction, design in html images. Performing the regressions for research question 2, interpretation and visualization for results. Data story: original draft and design.

- Daniel Gutierrez-Navarro: Data analysis, performing the regressions for research question 2 & 3, interpretation and visualization for results. Data story: original draft.
