Created an Artificial Neural Network from scratch to better understand the underlying
fundemental concepts of Deep Neural Networks. The Full neural network layout with extensive
comment descriptions can be found in Full_Neural_Network.ipynb. 

Utilized the handmade ANN framework on the Heart Failure Clinical Record Dataset. trial_run.ipynb
was one trial run on how the ANN would perform with preset hyperparameters. This was done to see if
the framework was fully functional, rather than trying to optimize accuracy scores. This file proved
that the framerwork was working properly.

To properly train and test the model, I implemented a full pipeline that utilizes a Grid Search and 
a K-Fold Cross Validation. This will both find the best performing hyperparameters and properly calculate
the performance metrics of the model. After running the pipeline, I got an average accuracy score of 
79.6 percent and the optimal calculated hyperparameters are as followed: 

{'layer_widths': 48, 'learning_rates': 0.0012, 'epochs': 10000, 'l2': 0.0009}
{'layer_widths': 24, 'learning_rates': 0.0012, 'epochs': 50000, 'l2': 0.0009}

Dependencies:
- Numpy 1.24.3 
- Pandas 2.0.3 
- scikit-learn 1.3.0 
- jupyterlab 3.6.3  