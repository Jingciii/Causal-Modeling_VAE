# Causal Model -- VAE
CS 7290 Project: Causal Modeling with a Variational Autoencoder

### Project Goal

Refactor the provided program such that there is a causal relationship between the given variables.

What would the image be like if we change something?


### Confusions during Development

 -  Where is the DAG? How to find it?
 -  Which part to refactor?
 -  What is the use of SCM?

 
## Timeline

**Pre-launching**


*Week 1*

- [x] Topic Determination 
- [x] Literature Reviews

*Week 2*

- [x] Literature Reviews
- [x] Task Assignment

**Developing**	

*Week 3*

- [x] Understanding the pyro tutorial for creating, training, and making inference on VAE models
- [x] De-noising exogenous variables for image representations in SCM (stochastic causal model)

*Week 4*

- [x] Fine-tuning Encoder and Decoder in VAE model for refactoring
- [x] Training the model so that the orignial images can be reconstructed
- [x] Creating conditioned model on one of the labels
- [x] Intervening on the conditioned model by applying do-operation on the other labels
- [x] Visualizing results and drawing insights from them

**Post-development**
 

 
 *Week 5*
 
 - [x] Formatting the notebook
 - [x] Ready for presentation


### References

[Understanding VAEs](https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73)

[Tutorial Provided By TA](https://github.com/robertness/causalML/blob/master/tutorials/causal_vae_dsprites.ipynb)

[Pyro Documentation](http://docs.pyro.ai/en/stable/contrib.cevae.html)

[An Introduction to Variational Autoencoders](https://arxiv.org/pdf/1906.02691.pdf)

[Robustly Disentangled Causal Mechanisms: Validating Deep Representations for Interventional Robustness](https://arxiv.org/pdf/1811.00007.pdf)

[Causal Effect Inference with Deep Latent-Variable Models](https://arxiv.org/pdf/1705.08821.pdf)

<!---[Causal Analysis of an Agent-Based Model of Human Behaviour](http://downloads.hindawi.com/journals/complexity/2017/8381954.pdf)

[Agent-Based Models for Causal Inference](https://dash.harvard.edu/bitstream/handle/1/27201721/MURRAY-DISSERTATION-2016.pdf?sequence=3&isAllowed=y)

[Picture: A Probabilistic Programming Language for Scene Perception](https://mrkulk.github.io/www_cvpr15/1999.pdf)

[Approximate Bayesian Image Interpretation using
Generative Probabilistic Graphics Programs](https://arxiv.org/pdf/1307.0060v1.pdf)--->
