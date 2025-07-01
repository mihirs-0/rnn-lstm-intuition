# From "classical" ML to NN-ML

It is an important distinction to make, where the massive scope of generalizability and zero-shot learning starts in LLMs. It starts where we let the architecture speak for itself, based on the data it sees. 
Essentially, we let the model choose how to interpret and weigh the data: we define the resources which it can use, not even the framework.

Classical ML can be thought of as framework-constrained, whereas NN-ML is resource-constrained. We choose how much we want to fit the data. 

Neural Networks are universal function approximators.

And in that too, they're especially good at handling increasing dimensionality. 

There is this epistemological shift that happes when moving from linear and tree based models to layered neural architectures. 

Going from feature engineering to feature learning is key. The features are learned, not arbitrarily defined. This imparts a broader generalizing power to NNs. 

Both classical ML and neural networks begin with a function template and learn its parameters through training. But classical ML defines a clear, interpretable function form — like a line or a tree — and optimizes within it. Neural networks, by contrast, define a differentiable system that generates functions through composition, depth, and nonlinearity. The final function in NN ML is not just parameterized, it is emergent — shaped by the data, not just fitted to it. This is the philosophical shift: classical ML chooses a function and tunes it; neural ML builds the function itself, layer by layer.

As a detour, I also want to note how powerful mathematical functions like the Fourier and Taylor series can approximate 2D data with a very high accuracy. However, when scaled, the number of terms to be tackled go on increasing exponentially. With Neural Networks, it's about adding more hidden layers. 
