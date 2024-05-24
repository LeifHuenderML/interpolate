# Week 10 Research

## Weekly Strategy
- try to get a first draft of the paper written by the end of the week
- get at least a few predictive models up and running
- analyze the difference in predictive quality between the models with dimensionality reduction and the ones without

- for dimensionality reduction i will be using the 7 similarity scoring metrics that i have created to reduce the dimensionality of the data. since i have similarity scores measure similarity between 2 different geo locations, for each of their features, will use each individual features sim score as an output for the yield, as well as the average of all the sim scores features for the output of the yield. i will do this accross all 7 sim scores. Then i will do an average of all sim scores. then i will analyze this to see if their is better predictive ability from that than to a regular larger model trained on the higher dimensionality data. 


## Long-term Strategy

- Outcome: Comparative Climate Analysis:
  A. Analyze individual microclimate data streams to compare and calculate similarity scores.
  B. Assess combined microclimate data streams for seasonal variations comparison.
  C. Group years based on microclimate similarities to identify patterns.
  D. Develop predictive models (LSTM/transformer-based) linking climate to observed outcomes.
  E. Test models against various seasonal stages to evaluate performance.
  F. Synthesize findings to derive actionable insights.

## TODO

- [] look over the paper guidelines
- [] creaete an outline for the paper
- [] finish the research that will be needed for the paper
- [] start writing the paper


# Ideas

# Notes 

# Summary

## Tuesday:
- was at moscows campus all day geting filled in on the summer research fellowship

## Wednesday:
- completed the CITI training

## Thursday: 
- started in the morning by cleaning up the repo to make it easier to navigate
- added dates to the datasets for easier tracking
- added a readme to the datasets folder to make it easier to navigate
- created the ipynbs for touch svm.ipynb gpr.ipynb descision_trees.ipynb rndm_forest.ipynb xg_boost.ipynb kNN.ipynb naive_bayes.ipynb
- fixed a memory + space issue with the repo
- i realized that my similarity scores data is not very well labeled, so i will need to go back and relabel the data
- built the [sim_score_and_yield_05_23_24](../../data/pecan/sim_score_and_yield_05_23_24.csv) dataset
- started testing the quality of predictions from the dataset above using a svm but the results were not very good
- i then created a xgboost model and the results were slightly better but not very impressive
- inside the svm.ipynb is where i created the dataset of sim scores and yield
- i created a dummy model that just predicts the average of the yield for the training data, and the results were not very good at a mse of 484
- then testing that up against the xgboost model, the mse was 478 so there was slight improvement but not very impressive
- i think now what i want to do is to train a larger sequential model so to see if there is stronger predicitve ability from the larger model
- then i can think of a way to reduce the dimensionality of the data to see if that will improve the predictive ability of the model
- built and trained a lstm on weather sequences to output the yield, the results are not yet confirmed but look better than the sim scores by a 97% improvemnent


# Next Week's Outline For 