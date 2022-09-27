# FlappyBird-NEAT_algo
## Neuro-evolution of augmenting topologies
We will use this technique to generate various neural networks that differ from each other in a small way.
We will let these Neural Networks control our Bird and we will pick the Neural Network that made the bird stay alive the longest 
That is, the Score will be our Fitness Function
Then, this selected Neural Network (specimen) will be used to inspire/generate Neural Networks of the next generation.
We will provide a Max Generation Threshold, which will be the number of genreations after which we will stop the evolution and try again; possibly with a different population size.

## Clone
We will start by making a clone of the game Flappy Bird 
The assests used for this are placed in the `imgs` folder
