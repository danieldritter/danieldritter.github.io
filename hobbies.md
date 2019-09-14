---
layout: page
title: Hobbies
nav-menu: true
---

<section id="one" markdown="1">

<div class="inner">
  <header class="major">
    <h1>Music</h1>
  </header>
  </div>

<div class="inner">
  <h2> Jazz and Classical Piano </h2>
  <p>
  <img class="imbox" src="/assets/images/piano_pic.JPG" alt="Picture of me playing piano in a pit orchestra">
  I've played classical piano for almost 12 years, and jazz piano for around 8. I played in small ensembles all throughout high school, and still take lessons and play in groups occasionally in college. You can hear a few examples of my playing below.
  </p>
  <audio controls="controls" src="/assets/audio/bach_invention_in_d_minor.mp3">
    Your browser does not support the html5 audio tag
  </audio>
  <audio controls="controls" src="/assets/audio/rach_prelude.mp3">
    Your browser does not support the html5 audio tag
  </audio>
  </div>

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
  <h2> Geomedia </h2>
  <p>
  This is a project that's moving rather slowly because I haven't had time to work on it very frequently, but that I really want to flesh out at some point. The basic idea is to scrape various news source using the News API and get a bunch of articles from the past day, week, month, etc. Given these articles, find the locations that are most frequently mentioned by each news source, and then place the logo for that news source on those locations on a map. This would give a really cool visual representation of where media is focused at any particular time, and, even more interestingly, which kinds of media sources are focused where. The project is written using Node.js and you can see the source code <a href="https://github.com/danieldritter/Geomedia.git">here</a>.
  </p>
  </div>
  </section>
