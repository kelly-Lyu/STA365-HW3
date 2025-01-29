# STA365-HW3
This repository contains solutions and explanations for key problems in Bayesian inference and computational statistics. The focus is on deriving posterior distributions, implementing Gibbs samplers, and exploring Bayesian model properties.

Questions Overview

Q1: Implementing a Gibbs Sampler
This question focuses on implementing a Gibbs sampler for a Bayesian model with priors
p
(
θ
,
τ
)
∝
1
p(θ,τ)∝1. The Gibbs sampler alternates between sampling from full conditionals for 
θ
θ and 
τ
τ, where 
τ
τ follows a Gamma distribution and 
θ
θ follows a Normal distribution. The repository includes code and examples to demonstrate Bayesian inference with arbitrary data.

Q2: Full Conditional Distributions and Prior Effects
In this question, the full conditional distributions 
p
(
τ
∣
θ
,
x
)
p(τ∣θ,x) and 
p
(
θ
∣
τ
,
x
)
p(θ∣τ,x) are derived for a Bayesian model with Normal and Gamma priors. It explores how prior hyperparameters (
α
α and 
λ
λ) influence the posterior distribution by controlling the balance of prior information and likelihood. The updated Gibbs sampler implementation demonstrates these effects in practice.

Q3: Posterior Derivation for Multinomial-Dirichlet and Beta-Bernoulli Models
This question involves deriving the posterior for a Multinomial-Dirichlet model and the Beta-Bernoulli model using Bayes' theorem. The solutions illustrate how the posterior retains the same functional form as the prior (conjugacy). Applications and intuition for using these models in categorical and binary data settings are included.
