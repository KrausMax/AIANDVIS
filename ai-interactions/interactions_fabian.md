Initial Prompt:

  are these good datasets we can use for the tasks at hand?

  also are these good for the tasks we should do??

  https://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html
  https://github.com/zalandoresearch/fashion-mnist

Output:

  Said DeepFashion can work and that Fashion-MNIST is usable but a weak pick, mainly because it is a teaching dataset and scores low on originality.
  As a group we still went with Fashion-MNIST, so this suggestion was not followed.


Prompt 2:

  this is the Dataset we decided to choose: https://www.kaggle.com/datasets/zalando-research/fashionmnist, with this architecture: https://github.com/kefth/fashion-mnist lets create a notebook to see some values of the dataset and what different kind of visualisations we could use. Plan out everything before we start with any real coding, and then we refine the plan together.

Output (Plan mode):

  Gave back a detailed plan with different visualisations which would be good for this dataset.  

Prompt 3:

  I said that I will try to create as many visualisations as possible with the stuff I was given, create a jupyternotebook with all possible visualisations, so I can see which one look the nicest/ best from the plan we wrote. 

Output:

  Phase1_BlackBox_Visualizations.ipynb with 31 visualisations of our ResNet18 on Fashion-MNIST. It only accesses the model through a predict function, so the Phase 1 black box rule is kept, and every plot has a takeaway computed from the data.
  It retrained the same model and got 94.53% instead of 94.22% in the notebook of Max, because the data was moved to the GPU to avoid Windows/notebook problems.
  This was the base of my Phase 1 work, which I then refined a little more with some follow-up prompts:
  - I removed the Phase 2 leads from the notebook.
  - I had the most valuable visualisations selected and described for the team. In this step the AI corrected 4 of its earlier statements, for example "probably wrong labels", where most of the cases are just ambiguous garments. Two more training runs with different seeds confirmed the main findings.
  - For the presentation V10 and V3 were redrawn as slides, V10 so that the 26% "camouflaged" errors became visible in the plot.




