# wine_expert
An investigation into NLP interpretability using the Kaggle wine reviews dataset.

**Project Summary**

This project was undertaken to build a greater understanding of NLP methods and more specifically the growing field of NLP interpretability. The ultimate goal of this project was to create a classifier that was capable of both performing at expert level, but also operated with a level interpretability that would allow the education of newcomers to wine tasing and reviewing (like me).

**Project Contents**
  1. Building a classifier
  2. Prediction Interpretation 1 - mapping the embedding layer
      - visualising the grouping of wine descriptions learnt by classification model with tSNE
  3. Prediction Interpretation 2 - Predictions with Justification
      - delivering predictions with rationale
      - understanding 'nearest' categories and why
  4. Context in RNNs - 'Apples not Oranges'
      - investigating the importance of the context a word is used in and how current interpretability techniques fail.
      - Visualising the 'inter-dependency' of words in a description
      - graphical representation of classification profile to further rationalize outputs
  5.  Generating classification profiles
      - what are the key characteristics of a certain wine region? Can we make experts of novices?


      
**Future Work**

In future work on NLP interpretability I would like to investigate the use of Three Player Games for Rationalization - as described by this paper https://arxiv.org/pdf/1910.13294.pdf. This appears to be an elegant solution to the problem of 'overfit' interpretability, where seemingly meaningless tokens are returned as the most influential or the final word of a key phrase is shown but the rest of the phrase is ignored.
      
