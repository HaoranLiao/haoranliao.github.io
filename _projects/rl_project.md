---
layout: page
title: Learn Reward Functions
description: Random Expert Distillation for reinforcement learning
img: assets/img/data2.jpeg
importance: 2
category: data & cs
---

<a href="https://github.com/HaoranLiao/cs285_project">Source Code</a><br>

Since reward functions are difficult to obtain in real-world problems, learning reward functions has gained a lot of interests in the <a href="https://en.wikipedia.org/wiki/Reinforcement_learning">reinforcement learning</a> community. Adversarial optimizations have been employed to learning reward functions but can suffer from instabilities and are hard to implement. In this report, we consider a recently proposed method -- random expert distillation (RED) -- in attaining reward functions for reinforcement learning. This method estimates whether a given state-action tuple belongs to the support of the expert data using prediction error from a network that is trained to mimic a random mapping for the expert data, and this error value on new state-action tuples can be translated into reward. It has been successfully demonstrated in training policies on various low-dimensional tasks and was shown to perform better in some tasks than using adversarial optimizations. In this paper, we extend the RED technique to high-dimensional input states, through two approaches. One approach is to incorporate <a href="https://en.wikipedia.org/wiki/Convolutional_neural_network">convolutional neural networks</a> in the RED critic and policy, and the other approach is to utilize an <a href="https://en.wikipedia.org/wiki/Autoencoder">autoencoder</a> to compress the raw inputs before applying RED. Our experiments show that the latter approach succeeds in dealing with high-dimensional pixel inputs in the Atari game MsPacman.

<iframe src="https://drive.google.com/file/d/1nO02F8lcQA4NEMtZ3UEbtz4XMrmZsFh8/preview" width="770" height="1080" allow="autoplay"></iframe>


