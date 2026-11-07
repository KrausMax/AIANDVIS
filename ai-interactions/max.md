Initial Prompt:

  Our goal is to examine how the model handles different types of apparel, looking into common misclassifications, confidence drops, and feature importance across broad item groupings (such as seasonal or structural categories). 
  We also want to see how image transformations affect predictions and inspect internal representations to understand what visual features drive errors.
  
  The Dataset: https://www.kaggle.com/datasets/zalando-research/fashionmnist
  
  
  
  Create a notebook to train/evaluate/visualize the model
  
  Use this architecture ResNET18: https://github.com/kefth/fashion-mnist  

Output:

  Good first Codeblocks to setup data set, model and train, already included some visualizations but were not suitable for phase 1 / not further considered in the Project

Prompt 2:

  The project is split into 2 phases,
  
  Phase I: How does the model behave?
  
  In this phase, you will treat the model as a black box; you don’t look inside it. You only look at inputs and outputs and build up a picture of its behavior from that alone. W

Output:

  Good first looks at the data, were used to coordinate in the 2nd team meeting which parts of the data we wanted to focus on / what were interesting points to explore. Not used in Final output

Prompt 3:

  I want to create an interactive visualization to interact with the Dataset, how could such a visualization look like, dont code yet, only give ideas

Output:

  In the group we discussed what visualization techniques we wanted to implement and i volunteered to try to implement an interactive one, since AI use could greatly speed up the process of writing the code. 
  To get a start of what was feasible i asked this question and got 4 Answers. One strongly correlated with what I had in mind which i further expanded upon.

Prompt 4:

  Concept 1 seems very promising, can you create such an interactive visualizer

Output: 

  A implemented Code block to run after the model training, implemented all the features required for the taks.
  It was already very promising, some minor adjustments were needed to run it independently as the model had to be trained every time before startup
  
