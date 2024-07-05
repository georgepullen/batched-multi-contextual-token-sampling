# Batched Multi-Contextual Token Sampling
A significantly faster implementation of my novel 'needle in a haystack' methodology for SLMs.

![image](https://github.com/georgepullen/batched-multi-contextual-token-sampling/assets/90179633/c50a4f1c-89d0-4871-8be6-46c48e2763a6)

# Improvements over Linear Multi-Contextual Token Sampling
* Testing with an RTX 3090 (24GB) shows approximately **30K tokens** can be considered when generating a **25 token response** with a **10 second** constraint
* This is a **50% increase** from Linear MCTS which could only consider **20K tokens** when generating a **25 token response** in **10 seconds**
