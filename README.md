# Semeru Guidelines
> Semeru Data and Machine Guidelines

- Checkout our [wiki](https://github.com/WM-SEMERU/semeru_guidelines/wiki) for machine deployment and setup.
- Software Engineering Empirical Standards [[web]](https://acmsigsoft.github.io/EmpiricalStandards/docs/)

# Semeru Projects
Project | Managers | Contributors | Topic | Description
---|---|---|---|--- 
[TraceXplainer](https://github.com/WM-SEMERU/traceXplainer) | David | Yanfu, Daniel | DL4SE, Interpretability | Software Retrieval Interpretability
DeepCodeXplainer | Alvaro, David | Daniel | DL4SE, Interpretability | Deep Code Generator Explainer: Unconditioned open-ended generation of code
iCodeGen | David | Nathan | DL4SE, Interpretability | Conditioned interpretability of neural language models
[CodeShot](https://github.com/WM-SEMERU/code_review_4_vulnerability) | Daniel, David | Dipin | DL4SE, Security | Few-Shot Learners for Code Summarization
CodeCapability | Alejandro, David | ? | DL4SE, Evaluation | Capabilities for evaluating neural language models
[Athena](https://github.com/WM-SEMERU/athena) | Yanfu | Nathan | DL4SE, CodeSearch | A graph architecture for code search
Tango | Yanfu | Nathan | ? | ?
[CodeProbing](https://github.com/WM-SEMERU/CodeProbing) | Daniel, David | ? | DL4SE | Probing Compositionality and Uniquiness of Unconditioned Code Generation
[MASC-Ext](https://github.com/Secure-Platforms-Lab-W-M/MASC-Artifact) | Amit | Nathan | Security, Crypto-Detector | Extending MASC - Mutation Analysis for evaluating Static Crypto-API misuse detectors
x | Amit | - | Security, SE | Security Tools in Practice

# The Neophyte's Guide to Deep Learning 4 Software Engineering
> By @computoloco

## DL4SE Basics
- A Systematic Literature Review on the Use of Deep Learning in Software Engineering Research [[web]](https://ml4code.github.io/publications/watson2021systematic/)
![checklist](https://user-images.githubusercontent.com/8354015/169404571-fb7a8d05-f501-4ebe-a02e-68617cd90281.png)

## DL Basics
- Deep Learning for Coders [[fast.AI]](https://www.fast.ai/)
- Natural Language Tutorial for DL Researchers [[tutorial]](https://github.com/graykode/nlp-tutorial)
- The Super Duper NLP Repo [[repo]](https://notebooks.quantumstat.com/)

## DL Approaches
### Convolutional Nets
1. CNNs from different viewpoints [[web]](https://medium.com/impactai/cnns-from-different-viewpoints-fab7f52d159c)
2. How convolutional neural networks work, in depth [[web]](https://www.youtube.com/watch?v=JB8T_zN7ZC0)
3. Deep Learning Tips and Tricks cheatsheet [[web]](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-deep-learning-tips-and-tricks)
4. Convolutional Neural Networks cheatsheet [[web]](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-convolutional-neural-networks)
5. An Interactive Node-Link Visualization of Convolutional Neural Networks [[demo]](http://www.cs.cmu.edu/~aharley/vis/)
6. ConvNetJS MNIST [[demo]](https://cs.stanford.edu/people/karpathy/convnetjs/demo/mnist.html)
7. A guide to convolution arithmetic for deep learning [[paper]](https://arxiv.org/pdf/1603.07285.pdf)
8. Understanding Deep Residual Networks [[web]](https://shuzhanfan.github.io/2018/11/ResNet/)

### Stochastic Nets
1. Introduction to Restricted Boltzmann Machines [[web]](http://blog.echen.me/2011/07/18/introduction-to-restricted-boltzmann-machines/)
2. Monte Carlo Methods and Importance Sampling [[Lecture]](http://ib.berkeley.edu/labs/slatkin/eriq/classes/guest_lect/mc_lecture_notes.pdf)
3. Expectation Maximization (EM) [[blog]](https://karinknudson.com/expectationmaximization.html)

### Recurrent Nets
1. Illustrated Guide to Recurrent Neural Networks: Understanding the Intuition [[YT]](https://www.youtube.com/watch?v=LHXXI4-IEns)
2. Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) [[YT]](https://www.youtube.com/watch?v=WCUNPb-5EYI)
3. Recurrent Neural Networks cheatsheet [[web]](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)
4. The Illustrated Word2vec [[blog]](https://jalammar.github.io/illustrated-word2vec/)
5. Embedding Projector [[demo]](http://projector.tensorflow.org/)
6. Understanding LSTM Networks [[blog]](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
7. Illustrated Guide to LSTM's and GRU's: A step by step explanation [[YT]](https://www.youtube.com/watch?v=8HyCNIVRbSU)

### Transformers
1. Practicum: Attention and the Transformer [[YT]](https://www.youtube.com/watch?v=f01J0Dri-6k)
2. Understanding Transformers, the Data Science Way [[blog]](https://www.kdnuggets.com/2020/10/understanding-transformers-data-science-way.html)
3. The Illustrated Transformer [[blog]](https://jalammar.github.io/illustrated-transformer/)
4. The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning) [[blog]](https://jalammar.github.io/illustrated-bert/)
5. The Annotated Transformer [[web]](http://nlp.seas.harvard.edu/2018/04/03/attention.html)

### Few-shot Learning:
- (2022) Flamingo [[paper]](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model) [[code]](https://github.com/lucidrains/flamingo-pytorch)
- Language Models are Few-Shot Learners [[paper]](https://arxiv.org/pdf/2005.14165.pdf)

### AutoEncoders
1. Building Autoencoders in Keras [[blog]](https://blog.keras.io/building-autoencoders-in-keras.html)
2. AutoenCODE [[repo]](https://github.com/micheletufano/AutoenCODE)
3. Autoencoder - denoising autoencoder [[YT]](https://www.youtube.com/watch?v=t2NQ_c5BFOc)
4. Autoencoder - contractive autoencoder [[YT]](https://www.youtube.com/watch?v=79sYlJ8Cvlc)
5. Ali Ghodsi, Lec : Deep Learning, Variational Autoencoder [[YT]](https://www.youtube.com/watch?v=uaaqyVS9-rM)
6. Deep learning - variational bound [[YT]](https://www.youtube.com/watch?v=pStDscJh2Wo)
7. Variational_AutoEncoder [[YT]](https://www.youtube.com/playlist?list=PLdxQ7SoCLQANizknbIiHzL_hYjEaI-wUe)
8. vae_maths [[repo]](https://github.com/AndrewSpano/Disentangled-Variational-Autoencoder/blob/main/mathematical_analysis/vae_maths.pdf)
9. Practicum: Variational autoencoders [[YT]](https://www.youtube.com/watch?v=7Rb4s9wNOmc)
10. Generative Models - Variational Autoencoders [[book]](https://atcold.github.io/pytorch-Deep-Learning/en/week08/08-3/)
11. Introducing Variational Autoencoders [[blog]](https://blog.fastforwardlabs.com/2016/08/12/introducing-variational-autoencoders-in-prose-and-code.html)
12. NSynth: Neural Audio Synthesis [[blog]](https://magenta.tensorflow.org/nsynth)
13. An Introduction to Variational Autoencoders [[paper]](https://arxiv.org/pdf/1906.02691.pdf)
14. Understanding Variational Autoencoders (VAEs) [[blog]](https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73)

### Adversarial NETS
1. GANs [[web]](https://developers.google.com/machine-learning/gan)
2. Generative adversarial networks [[YT]](https://www.youtube.com/watch?v=xYc11zyZ26M)
3. Understanding Generative Adversarial Networks (GANs) [[blog]](https://towardsdatascience.com/understanding-generative-adversarial-networks-gans-cd6e4651a29)
4. GAN Lab [[demo]](https://poloclub.github.io/ganlab/)
5. Generative Adversarial Networks [[tutorial]](https://arxiv.org/pdf/1701.00160.pdf)

## DL Influential Work
Authors | Paper | Topic
---|---|---
Krizhevsky.2012 |	ImageNet Classification with Deep Convolutional Neural Networks |	Convolutional
Zeiler.2013 |	Visualizing and Understanding Convolutional Networks | Convolutional
He.2015 |	Deep Residual Learning for Image Recognition | Convolutional
Salakhutdinov.2007 |	Semantic Hashing |	Stochastic
Tang.2013 |	A New Learning Algorithm for Stochastic Feedforward Neural Networks	| Stochastic
Hochreiter.1997	| Long Short-term Memory |	Recurrent
Mikolov.2012 |	Statistical Language Models Based on Neural Networks (Chap. 1-4) |	Recurrent
Mikolov.2013 |	Efficient Estimation of Word Representations in Vector Space |	Recurrent
Vaswani.2017 |	Attention Is All You Need |	Transformer
Devlin.2019 |	BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding |	Transformer
Socher.2011b |	Semi-Supervised Recursive Autoencoders for Predicting Sentiment Distributions	| Autoencoder
White.2016 |	Deep Learning Code Fragments for Code Clone Detection |	Autoencoder
Vincent.2008 |	Extracting and Composing Robust Features with Denoising Autoencoders	| Autoencoder
Engel.2017 |	Neural Audio Synthesis of Musical Notes with WaveNet Autoencoders |	Autoencoder
Kingma.2014	| Auto-Encoding Variational Bayes |	Autoencoder
Higgins.2017 |	beta-VAE: Learning Basic Visual Concepts with a Constrained Variational Framework	| Autoencoder
Goodfellow.2014 |	Generative Adversarial Nets |	Adversarial


