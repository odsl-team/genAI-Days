# Tuesday: Flow Matching 

**Morning mini-lecture:** Continuous normalizing flows
- The flow is parametrized as a ODE now with a NN as a velocity field

**Tutorial:** `01_continuous_flow.ipynb`
- Let's code this up
- Key concept: Use standard ODE solvers to integrate the NN to
     (1) Get the likelihood [for training]
     (2) Draw samples [for evaluation]

**Afternoon mini-lecture:**
- New loss function for matching (regressing) these **velocity fields**
- Most of the plots in this lecture are made in `Lecture-nb.ipynb`

**Tutorial:** `02_flow_matching.ipynb`
- Binary black hole mergers, revised :)
- This model takes some time to train, strongly recomment collab with the gpu backend here

 [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/odsl-team/genAI-Days/blob/main/)
