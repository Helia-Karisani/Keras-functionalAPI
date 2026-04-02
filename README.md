
# Keras Functional API – Neural Network Design

This project demonstrates how to build neural networks using the **Keras Functional API**, which allows more flexible and expressive model architectures compared to the Sequential API.

---

##  Overview

The notebook focuses on constructing models where layers are connected explicitly, enabling:

- multiple inputs and outputs  
- non-linear architectures  
- better control over model structure  

The Functional API treats models as **graphs of layers**, rather than simple stacks.

---

##  Key Idea

Instead of stacking layers linearly, we define how data flows:

```python
x = Dense(64, activation='relu')(input_layer)
output = Dense(10, activation='softmax')(x)
````

Each layer takes the previous layer as input and returns a new tensor.

---

##  What This Project Covers

* defining input layers
* connecting hidden layers
* building models with custom structures
* understanding how data flows through the network

---

##  Why Functional API?

* more flexible than Sequential models
* supports complex architectures
* widely used in real-world deep learning systems

---

##  File

```
Keras-functionalAPI.ipynb   # main notebook
```

---

##  Summary

This project provides a hands-on introduction to designing neural networks using Keras in a more flexible and scalable way, preparing for advanced architectures such as multi-input models and deep learning pipelines.

