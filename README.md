In this project the area of Machine Learning was applied to Formula One race strategy, to assess just how applicable ML and AI are in Formula One. With the vast amounts of data gathered by Formula One teams during each race, and the availability of high-performance computing, Formula One is ripe for the application of AI and ML. There are a great number of areas in Formula One that could benefit from the application of ML and AI, but race strategy was chosen to be the area of focus for this project. Race strategy was chosen due to some recent high-profile mistakes by some Formula One teams and the availability of suitable public data for model training.
For all the complexities of Formula One race strategy, the problem faced by an F1 strategist is a simple question: “When do I call my drivers in for a pitstop?”. The decision-making behind this question involves simulations, data analysis and human intellect. Having contacted several F1 engineers, it was confirmed that ML and AI tools are currently not part of this decision-making toolbox, and with this, the premise of this project was born. 


A Machine Learning model was successfully built which produced a probability of a given driver pitting for each lap of the race. The model was trained, evaluated and tested using race data from 2018 to 2023. On separate test data, the model displayed an ability to identify various common race situations and provide a probabilistic output which would be useful for a Formula One strategist to use as part of their decision-making toolbox.

In this report the background theory of the model will be explained, the methodology for developing it, and the model’s performance, will be discussed. As part of analysing the model's results, the model’s performance for several races will be presented, in the same way that a Formula One strategist would use the model. Finally, as part of the conclusion some thoughts will be given on the usefulness of the model developed and future work that could be done to improve the model. 

The model created during the project displayed an ability to predict the pitstops of drivers with a good level of confidence. The model successfully handled safety car situations, a common strategic situation. Furthermore, the model was able to identify when a driver was at risk of being undercut and acted appropriately. As seen in the results however the model was not perfect, this was exemplified by the 2023 Abu Dhabi Grand Prix, where the model failed to predict the pitstops of drivers with a high degree of confidence. A highlight of the model's traits was its ability to predict the pitstops of top drivers more accurately. This is very positive as top drivers would generally follow more optimal strategies and so the model has learned how to do “good” race strategy.


Overall, the model was a good classifier with it far outperforming a random classifier. It is very possible to see how the model could be used as an additional tool by a Formula One team when they are making race strategy decisions live during a race. As mentioned previously, with the vast amounts of extra data available to a Formula One Team this model could be further improved. Along with this, the extra technical capabilities of a Formula One team would benefit the model’s performance.
The future work of this model would be to retrain the model with a larger dataset. A second dataset was found during the project, with race data back as far as 2014, it was decided not to include this data in the project's model due to issues around merging the dataset, however in the future, this could be done to improve the model. In the future, an LSTM (long short-term memory) layer could be added to the model. This would mean that the model would have information on previous laps when predicting the probability of a pitstop. This would make sense as when Formula One strategists are making decisions on race strategy they consider multiple laps at a time. Finally, I believe merging an ML model with a race strategy simulator would be the optimal solution. In doing this, it would allow for the implications of the model predictions to be evaluated in real-time. This could be used in a reinforcement learning configuration, with the model constantly learning.


Author: Laurence Hearne


Contact: laurenceh19@gmail.com

