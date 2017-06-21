# ML-ReadingGroup
*(Short URL to here: https://j.mp/MLReadingGroup)*

Resources (including transcripts) for the Reading Group on (IRC -> Freenode -> ##machinelearning)  
Reading Group is currently every 2-3 Sundays! Keep an eye on the channel topic!  
Talk to p-i- on the main channel for more info.  


## Next discussion: Sunday ? June? 2017 @ [7pm UTC](https://www.wolframalpha.com/input/?i=Sunday+7+pm+UTC)

Open to ideas. Maybe we should cover the main directions/areas in ML before drilling into anything too specific??


## Candidates for future discussions (most recent/best first):
* [Learning to act by predicting the future](https://openreview.net/pdf?id=rJLS7qKel)  
* [Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1602.01783)  
* [DNC](https://github.com/deepmind/dnc) (Differentiable Neural Computer)
* Learning without Backpropagation http://www.breloff.com/no-backprop/
* [Overcoming catastrophic forgetting in neural networks](https://arxiv.org/abs/1612.00796)
* [Semi-Supervised Learning with Ladder Networks](https://arxiv.org/abs/1507.02672)
* [The Reactor: A Sample-Efficient Actor-Critic Architecture](https://arxiv.org/abs/1704.04651) (15 Apr '17)
* [Grid Long-Short--Term Memory](https://arxiv.org/pdf/1507.01526.pdf) (tomzx offers to host)
* (NIPS '14) https://research.googleblog.com/2014/12/advances-in-variational-inference.html (tx tfunnell)
* http://videolectures.net/course_information_theory_pattern_recognition/ [on YouTube](https://www.youtube.com/watch?v=BCiZc0n6COY&list=PLruBu5BI5n4aFpG32iMbdWoRVAA-Vcso6)
  Maybe take apart 2 videos per week (tx rofer)


## Past discussions (newest at top):

* [Human-level control through deep reinforcement learning](https://www.nature.com/nature/journal/v518/n7540/full/nature14236.html) ([PDF](https://pdfs.semanticscholar.org/340f/48901f72278f6bf78a04ee5b01df208cc508.pdf))  
[log](logs/2017.06.18_DeepRL)

  Led by Lyote (tx Lyote)!  

  Resources:  
    * Source code: https://github.com/deepmind/dqn (Source code is LUA)
    * https://keon.io/deep-q-learning/ -- leads to Python source code!
    * Matiisen: [RL Primer](https://www.nervanasys.com/demystifying-deep-reinforcement-learning/)
    * Karpathy: [Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/)
    * Simple implementation (by Lyote with minor refactoring & doc by p-i-) of a tabular RL agent which learns to play Tic Tac  Toe [here](https://github.com/Lyote/TicTacToe-RL)
    * [David Silver's RL course (10 vids)](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)


* 2017.05.28 [NTM](https://arxiv.org/abs/1410.5401) (Neural Turing Machines)  
  [log](logs/2017.05.28_NTMs)  
  
  ([slides](http://klab.smpp.northwestern.edu/wiki/images/4/43/NTM2.pdf))  
  ([Old keras code for layer by EderSanta](https://github.com/EderSantana/seya/blob/master/seya/layers/ntm.py))  
  ([Old keras example by EderSanta](https://github.com/EderSantana/seya/blob/master/examples/NTM.ipynb))

  A [nice little talk](https://www.youtube.com/watch?v=_H0i0IhEO2g) by the first author of the NTM paper that gives a high-level description of the architecture. 
  
  [PyTorch implementation](https://github.com/HenryJia/seya_pytorch/blob/master/NTM.ipynb) by Henry Jia.


* 2017.05.07 VAE (Variational AutoEncoders)  
  [log](logs/2017.05.07_VAE)

  * Main paper: [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)  

  Resources (roughly in order they should be approached):  

  * Eric Jang
    * [A Beginner's Guide to Variational Methods: Mean-Field Approximation](http://blog.evjang.com/2016/08/variational-bayes.html)

  * Variational Autoencoders (in Prose and Code) by Miriam.
    * [PART 1: Introducing Variational Autoencoders (in Prose and Code) by Miriam](http://blog.fastforwardlabs.com/2016/08/12/introducing-variational-autoencoders-in-prose-and.html)
    * [PART 2: Under the Hood of the Variational Autoencoder (in Prose and Code) by Miriam](http://blog.fastforwardlabs.com/2016/08/22/under-the-hood-of-the-variational-autoencoder-in.html).
    * [code on GitHub](https://github.com/fastforwardlabs/vae-tf/tree/master)

  * Jaan Altosaar
    * [Tutorial - What is a variational autoencoder by Jaan Altosaar](https://jaan.io/what-is-variational-autoencoder-vae-tutorial/)
    * [A very clean Tensorflow implementation](https://github.com/altosaar/vae/blob/master/vae.py)

  * [(ArXiv Doersch, June '16) Tutorial on Variational Autoencoders](https://arxiv.org/abs/1606.05908)  

  * Variational Autoencoders by Vu Pham (elaborates on Doersch)
    * [Variational Autoencoders 1: Overview](https://phvu.net/2017/02/26/variational-autoencoders-1-overview/)
    * [Variational Autoencoders 2: Maths](https://phvu.net/2017/04/02/variational-autoencoders-2-maths/)
    * [Variational Autoencoders 3: Training, Inference and comparison with other models](https://phvu.net/2017/04/02/variational-autoencoders-3-training-inference-and-comparison-with-other-models/)

  * [(ArXiv Blei, Nov '16) Variational Inference: A Review for Statisticians](https://arxiv.org/abs/1601.00670)

  * VIDEO: [(DeFreitas)Deep Learning Lecture 14: Karol Gregor on Variational Autoencoders and Image Generation](https://www.youtube.com/watch?v=P78QYjWh5sM) <-- deriving the theory from an information theoretic perspective (ouch?)


* 2017.04.23 GANs: Goodfellow's 2014 "Generative Adversarial Networks" [paper](https://arxiv.org/abs/1406.2661)  
  [log](logs/2017.04.23)  
  Resources:
     - [NIPS 2016 Tutorial: Generative Adversarial Networks](https://arxiv.org/abs/1701.00160)
     - http://blog.evjang.com/2016/06/generative-adversarial-nets-in.html
     - [Goodfellow @ NIPS '16 (+6 other vids on GAN)](https://www.youtube.com/watch?v=RvgYvHyT15E&list=PLJscN9YDD1buxCitmej1pjJkR5PMhenTF)     
     - Stacked GANs:  
        - [Stacked Generative Adversarial Networks](https://arxiv.org/abs/1612.04357) <-- Can anyone grok fig.1??  
        - [StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks](https://arxiv.org/abs/1612.03242)  
        ^ note both papers were submitted within three days one another (10/13 Dec '16)  


* 2017.04.16 Hinton's 2006 "Reducing the Dimensionality of Data with Neural Networks" [paper](https://www.cs.toronto.edu/~hinton/science.pdf)  
  [log](logs/2017.04.16)  

