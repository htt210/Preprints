# Preprints
Store my working papers and incomplete ideas. 

## [Toward a Generalization Metric for Deep Generative Latent Variable Models](DGLVM_Generalization_Metric.pdf)
*Abstract* 

Deep Generative Latent Variable Models (DGLVMs) are generative models (GMs) that use deep neural networks to transform a latent distribution to another distribution that approximates a target distribution.
The generalizability of a DGLVM depends on the generalizability of the generator network, which is very hard to measure correctly.
Although a number of evaluation metrics for generative models have been proposed, they are not designed to measure generalization.
In this paper, we develop a tool for comparing the ability to measure generalization of evaluation metrics.
We introduce the concept of \textit{breaking number} $(BN)$ - the size of the smallest dataset that can fool an evaluation metric - and show that BNs correlate to the robustness of evaluation metrics.
Inspired by the Minimum Description Length principle, we propose to measure the quality of DGLVMs in 2 parts: fitness and complexity. Experimental results show that our metric has better discriminative power and is more robust than existing metrics.

