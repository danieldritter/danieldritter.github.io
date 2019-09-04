---
layout: page
title: Projects
nav-menu: true
---

<section id="one" markdown="1">
<div class="inner">
  <header class="major">
    <h1>Personal Projects</h1>
  </header>
  </div>

  <div class="inner">
    <h2>Reinforcement Learning Implementations</h2>
    <p>
    I find reinforcement learning absolutely fascinating, and I've recently started trying to write my own implementations of common reinforcement learning
    algorithms, both to improve my understanding of them, and to have frameworks in place if they become useful in later projects or research. My goal is to move from
    simple algorithms to more complex ones, going back and adding improvements as I go along and learn more(for example, going from A2C -> A3C -> PPO in terms of
    policy gradient methods). At the moment, I have working implementations of A2C and DQN on OpenAI's cartpole gym environment. I am also trying to write these
    implementations in a variety of different frameworks(Keras, Tensorflow, Pytorch, etc.). Both my A2C and DQN implementations are written in Pytorch, but I'm planning
    to write my next algorithm in Tensorflow. Presently, I'm working on adding Double DQN as well as multiprocessing A2C to allow for faster learning/batching. You can find
    the source code <a href="https://github.com/danieldritter/RL_Implementations">here</a>.
    </p>
  </div>
  <div class="inner">
    <h2>Deep Learning Implementations</h2>
    I've very recently started a repository for storing personal implementations of common deep learning architectures and for smaller personal deep learning related projects. See the code for these projects <a href="https://github.com/danieldritter/Deep-Learning-Repo">here</a>.
    <h3> CycleGAN </h3>
    <p>
    I wrote an implementation of the original CycleGAN architecture in Pytorch, and trained it against the Cezanne2Photo dataset used in the original paper. The implementation currently destabilizes during training, so I'm currently working on tweaking the hyperparameters and adjusting the architecture to stabilize training.
    </p>
    <h3> DCGAN </h3>
    <p>
    This is just a standard DCGAN implementation I'm working on writing in Pytorch. I'm using the Celeb-A faces dataset, but it's very much a work in progress at the moment, so it's not running yet.
    </p>
  </div>
  </section>
