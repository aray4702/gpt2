The is the result of my learning results of Karpathy's from zero to hero courses.

1. micrograd [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aray4702/transformer/blob/main/notebooks/micrograd.ipynb)

2. makemore optimization [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aray4702/transformer/blob/main/notebooks/makemore_optimization.ipynb)

3. makemore wavenet [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aray4702/transformer/blob/main/notebooks/makemore_wavenet.ipynb)

4. gpt [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aray4702/transformer/blob/main/notebooks/gpt.ipynb)

5. tokenizer [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aray4702/transformer/blob/main/notebooks/makemore/tokenizer.ipynb)

6. reproduce gpt-2 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aray4702/transformer/blob/main/notebooks/reproduce-gpt2.ipynb)

7. td learning [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aray4702/transformer/blob/main/notebooks/td.ipynb)

8. mcts [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aray4702/transformer/blob/main/notebooks/mcts.ipynb)


** next step
# gpt2
** plan **
1. write a doc to explain gpt2 and my training process
2. describe how it is evaluated
3. compare it with OpenAI's gpt2, gpt3, and gpt4

# transformer

- attention

$$softmax(\frac{K \times Q^T}{\sqrt{d_{head}}})\times V$$

- architecture
```mermaid
flowchart TD
X[prediction head]---A
subgraph tranformer block 
A[mlp]---B[self attention]
end
B---C[positional encoding]---D[embedding layer]---E([token sequene])
```
