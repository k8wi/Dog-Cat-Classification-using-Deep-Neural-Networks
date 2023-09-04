# Dog-Cat Image Classification

Classifies an image as containing either a dog or a cat (using Kaggle's <a href="[https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset)">public dataset</a>), but could easily be extended to other image classification problems.

### Dependencies:
- mathplotlib
- Numpy
- keras

## Data

The data directory structure I used was:

* project
  * data
    * dogs
    * cats 

## Performance
The result of the notebook in this repo produced a log loss score on Kaggle's hidden dataset of 1.3778e-04 and an accuracy of 86.81% -- further gains can probably be achieved by creating an ensemble of classifiers using this approach. 
