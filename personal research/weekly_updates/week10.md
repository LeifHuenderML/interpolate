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

## Monday: 
- started in the morning by cleaning up the repo to make it easier to navigate
- added dates to the datasets for easier tracking
- added a readme to the datasets folder to make it easier to navigate
- created the ipynbs for touch svm.ipynb gpr.ipynb descision_trees.ipynb rndm_forest.ipynb xg_boost.ipynb kNN.ipynb naive_bayes.ipynb
- fixed a memory + space issue with the repo
- i realized that my similarity scores data is not very well labeled, so i will need to go back and relabel the data


# Next Week's Outline For 