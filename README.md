# AI-Coursework

# Task 1

* The algorithms are in a class called: GridEnvironment
* Create a new object: test = GridEnviroment(n, m) the size of the matrix
* To call the simple algorithm: test.stupidAlgorithm(), returns the shortest path value
* To call the dijkstra: test.dijkstra(), return the shortest path value. You can uncomment the print at the end of dijkstra method for printing shortest paths for all cells.

## The ant colony optimization doesn't work.

# Task 2

* The neural network is in a class NeuralNetwork(lr, units1, units2, layer1, layer2) with 2 hidden layers
* lr - learning rate
* units1 and units2, the number of neurons for the first and second hidden layers
* layer1 and layer2 are the type of hidden layers in all lower case letters, i.e "sigmoid", "relu"

* an example of a NeuralNetwork object: model = NeuralNetwork(0.001, 128, 64, "sigmoid", "relu")

* to train and test the model, call train_test(epochs, model)
* epochs - epoch number
* model - an instance of a class NeuralNetwork()

* an example: train_test(5, model)

# Task 3

* 2 classes: NeuralNetwork(units1, units2, first_layer, second_layer) and CNN():
* units1 and units2, the number of neurons for the first and second hidden layers
* first_layer and second_layer are the type of hidden layers in all lower case letters, i.e "sigmoid", "relu"

* CNN() has no parameters.

* to train and test the model, call train_test(epochs, model, lr)
* epochs - epoch number
* model - an instance of a class NeuralNetwork() or CNN()
* lr - learning rate
