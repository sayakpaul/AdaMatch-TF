# AdaMatch-TF
Includes additional materials for the following keras.io blog post: **Semi-supervision and domain adaptation with AdaMatch**. [PR in Progress](https://github.com/keras-team/keras-io/pull/513).

## About the notebooks

* `AdaMatch.ipynb`: Original notebook submitted for the [PR](https://github.com/keras-team/keras-io/pull/513).
* `Vanilla_WideResNet.ipynb`: Trains a WideResNet-28-2 on MNIST (source domain) and evaluates on the SVHN dataset (target domain). The model trained in this notebook serves as the baseline. 

## Results

All the models are trained on MNIST as the source domain and evaluated on the SVHN dataset as the target domain. Following are the top-1 accuracies on SVHN:
          
| With AdaMatch 	| Without AdaMatch 	|
|:-------------:	|:----------------:	|
|     29.59%    	|       7.20%      	|

## Acknowledgements

[ML-GDE](https://developers.google.com/programs/experts/) program for providing GCP credits that supported the experiments. 
