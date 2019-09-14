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
  <img class="imbox" src="/assets/images/piano_pic.JPG" width="462" height="306" alt="Picture of me playing piano in a pit orchestra">
  I've played classical piano for almost 12 years, and jazz piano for around 8. I played in small ensembles all throughout high school, and still take lessons and play in groups occasionally in college. You can hear a few examples of my playing below.
  </p>
  <h3> Bach's Invention No. 4 in D Minor, BWV 775 </h3>
  <audio controls="controls" src="/assets/audio/bach_invention_in_d_minor.mp3">
    Your browser does not support the html5 audio tag
  </audio>
  <h3> Rachmaninoff Prelude in C# Minor, Op. 3, No. 2</h3>
  <audio controls="controls" src="/assets/audio/rach_prelude.mp3">
    Your browser does not support the html5 audio tag
  </audio>
  </div>

<div class="inner">
  <h2> Musical Theater</h2>
  <div class="row" style="display:flex; justify-content:space-between;">
  <img width="461" height="691" src="/assets/images/pippin.jpeg" alt="Poster for BUG's production of Pippin">
  <img width="461" height="691" src="/assets/images/into_the_woods.jpg" alt="Poster for BUG's production of the 25th Annual Putnam County Spelling Bee">
  <img width="461" height="691" src="/assets/images/bugs.png" alt="poster for Brown University Gilbert and Sullivan">
  </div>
  <p>
  I've been involved in a number of different musical productions since I started college. I've performed in the pit orchestra's for 4 different shows, and music directed an original show last spring as well. I'm also on the producing board for Brown University Gilbert and Sullivan, a student group that puts on a large ensemble musical every semester.
  </p>
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
