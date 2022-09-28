# FlappyBird-NEAT_algo
## Neuro-evolution of augmenting topologies
1. We will use this technique to generate various neural networks that differ from each other in a small way.
2. We will let these Neural Networks control our Bird and we will pick the Neural Network that made the bird stay alive the longest 
3. That is, the Score will be our Fitness Function
4. Then, this selected Neural Network (specimen) will be used to inspire/generate Neural Networks of the next generation.
5. We will provide a Max Generation Threshold, which will be the number of genreations after which we will stop the evolution and try again; possibly with a different population size.
6. All the different options and parameters must be configured inside of the `configfeedforward.txt` template file which must be placed in the same folder as we will access it in our code
7. We will define a threshold score, which upon being surpassed will indicate us to save the current weight as they are good enough for our liking. We will save these weights using the `pickle` library in the `best.pickle` file
8. Now, we can load these saved weights and have our selected (best) neural network play Flappy Bird for us any time we wish
9. Paper Link: https://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf 

## Game Engine
1. We will start by making a clone of the game Flappy Bird using the `pygame` library
2. The assests used for this are placed in the `imgs` folder
3. The code and logical flow of the entire project is present in the `FlappyBird.py` file

## Notes
1. Adjust the pygame.time.Clock().tick() method to determine how fast each frame is processed.
2. Adujst the score threshold according to your liking
3. Experiment with adjusting the activation function to study its effects on the result
