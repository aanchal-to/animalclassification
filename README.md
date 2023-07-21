# animalclassification-techhack1
Classify species of animals based on pictures. Can automatically help identify animals taken from the wild by wildlife conservatories. 
Can lead to discoveries of potential new habitats as well as new, unseen species of animals within the same class.

Train images of animals from three different species with thousands of labeled pictures model using Convulational Neural Network.
Data came from Animals-10 dataset in kaggle. Only chose three of the available species due to computer processing limitations, as well as fixed time window to run experiment.

All process and methods can be found in the [Final Notebook](https://github.com/aanchal-to/animalclassification-techhack1/blob/main/classify.ipynb)

This model can excellently guess a picture of an animal if the shape of the animal is in the training method. To train it on additional animals, simply feed it labeled images (1000 at least for training and 300+ for validation). 
Also, just for fun, you can also give the machine a picture of a pokemon like Rapidash, and it will guess it is a horse.
