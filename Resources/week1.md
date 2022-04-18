# Week 16 - Resources

[:house: Main page](https://github.com/kokchun/Deep-learning-AI21)

## Setup :wrench:

1. Create a new folder for this course
2. Create a new pipenvironment with
   ```python
   pipenv shell
   ```
3. Install **numpy**, **pandas**, **matplotlib**, **seaborn**, **ipykernel**, **scikit-learn**, **tensorflow** to this pipenv

When training the network, we will use Kaggles jupyter notebooks, which gives ca 30h of GPU time each week.

Optional local installation for GPU support if your computer has an Nvidia GPU:

- [Setup CUDA, cuDNN, tensorflow-gpu - towardsdatascience](https://towardsdatascience.com/installing-tensorflow-with-cuda-cudnn-and-gpu-support-on-windows-10-60693e46e781)

## Video guides :video_camera:

- [Backpropagation part 1 - Andrew Ng](https://www.youtube.com/watch?v=x_Eamf8MHwU)
- [Backpropagataion part 2 (intuition) - Andrew Ng](https://www.youtube.com/watch?v=mOmkv5SI9hU)
- [Backpropagation - 3Blue1Brown](https://www.youtube.com/watch?v=Ilg3gGewQ5U&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=3)
- [Backpropagation calculus - 3Blue1Brown](https://www.youtube.com/watch?v=tIeHLnjs5U8&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=5)
- [How many hidden layers and nodes? - DigitalSreeni](https://www.youtube.com/watch?v=bqBRET7tbiQ)
- [Cross entropy - normalizednerd](https://www.youtube.com/watch?v=gIx974WtVb4)

Improving on gradient descent
- [Gradient descent with momentum - Andrew Ng](https://www.youtube.com/watch?v=k8fTYJPd3_I)
- [RMSProp optimization algorithm - Andrew Ng](https://www.youtube.com/watch?v=_e-LFe_igno)
- [Adam optimization algorithm - Andrew Ng](https://www.youtube.com/watch?v=JXQT_vxqwIs)

## Lecture notes :book:
- [MLP for regression](https://github.com/kokchun/Deep-learning-AI21/blob/main/Lectures/Lec0-MLP_regression.ipynb)
- [MLP for classification](https://github.com/kokchun/Deep-learning-AI21/blob/main/Lectures/Lec0.1-MLP_classification.ipynb)
- [MLP for image classification](https://github.com/kokchun/Deep-learning-AI21/blob/main/Lectures/Lec1-MLP_image_classification.ipynb)

## Theory :book:

- [Backpropagation - Michael Nielsen](http://neuralnetworksanddeeplearning.com/chap2.html)
- [Backpropagation - wikipedia](https://en.wikipedia.org/wiki/Backpropagation#Motivation)
- [Multilayered Perceptron - wikipedia](https://en.wikipedia.org/wiki/Multilayer_perceptron)
- [Activation function - wikipedia](https://en.wikipedia.org/wiki/Activation_function)
- [Configure layers and nodes in NN - machinelearningmastery](https://machinelearningmastery.com/how-to-configure-the-number-of-layers-and-nodes-in-a-neural-network/)
- [Adam optimizer - wikipedia](https://en.wikipedia.org/wiki/Stochastic_gradient_descent#Adam)
- [Cross-entropy - wikipedia](https://en.wikipedia.org/wiki/Cross_entropy)
- [Cross-entropy - machinelearningmastery](https://machinelearningmastery.com/cross-entropy-for-machine-learning/)
- [Vanishing gradient problem - wikipedia](https://en.wikipedia.org/wiki/Vanishing_gradient_problem)
- [Probabilistic machine learning draft pp. 419-444 - Murphy (2022)](https://probml.github.io/pml-book/book1.html)
- [Softmax function - wikipedia](https://en.wikipedia.org/wiki/Softmax_function)
- [How many hidden layers/neurons - Gad (2018) towardsdatascience](https://towardsdatascience.com/beginners-ask-how-many-hidden-layers-neurons-to-use-in-artificial-neural-networks-51466afa0d3e)
- [Rule of thumb - Ranjan (2019) towardsdatascience](https://towardsdatascience.com/17-rules-of-thumb-for-building-a-neural-network-93356f9930af)
- [Convolution - wikipedia](https://en.wikipedia.org/wiki/Convolution)


Keras

- [Sequential model guide - TensorFlow](https://www.tensorflow.org/guide/keras/sequential_model)
- [InputLayer Keras - TensorFlow](https://www.tensorflow.org/api_docs/python/tf/keras/layers/InputLayer)
- [Dense layer Keras - TensorFlow](https://www.tensorflow.org/api_docs/python/tf/keras/layers/Dense)
- [Visualize model training history - machinelearningmastery](https://machinelearningmastery.com/display-deep-learning-model-training-history-in-keras/)
- [EarlyStopping - Keras](https://keras.io/api/callbacks/early_stopping/)
- [None in model - stackoverflow](https://stackoverflow.com/questions/47240348/what-is-the-meaning-of-the-none-in-model-summary-of-keras)
- [Sparse categorical cross-entropy keras - TensorFlow](https://www.tensorflow.org/api_docs/python/tf/keras/losses/SparseCategoricalCrossentropy?version=nightly)
- [Classification metrics in Keras - machinelearningmastery](https://machinelearningmastery.com/custom-metrics-deep-learning-keras-python/)

TensorFlow basics (to get understanding of how pure TensorFlow works)

- [TensorFlow basics - TensorFlow](https://www.tensorflow.org/guide/basics)
- [Introduction to Tensors - TensorFlow](https://www.tensorflow.org/guide/tensor)
- [Variables - TensorFlow](https://www.tensorflow.org/guide/variable)
- [Training loops - TensorFlow](https://www.tensorflow.org/guide/basic_training_loops)

Mathematical prerequisite:

- [Gradient - wikipedia svenska](<https://sv.wikipedia.org/wiki/Gradient_(matematik)>)
- [Partiell derivata - wikipedia svenska](https://sv.wikipedia.org/wiki/Partiell_derivata)

## Exercises :running:
- [MLP exercises](https://github.com/kokchun/Deep-learning-AI21/blob/main/Exercises/E0-MLP.ipynb)
- [MLP image classification exercises](https://github.com/kokchun/Deep-learning-AI21/blob/main/Exercises/E1-MLP_image_classification.ipynb)