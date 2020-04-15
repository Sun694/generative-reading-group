### week 2: w2_latent_skip_notes.pdf: https://arxiv.org/abs/1807.04863

Summary: Connect your latent space to your decoder using skip connections.

Empirical uses and problems solved: Helps avoid posterior collapse. Reinforces corrolation between Z and X.


### week 3: w3_discrete_flows.pdf: https://arxiv.org/abs/1905.10347

Summary: Use normalizing flows, but discrete.

Empirical uses and problems solved: Extremely fast when compared to continuous flows. Useful for discrete data.


### week 4: w4_balancing_reconstruction.pdf: https://arxiv.org/abs/1909.03765

Summary: Weight your reconstruction loss less when your data is noisy

Empirical uses and problems solved: "Removes" KL annealing for VAEs. Better preformance on all benchmarks when compared to more traditional VAEs.


### week 5: w5_challenging_assumptions.pdf: https://arxiv.org/abs/1811.12359

Summary: Disentanglment is a scam

Empirical uses and problems solved: Don't care too much about disentanglment. It doesn't matter that much in alot of cases. More research required. Better metrics required.

### week 6: w6_adversarial autoencoders.pdf: https://arxiv.org/abs/1511.05644

Summary: If you're willing to have a discriminator, any prior can be used for a VAE.

Empirical uses and problems solved: If you want a weird prior that is easy to sample from, but that does not have a closed-form / computationally efficient KL term, consider using a discriminator. 

### week 7: w7_conditional_priors.pdf: https://arxiv.org/abs/1911.10885

Summary: If you have data that has distinct rough-grained modes, encorperate a "modality predictor" into your latent representation.

Empirical uses and problems solved: Seemingly useful for rough-grained data, but no uses were presented in high dimension.

### week 8: w8_multilingual_translation.pdf: https://arxiv.org/abs/2002.02955

Summary: Using expectation maximization, you can train unsupervised machine translation models suprisingly well.

Empirical uses and problems solved: SOTA in some tasks for unsupervised machine translation, provides a moral derivation of the backtranslation optimization.

## week 10: w10_BERT.pdf: https://arxiv.org/abs/1810.04805

Summary: Masked language modeling is able to produce extremely powerful models.

Empirical uses and problems solved: SOTA in 11 tasks at time of publication. Still used today due to extreme flexability. Very good model.