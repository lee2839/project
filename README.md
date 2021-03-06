# Title
*Regularizer Design: Selectivity-based Dropout to suppress memorizing neurons*
## Team members
Junseok Lee (lee2839)
## Goals
Based on an ICLR 2018 paper by Google DeepMind saying that 'confusing' units are more important than 'memorizing' units, this project tries to suppress the 'memorizing' neurons by individually performing Dropout on each units.
## Challenges
1. Need to develop a dataset loader that corrupts labels of the MNIST dataset.
1. Need to develop a custom Dropout module that drops each individual unit with the dropout probability based on selectivity indices.
1. Need to develop a class that calculates selectivity indices and pass them to the custom dropout module.
## Restrictions
1. Computational power: this project will be performed my laptop equipped with an i7 mobile processor.
