## 🧠 Proposed Methodology
This research introduces two distinct paradigms for reservoir optimization:

### 1. Supervised Optimization Model
In this model, we move beyond random initialization by incorporating an iterative refinement process.
- **Mechanism:** Uses error gradients (Backpropagation) to adjust the internal reservoir weight matrix ($W$).
- **Key Insight:** Demonstrates how connection weights evolve and sparsify during training to minimize NRMSE.
- **Visualization:** See `supervised_architecture.png` in the results folder.

### 2. Semi-Supervised Hybrid Model
A novel approach combining Complex Network Theory with Hyperparameter Optimization (HPO).
- **Topology:** Integrates **Small-World** (Watts-Strogatz) for local clustering and **Scale-Free** (Barabási-Albert) for efficient global information flow.
- **Optimization:** Utilizes Direct and Inverse Parameter Prediction to find the optimal mixing ratio ($\alpha$) and connectivity parameters.
- **Visualization:** Refer to `network_metrics_analysis.png` for a comparative study of network indices.
