# Swift-TensorFlow-Sample-Notebooks
Collection of sample Swift for TensorFlow Colab Notebooks:

- XOR (Bit Mutual Exlusion Operator)
- FizzBuzz (Trivial coding test)
- Multi-variable Linear Regression (Easy tabular data: Width, Height, Sex)


## XOR
Classic Trivial Model for the XOR (^) Bit Mutual Exclusive Operation

```
0 ^ 0 = 0
1 ^ 0 = 1
0 ^ 1 = 1
1 ^ 1 = 0
```

### Swift Classic 2:2:1 Architecture
Swift TensorFlow implementation with 1 Hidden Layer with only two neurons and sigmoid activation.
This architecure force the model to mimic the following XOR formula: `XOR(x1, x2) = !((x1 & x2) | (!x1 & !x2))`
This model is pretty slow to converge and need lot's of epoch interaction to converge.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/XOR_Swift_TensorFlow_2-2-1.ipynb)

### Swift Fast 2:10:1 Architecture (One hidden layer with ten neurons and relu activation)
Swift TensorFlow faster model with 1 Hidden Layer but a greater number of neurons.
This architecture let the model auto discover features without forcing a particular formula.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/XOR_Swift_TensorFlow_Fast_2-10-1.ipynb)

### Python Keras version for 2:2:1 
Python Keras original implementation of the XOR problem using 1 Hidden Layer with with two neurons and sigmoid activation.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/XOR_Python_Keras_2-2-1.ipynb)


## FizzBuzz
The age-old problem that supposedly filters out the 99.5% of programmers who can’t seem to code

```
if i % 15 == 0:   return "fizzbuzz"
elif i % 5  == 0: return "buzz"
elif i % 3  == 0: return "fizz"
else:             return str(i)
```

### Swift version
Swift TensorFlow version of the classic FizzBuzz programming test

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/FizzBuzz_Swift_TensorFlow.ipynb)

### Python Keras version 
Python Keras version of the classic FizzBuzz programming test

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/FizzBuzz_Keras.ipynb)


## Linear Regression (Width, Height, Sex)
Simple linear regression with multi-variable and categories

Dataset with Height, Weight, Sex statistics from:  https://raw.githubusercontent.com/Dataweekends/zero_to_deep_learning_video/master/data/weight-height.csv

### Swift with SciKitLearn MinMax normalization
Use Python/Pandas to import the dataset
Use SciKit Learn to normalize values with MinMax scaler

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/LinearRegression_MultiVariable_SciKit_Normalize_Swift_TensorFlow.ipynb)

### Swift with Swift Package import for normalizations
Use Python/Pandas to import the dataset
Use SwiftNormalization Package (MinMax, Max, Mean, L1, L2, ZScore) from https://github.com/JacopoMangiavacchi/SwiftNormalization

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/LinearRegression_MultiVariable_With_Packages_Swift_TensorFlow.ipynb)


