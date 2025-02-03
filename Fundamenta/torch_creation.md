# Origins in Torch

The original Torch library was developed in 2002 by Ronan Collobert, Koray Kavukcuoglu, and Clément Farabet. It was primarily written in Lua, a lightweight scripting language, and became popular in the machine learning community, especially in computer vision tasks.

Torch provided a flexible and efficient framework for tensor computations, leveraging the benefits of the underlying TH (Torch Hardware) library, which provided optimized linear algebra routines.

## Shift to Python

While Torch was effective, the Lua ecosystem was not as widely adopted as Python, which was becoming the de facto language for machine learning and data science. In response to the growing popularity of Python and the demand for deep learning tools that integrated well with existing Python libraries (like NumPy and SciPy), the team behind Torch decided to create a new library in Python.

## Development of PyTorch

In 2016, Facebook's AI Research (FAIR) lab released PyTorch as a successor to Torch. PyTorch was designed to be more user-friendly and flexible, allowing for easy experimentation and dynamic computation graphs (as opposed to the static computation graphs used in many other frameworks, like TensorFlow at that time).

PyTorch's dynamic computational graph (or define-by-run paradigm) enables developers to change the network architecture on-the-fly, which is particularly useful for tasks involving variable input sizes and recurrent neural networks.
