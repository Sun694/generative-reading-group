###latent_skip_notes.pdf: https://arxiv.org/abs/1807.04863

Summary: Connect your latent space to your decoder using skip connections.

Empirical uses and problems solved: Helps avoid posterior collapse. Reinforces corrolation between Z and X.


###discreteflows.pdf: https://arxiv.org/abs/1905.10347

Summary: Use normalizing flows, but discrete.

Empirical uses and problems solved: Extremely fast when compared to continuous flows. Useful for discrete data.


###balancing_reconstruction.pdf: https://arxiv.org/abs/1909.03765

Summary: Weight your reconstruction loss less when your data is noisy

Empirical uses and problems solved: "Removes" KL annealing for VAEs. Better preformance on all benchmarks when compared to more traditional VAEs.
