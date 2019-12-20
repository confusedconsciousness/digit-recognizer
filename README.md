# digit-recognizer
This repository contains self made neural network that is able to classify handwritten digits<br>
Dataset can be downloaded from the following link https://drive.google.com/open?id=1vI3QJ8whh-z4AQo7FyNxfOw6G8dTCDBF
<br>
A little about the neural network:<br>
The neural network consists of three layers
<ol>
	<li> Input layers consisting of 784 nodes</li>
	<li> Hidden layers consisting of 100 nodes</li>
	<li> Output layers consisting of 10 nodes</li>
</ol>
we are basically using sigmoid as our activation function and weights are not completely initialised furthermore the pixels details are scaled and shifted so that values lie between <b>[0.01, 0.99]</b><br>
The neural network class contains three methods and the whole training part is done using stochastic(not vanilla gradient descent) gradient descent.

