### week 2: anokhi_w02_hamiltonian_generative_networks.pdf: https://arxiv.org/abs/1909.13789

Summary: You can draw paralells between generative networks and the Hamiltonian.

Empirical uses: You can use them as modified normalizing flow with some benefits.

### week 3: anokhi_w03_thermodynamic_variational_objective.pdf.pdf: https://arxiv.org/abs/1907.00031

Summary: You can generalize the ELBO by drawing from thermodynamics.

Empirical uses: Better performance in some situations when using the extensions.

### week 4: anokhi_w04_tighter_variational_bounds_are_not_necessarily_better.pdf: https://arxiv.org/abs/1802.04537

Summary: Theoretical and empirical proof that tighter variational bounds can result in worse performance.

### week 9: anokhi_w09_wasserstein_autoencoders.pdf: https://arxiv.org/abs/1711.01558

Summary: Autoencoder extension that brings the magic of Wasserstein optimization.

Empirical uses: Arguably, much better theoretical justification than VAEs. Better opimization.

### week 12: anokhi_w12_variational_to_deterministic_autoencoders.pdf: https://arxiv.org/abs/1903.12436

Summary: Regularize your AEs, don't use VAEs.

Empirical uses: RAEs are as good as VAEs, but without alot of the bad aspects (posterior collapse). 

### week 15: anokhi_w15_vqvae2.pdf: https://arxiv.org/abs/1906.00446

Summary: VQVAE 2: Back and better than before. Slight changes, better results.

Empirical uses: If you need a good VAE, there's no better (May 2020).

### week 2: sun694_w02_latent_skip_notes.pdf: https://arxiv.org/abs/1807.04863

Summary: Connect your latent space to your decoder using skip connections.

Empirical uses: Helps avoid posterior collapse. Reinforces corrolation between Z and X.

### week 4:  sun694_w04_balancing_reconstruction.pdf: https://arxiv.org/abs/1909.03765

Summary: Weight your reconstruction loss less when your data is noisy

Empirical uses: "Removes" KL annealing for VAEs. Better preformance on all benchmarks when compared to more traditional VAEs.

### week 5:  sun694_w05_challenging_assumptions.pdf: https://arxiv.org/abs/1811.12359

Summary: Disentanglment is a scam

Empirical uses: Don't care too much about disentanglment. It doesn't matter that much in alot of cases. More research required. Better metrics required.

### week 6:  sun694_w06_adversarial_autoencoders.pdf: https://arxiv.org/abs/1511.05644

Summary: If you're willing to have a discriminator, any prior can be used for a VAE.

Empirical uses: If you want a weird prior that is easy to sample from, but that does not have a closed-form / computationally efficient KL term, consider using a discriminator. 

### week 7:  sun694_w07_conditional_priors.pdf: https://arxiv.org/abs/1911.10885

Summary: If you have data that has distinct rough-grained modes, encorperate a "modality predictor" into your latent representation.

Empirical uses: Seemingly useful for rough-grained data, but no uses were presented in high dimension.