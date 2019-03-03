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

In 2:2:1 Architecture XOR(x1, x2) = !((x1 & x2) | (!x1 & !x2))

### Swift Classic 2:2:1 Architecture (One hidden layer with only two neurons and sigmoid activation)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/XOR_Swift_TensorFlow_2-2-1.ipynb)

### Swift Fast 2:10:1 Architecture (One hidden layer with ten neurons and relu activation)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/XOR_Swift_TensorFlow_Fast_2-10-1.ipynb)

### Python Keras version for 2:2:1 
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
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/FizzBuzz_Swift_TensorFlow.ipynb)

### Python Keras version 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/FizzBuzz_Keras.ipynb)


## Linear Regression (Width, Height, Sex)
Simple linear regression with multi-variable and categories
Dataset with Height, Weight, Sex statistics: https://raw.githubusercontent.com/Dataweekends/zero_to_deep_learning_video/master/data/weight-height.csv

## Swift with SciKitLearn MinMax normalization

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JacopoMangiavacchi/Swift-TensorFlow-Sample-Notebooks/blob/master/LinearRegression_MultiVariable_SciKit_Normalize_Swift_TensorFlow.ipynb)

