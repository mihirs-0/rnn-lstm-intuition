# rnn-lstm-intuition

# From MLPs to Attention

I have been curious about the emergence of causality in LLMs. The emergence of causal understanding (or not) in LLMs is a wonder to me, and in an effort to develop an intuition, I will begin from the beginning: The Multi-layer Perceptron, and build upwards from there. 

I want to understand how, at each stage in the evolution of LLM precursor models, certain architectural choices were made, which eventually led to the attention mechanism. 

My understanding will be from a causality perspective. 

I will:
- Build strong intuition for how RNNs and LSTMs are trained
- Understand **where** and **how** backpropagation updates weights in RNNs
- Recreate LSTM from scratch using NumPy to solidify memory mechanics
- Create annotated visuals for gate-level understanding
- Make this repo self-contained and helpful for others


What I will explore (not limited to):

- **How feedforward networks (MLPs) map inputs to outputs**
- **Why RNNs were introduced** to handle sequences
- **How RNNs update hidden states and weights over time**
- **Where they fail (vanishing gradients) and how LSTMs fix it**
- **Detailed breakdown of LSTM gates (input, forget, output)**
- **Variants like GRUs and Bidirectional RNNs**
