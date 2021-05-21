# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn, PyTorch and Keras.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2

# For students from SJTU
Please read [HEAR](EE369.md).



# Result

Q1:

```
Training accuracy: 97.17%
Testing accuracy: 89.10%
```

Q2:

```
Training accuracy: 82.07%
Testing accuracy: 80.60%
```

Q3:

```
Training accuracy: 97.78%
Testing accuracy: 85.80%
```

Q4:

```
Training accuracy: 100.00%
Testing accuracy: 96.00%
```

Q5:

```
Train Epoch: 0 [0/60000 (0%)]	Loss: 2.296005
Train Epoch: 0 [38400/60000 (64%)]	Loss: 0.127932

Train set: Avg. loss: 0.0995, Accuracy: 56526/60000 (94%)


Test set: Avg. loss: 0.0519, Accuracy: 9815/10000 (98%)

Train Epoch: 1 [0/60000 (0%)]	Loss: 0.046039
Train Epoch: 1 [38400/60000 (64%)]	Loss: 0.014805

Train set: Avg. loss: 0.0125, Accuracy: 59055/60000 (98%)


Test set: Avg. loss: 0.0293, Accuracy: 9897/10000 (99%)

Train Epoch: 2 [0/60000 (0%)]	Loss: 0.043639
Train Epoch: 2 [38400/60000 (64%)]	Loss: 0.015948

Train set: Avg. loss: 0.0220, Accuracy: 59324/60000 (99%)


Test set: Avg. loss: 0.0289, Accuracy: 9891/10000 (99%)

Train Epoch: 3 [0/60000 (0%)]	Loss: 0.003749
Train Epoch: 3 [38400/60000 (64%)]	Loss: 0.003077

Train set: Avg. loss: 0.0056, Accuracy: 59480/60000 (99%)


Test set: Avg. loss: 0.0373, Accuracy: 9870/10000 (99%)

Train Epoch: 4 [0/60000 (0%)]	Loss: 0.008909
Train Epoch: 4 [38400/60000 (64%)]	Loss: 0.001905

Train set: Avg. loss: 0.0587, Accuracy: 59570/60000 (99%)


Test set: Avg. loss: 0.0315, Accuracy: 9887/10000 (99%)

Train Epoch: 5 [0/60000 (0%)]	Loss: 0.061545
Train Epoch: 5 [38400/60000 (64%)]	Loss: 0.062479

Train set: Avg. loss: 0.0013, Accuracy: 59650/60000 (99%)


Test set: Avg. loss: 0.0273, Accuracy: 9895/10000 (99%)

Train Epoch: 6 [0/60000 (0%)]	Loss: 0.012520
Train Epoch: 6 [38400/60000 (64%)]	Loss: 0.017918

Train set: Avg. loss: 0.0300, Accuracy: 59735/60000 (100%)


Test set: Avg. loss: 0.0263, Accuracy: 9909/10000 (99%)

Train Epoch: 7 [0/60000 (0%)]	Loss: 0.011532
Train Epoch: 7 [38400/60000 (64%)]	Loss: 0.004540

Train set: Avg. loss: 0.0044, Accuracy: 59778/60000 (100%)


Test set: Avg. loss: 0.0317, Accuracy: 9888/10000 (99%)

Train Epoch: 8 [0/60000 (0%)]	Loss: 0.011829
Train Epoch: 8 [38400/60000 (64%)]	Loss: 0.001396

Train set: Avg. loss: 0.0146, Accuracy: 59762/60000 (100%)


Test set: Avg. loss: 0.0256, Accuracy: 9909/10000 (99%)

Train Epoch: 9 [0/60000 (0%)]	Loss: 0.003021
Train Epoch: 9 [38400/60000 (64%)]	Loss: 0.000993

Train set: Avg. loss: 0.0049, Accuracy: 59794/60000 (100%)


Test set: Avg. loss: 0.0300, Accuracy: 9895/10000 (99%)
```