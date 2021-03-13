# W21-COMP4107-Project-Grootslang

**Carleton University - Group 28**

Devon Hope - 101038344

Yichen Dou - 101003897

## Introduction

The basic idea is to implement the Wave Function Collapse (WFC) in a neural network, researching how it works, its performance and its accuracy. Users should gain some controls over the inputs to generate procedural patterns

## Research Questions
### City Builder
A city builder system that uses a pattern image(height graph) to generate the city, where each module in the city is an unit that containing a height value and its possible neighbors (restricted). The application should generate a new matrix in which each unit is solved by WFC algorithm to get its correct neighbors and is maped into its corresponding height area in the pattern as much as possible
- Without restriction of neighbors, this city builder is just a simple unsupervised question, the model takes a city module's height as input and outputs its x and y coordinates on a map
- With restriction of neighbors, we probally need to do it in a WFC way by picking a city module first, solving that module's possible neighbors and updating the new network(a little bit like time-series network). Repeat the process until every city modules is predicted correctly

### Ecosphere System
It contains many animals and plants, some can be friends, some can be natural enemy, there are herbivores and carnivores. In the system, the aim of the nerural network is to make the ecosphere system as long as possible without any extinction of species, such that it forces us to map them correctly in a map where each species have neighbors that are friendly or less-feedable. This question should be solved in a WFC way
- More parameters and more understandable features
- Solve the block one by one using prediction
- May involve time-series network as well
- Similar to [Conways Game of Life](https://academo.org/demos/conways-game-of-life/)
- Possible to use RNNs like GRU(Gated Recurrent Units) or LSTM

## To-do

- [ ] Research things about WFC and its possibilities on CNN, GAN or RNN

## Progress

| Title    | Date   | Description | Status  |
| -------- | ------ | ----------- | ------- |
| Proposal | Mar 12 | Due Mar 13  | Ongoing |
|          |        |             |         |
|          |        |             |         |
|          |        |             |         |
|          |        |             |         |
|          |        |             |         |
|          |        |             |         |

## Related

[Wave Function Collapse Github](https://github.com/mxgmn/WaveFunctionCollapse)

[Wave Function Collapse in Deep Convolutional Generative Adversarial Network](https://www.ukessays.com/essays/computer-science/wave-function-collapse-in-deep-convolutional-generative-adversarial-network.php)

[Solving Sudoku with Convolution Neural Network | Keras](https://towardsdatascience.com/solving-sudoku-with-convolution-neural-network-keras-655ba4be3b11)

[Explain Wave Function Collapse](https://robertheaton.com/2018/12/17/wavefunction-collapse-algorithm/)

[Online Demo](http://oskarstalberg.com/game/wave/wave.html)

