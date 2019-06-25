# predict_flight_delay
Neural networks are an interesting implementation of a network model that propagates information from node to node.  
Predict flight delay by neural network on weather data. What I do here is - 
1.	Read in the weatherdata data set 
2.	Run the data through a neural network by calling neural net with the following parameters:  stepmax = 100000, hidden = 4, err.fct = "sse", and linear.output = FALSE.   
3.	Make a plot of the network with the weights, error, and steps. 
4.	Compare the predicted output to the known cases of delayed flights.  
5.	Run another neural network but now only use two hidden layers. 
6.	Compare the predicted output to the known cases of delayed flights.  
7.	Use this new network to make predictions by calling the “compute” function. 
