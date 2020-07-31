# bikes-sharing-project

Deep learning

Build a neural network from scratch to carry out a prediction of daily bike rental ridership. By building a neural network from the ground up, I'll have a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before moving to higher-level tools such as PyTorch.  

Jupyter notebook flow:  

- Data cleaning was not neccesary due to dataset provided already cleaned.
- Exploratory data anallysis (EDA) with seaborn or another smart python pacakge as SmartEDA in R (not done yet).
- Load and prepare the data: create dummy variables, drop unnecesary columns and standardize continuous variables (variables on different scales make it difficult for the network to efficiently learn the correct weights).
- Split the data into training, testing and validation sets.
- Build the network with the next functions: 
	- forward pass.
	- backpropagation.
	- update weights.