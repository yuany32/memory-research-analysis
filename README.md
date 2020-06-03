# **memory-research-analysis**
Repo contains all codes for data analysis and visualization of research data using iPython. <br>
_note_: All experiment designs, hypothesis and recorded data belong to Dr. Anna Jafarpour and the Buffalo Lab, Physiology and Biophysics Department, University of Washington.


## The Task
### Task goal and descriptions
During the experiment, we asked participants (ages 18 to 25 years old) to complete a memory maze (what we called "double Y maze") where they first identify the target image and they need to memorize the target image while navigating through sequences of images to try to get back to the target image. The _goal_ of the game is to navigate back to the target image with the correct route. There are _3 types of results_ for the memory game:
- **correct**: navigate back to the target image successfully with all correct decisions making.
- **wrong route**: navigate back to the target image successfully with only 1 correct decision at decision point 2.
- **incorrect**: fail to navigate back to the target image.

### While navigating in the game..
There are _2 types_ of questions: **fixed answers questions** and **decision points**.
- **Fixed answers questions**: Before starting the game, We ask participants a set of questions that have fixed answers based on their own opinion (_eg. is a trophy expensive?_). Those answers to the questions will never change throughout the game.
- **Decision points**: There are _2 decision points_ during the navigations. The participants need to get both decisions correct, which means the correct navigation route to receive a reward(a screen showing correct); If the participants successfully navigate back to the target but through the wrong route, there will be no reward but the screen will show "wrong route"; If the participants did not navigate back to the original target image, the screen will display "incorrect" as a punishment.

![maze design](doubleYmaze.png)

### The hypothesis
- people will get more correct trials in the later trials by learning the task.
- people will get faster response as they start learning and predicting the next showing image.
- People use previous schema to learn in new sets of trials.
- There might be segmentation after the decision point and people will have faster response time while learning the consecutive images.

## The Data

### Data sample

### Data analysis & visualization
- Tools used: Pandas, Numpy, re, glob, fnmatch
- [Data organizing and cleaning](https://github.com/yuany32/memory-research-analysis/blob/master/data%20summary.ipynb)
- Participants' data overview
