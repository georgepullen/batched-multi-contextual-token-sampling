# Batched Multi-Contextual Token Sampling
A significantly faster implementation of my novel 'needle in a haystack' methodology for SLMs.

![image](https://github.com/georgepullen/batched-multi-contextual-token-sampling/assets/90179633/c50a4f1c-89d0-4871-8be6-46c48e2763a6)

# Performance Improvements over Linear MCTS

| Aspect | Batched Multi-Contextual Token Sampling | Linear Multi-Contextual Token Sampling |
|--------|----------------------------------------|----------------------------------------|
| Tokens considered | 30K | 20K |
| Response length | 25 tokens | 25 tokens |
| Time constraint | 10 seconds | 10 seconds |
| Performance | 50% increase | Baseline |
| Hardware | RTX 3090 (24GB) | RTX 3090 (24GB) |
