# foundations for deep learning:
1. I emphasize mathematical/conceptual foundations because implementations of ideas(ex. Torch, Tensorflow)
   will keep evolving but the underlying theory must be sound. Anybody with an interest in deep learning 
   can and should try to understand why things work. 
2. I include neuroscience as a useful conceptual foundation for two reasons. First, it may provide inspiration
   for future models and algorithms. Second, the success of deep learning can contribute to useful hypotheses
   and models for computational neuroscience. 
3. Information Theory is also a very useful foundation as there's a strong connection between data compression
and statistical prediction. In fact, data compressors and machine learning models approximate Kolmogorov Complexity
which is the ultimate data compressor. 

You might notice that I haven't emphasized the latest benchmark-beating paper. My reason for this is that a good
theory ought to be scalable which means that it should be capable of explaining why deep models generalise and we
should be able to bootstrap these explanations for more complex models(ex. sequences of deep models(aka RNNs)).
This is how all good science is done. 

### For an excellent historical overview of deep learning, I would recommend reading [Deep Learning in Neural Networks](https://github.com/pauli-space/foundations_for_deep_learning/blob/master/deep_learning/history_of_deep_learning/deep_learning_in_neural_networks.pdf) as well as R. Salakhutdinov's [Deep Learning Tutorials](https://www.youtube.com/watch?v=-SY4-GkDM8g&t=4s). 

## Deep Learning:
1. History:
	* Deep Learning in Neural Networks: An Overview (J. Schmidhuber. 2015. Neural Networks.)
2. Optimisation:
	* Learning Internal Representations by Error Propagation(D. Rumelhart et al. 1996. MIT Press ) 
	* Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift(S. Ioffe. 2015. ICML.)
	* Weight Normalization (Salimans 2016. NIPS.)
	* Bayesian Back-Propagation (W. Buntine & A. Weigend 1991. )
	* Credit Assignment through Time: Alternatives to Backpropagation (Y. Bengio. 1993. NIPS.)
3. Regularisation:
	* Dropout: A Simple Way to Prevent Neural Networks from Overfitting (N. Srivastava et al. 2014. Journal of Machine Learning Research.)
	* Why Does Unsupervised Pre-training Help Deep Learning? (D. Erhan et al. 2010. Journal of Machine Learning Research.)
4. Inference:
	* Uncertainty in Deep Learning(Yarin Gal. 2017. University of Cambridge.)
	* Mixture Density Networks (Bishop 1994)
	* Dropout as a Bayesian Approximation(Yarin Gal 2016. ICML. )
	* Markov Chain Monte Carlo and Variational Inference: Bridging the Gap (Salimans. 2015. ICML.)
	* Auto-Encoding Variational Bayes (D. Kingma & M. Welling. 2014. ICLR.)
	* Variational Dropout and the Local Reparameterization Trick (D. Kingma, T. Salimans & M. Welling. 2015. NIPS.)
	* Avoiding pathologies in very deep networks (D. Duvenaud et al. 2014. AISTATS.)
	* Stochastic Gradient Hamiltonian Monte Carlo (T. Chen. 2014. ICML.)
	* On Sparse Variational Methods and the Kullback-Leibler Divergence between Stochastic Processes(A. Matthews et al. 2016. AISTATS.)
5. Deep Generative Models:
	* Learning Deep Generative Models(Salakhutdinov. 2015. Annual Review of Statistics and Its Application.)
	* Learning Disentangled Representations with Semi-Supervised Deep Generative Models (N. Siddarth et al. 2017.)
	* Generative Adversarial Nets (I. Goodfellow et al. NIPS. 2014.)
6. Continual Learning:
	* Long Short-Term Memory (S. Hochreiter & J. Schmidhuber. Neural Computation. 1997.)
	* Overcoming catastrophic forgetting in neural networks (J. Kirkpatrick et al. PNAS. 2017.)
7. Hyperparameter Optimization:
	* Taking the Human Out of the Loop: A Review of Bayesian Optimization (B. Shahriari et al. Proceedings of the IEEE. 2016.)
	* Convolution by Evolution (C. Fernando et al. GECCO. 2016.)

## Mathematical papers:
1. Dropout Rademacher Complexity of Deep Neural Networks(Wei Gao 2015. Science China Information Sciences.)
2. Distribution-Specific Hardness of Learning Neural Networks(Shamir 2017. CoRR.)
3. Lessons from the Rademacher Complexity for Deep Learning(Sokolic 2016.ICLR.) 
4. A mathematical theory of Deep Convolutional Neural Networks for Feature Extraction(Wiatowski 2016. CoRR.)
5. Spectral Representations for Convolutional Neural Networks(Rippl 2015. NIPS.)
6. Electron-Proton dynamics in deep learning(Zhang 2017. CoRR.)       
7. Empirical Risk Minimization for Learning Theory(Vapnik 1991. NIPS.)
8. The Loss Surfaces of Multilayer Networks(Y LeCun et al. 2015. AISTATS.)
9. Understanding Synthetic Gradients and Decoupled Neural Interfaces(W. Czarnecki 2017. CoRR.)
10. Dataset Shift(Storkey 2013)
11. The loss surface of deep and wide neural networks(Q. Nguyen 2017)
12. A Differential Equation for Modeling Nesterov’s Accelerated Gradient Method(W. Su 2016. Journal of Machine Learning Research.)
13. The Physical Systems behind Optimization (L. Yang et al. 2017.)
14. Simple Explanation of the No-Free-Lunch Theorem and Its Implications (Y. Ho. 2002. Journal of optimization theory and applications.)
15. Adam: A method for Stochastic Optimization (D. Kingma 2015. ICLR.)
16. On the ability of neural nets to express distributions （H. Lee, R. Ge, T. Ma, A. Risteski & S. Arora, 2017）

## Information Theory papers:
1. Shannon Information and Kolmogorov Complexity (Grunwald 2010)
2. Discovering Neural Nets with Low Kolmogorov Complexity(Schmidhuber 1997. Neural Networks.) 
3. Opening the black box of Deep Neural Networks via Information (Schwartz-Ziv 2017.)                                    

## Neuroscience papers:
1. Towards an integration of deep learning and neuroscience(Marblestone 2016. Frontiers in Computational Neuroscience.)
2. Equilibrium Propagation(Scellier 2016. Frontiers in Computational Neuroscience.)
3. Towards Biologically plausible deep learning(Bengio 2015. CoRR.)
4. Random synaptic feedback weights support error backpropagation for deep learning(Lillicrap 2016. Nature communications.)
5. Towards deep learning with spiking neurons(Mesnard 2016. NIPS.)
6. Towards deep learning with spiking dendrites(Guergiuev 2017)
7. Variational learning for recurrent spiking networks(Rezende 2011. NIPS.)
8. A view of Neural Networks as dynamical systems(Cessac 2009. I. J. Bifurcation and Chaos)

### Note: This is a work in progress. I have a lot more papers to add.

