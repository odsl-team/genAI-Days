# Tuesday: Flow Matching 

**Morning mini-lecture:** Continuous normalizing flows
- The flow is parametrized as a ODE now with a NN as a velocity field


**Tutorial:** `continuous_norm_flow.ipynb`
- Let's code this up
- Key concept: Use standard ODE solvers to integrate the NN to
     (1) Get the likelihood [for training]
     (2) Draw samples [for evaluation]
- **TO DO:** Add this tutorial in jax as well


**Afternoon mini-lecture:**
- New loss function for matching (regressing) these **velocity fields**
- Most of the plots in this lecture are made in `Lecture-nb.ipynb`

**Tutorial:** `flow_matching.ipynb`
- Binary black hole mergers, revised :)