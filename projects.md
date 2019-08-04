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
    <h2>MediGAN</h2>
    <p>
    <img class="imbox" src="/assets/images/hasbro_pet.jpeg" alt="One of Hasbro's Joy For All Companion Pets">
    Part of my job in the summer of 2019 was figuring out ways to apply deep learning image classification and
    segmentation algorithms to digital pathology images. Essentially, biopsy slides(primarily from the liver, in my case)
    can be digitized, uploaded to a computer, and then run through a neural network to automatically classify quantities
    like the percentage of fat, inflammation, or fibrosis(liver scarring) present. One of the greatest challenges in
    training these kinds of detection algorithms, though, is a scarcity of high quality training data. As an example,
    I was attempting to train a MaskRCNN network to identify and segment all nuclei from biopsy images(as a method for
    measuring inflammation). My dataset was 30 1000x1000 images from biopsy slides with all nuclei annotated. With only
    30 images, and using a network often trained on hundreds of thousands or millions, ensuring successful learning is difficult.
    Ideally, of course, we would simply get more data, but annotating images, especially ones with a large number of annotations
    like nuclei, is tedious and costly, without mentioning the additional difficulties surrounding getting access to patient
    data in the first place, making sure it is properly anonymized, etc. This problem of scarce training data got me wondering
    if there could be a way to mitigate the problems of hand annotation and data collection by generating images and
    their paired annotations. To this end, I wrote and trained a CycleGAN(which I've called MediGAN, in standard GAN naming fashion),
    a generative network meant for image-to-image translation, to generate a nuclei annotation mask(a binary mask of the image with 1's for nuclei and 0's for background)
    from a biopsy image and vice versa. This is a very difficult translation to make, and getting a network to make
    precise and accurate enough translations to serve as training data is unlikely. However, I could see this kind of an idea serving
    as an excellent tool for assisting and speeding up annotation. Rather than starting from nothing and annotating each nuclei
    in an image, someone could take the output of the image to mask generator and much more rapidly assess its quality. Generating
    data and annotations would then require simply human review, rather than hours of tedious annotation. The increase in available training
    data would then allow for the training of more effective segmentation networks, which could be more useful in assisting annotation,
    creating a feedback loop of improving performance. Later iterations of trained networks could bootstrap off of a combination of the
    previous generations predictions combined with human review. See the source code for this project <a href="https://github.com/danieldritter/MediGAN.git">here</a>.
    </p>
  </div>
  <div class="inner">
    <h2>Reinforcement Learning Implementations</h2>
    <p>
    <img class="imbox" src="/assets/images/hasbro_pet.jpeg" alt="One of Hasbro's Joy For All Companion Pets">
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
    <h2>CardGAN</h2>
    <p>
    <img class="imbox" src="/assets/images/hasbro_pet.jpeg" alt="One of Hasbro's Joy For All Companion Pets">
    This project is really just a fun application of Generative Adversarial Networks(GANs). I wanted to write a GAN implementation, but didn't want to use MNIST or CIFAR or any of the
    standard datasets. Instead, I wrote a script to pull Magic: The Gathering card arts from the internet, and saved those into a dataset instead, trying
    to train a generator to generate new card art. The GAN itself is a normal DCGAN implementation, which was trained against a dataset of several thousand
    card arts. See the source code for it <a href="https://github.com/danieldritter/CardGAN">here</a>.
    </p>

  </div>
  </section>
