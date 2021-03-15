# W21-COMP4107-Project-Grootslang

Group #: 28

# Members

Yichen Duo - 101003897
Devon Hope - 101038344

# What is the research question you are trying to answer?

Can neural network algorithms help interstellar colonization?

 

# What dataset will you be using and how do you plan to acquire it?

Visualized or real data about natural resources, atmosphere and environment on a planet

Example : https://www.kaggle.com/peijenlin/surviving-mars-maps

[Human life sustainability set](https://www.kaggle.com/jaimetrickz/surviving-on-mars)



# What data does the dataset contain?

Temperature, resources, topography at a specific latitude, longitude and altitude



# What techniques do you plan to use to approach the problem?

We will first use unsupervised learning in guiding learning features and finding correlations of possible features in the dataset, plotting maps and graphs scientifically. Then we use given labels such as difficulties or newly created features, such as possibilities to build a city, as labels to start training a convolutional neural network to learn the planet. Then we will try different models that best predict what are needed in interstellar colonization. To do this we will need to use an RNN such as the LSTM or GRU structured models to remember planet structures and viabilities while looking for other plants that have similarities. In development of the interstellar model, it is possible to switch to a GAN model while evaluating other planets viability. 



# What additional research do you need to conduct

Given inputs of data, we need to determine which area on the planet best suits humanity

The research may consider resource depletion and time-changing effects in the model

Some resources are essential in building cities, so a model should predict possibilities of the appearance of a resource in given locations, as well as predict the depletion of resources over time based on previous material extraction.

