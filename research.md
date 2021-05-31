---
layout: page
title: Research
nav-menu: true
---

<section id="one">
<div class="inner">
  <header class="major">
    <h1>Research</h1>
  </header>
  <p>Below are brief descriptions of some of the research projects I have worked on the past</p>
  </div>
  <div class="inner">
    <h2>Multiagent Planning Via Partial Coordination in Markov Games</h2>
        <p>
        This project was my senior honors thesis, and focused on finding methods for scaling multiagent planning algorithms in markov games. Learning and planning
        algorithms in markov games tend to scale very poorly as you increase the number of agents in the game. To avoid this, we proposed a 'model game' framework,
        in which each agent has a simplified internal model of the environment, and computes a plan using that model. The simplified models we used were versions of the markov game that only included a subset of the total agents, although it would be possible to extend the framework to different kinds of models,
        e.g. different state or action spaces. By planning in simplified models, the plans for each agent could be computed significantly faster than planning
        in the complete game. The resultant plans for each possible models are then compared in the true environment using monte carlo simulations, and the
        best combination of models, in terms of the overall sum of rewards, is chosen as the final joint policy. I am currently working on expanding this framework to
        both learning and planning problems, and to finding more efficient methods for evaluating the efficacy of joint model combinations in the complete game. My complete
        honors thesis can be found <a href="assets/pdfs/Senior-Thesis.pdf"> here </a>.  
        </p>
  </div>
</section>

<section id="two">
  <div class="inner">
    <h2> DeepLTLf: Learning Finite Linear Temporal Logic Specifications with a Specialized Neural Operator </h2>
        <p>
        This project was focused on the problem of learning linear temporal logic formulae from example temporal traces. Initially, we used a PMAXSAT-based
        approach, where we would convert the traces into a large CNF formula in standard propositional logic, and then use a PMAXSAT solver to generate a
        satisfying solution. The solution could then be converted back into an LTL formula. This built on work by Camacho and McIlraith at the University of
        Toronto that used a similar method for solving this problem, but their approach used a SAT solver, and so could not handle noisy data. We eventually
        hit scaling problems, as the PMAXSAT solver could not handle formulas above around length 12, and so devised a specialized filter for a neural network
        explicitly meant to learn an LTL operator. After training a network on these filters on example traces, we could extract an LTL filter from the weights
        of the network, and simplify it into a reasonable reconstruction of the original target formula. I worked on this project with Homer Walke, Carl Trimbach, and
        Michael Littman. A link to the paper can be found <a href="assets/pdfs/Deep_LTL_Paper.pdf"> here </a>
        </p>
  </div>
</section>

<section id="three">
  <div class="inner">
  <h2>Starcraft II ExAI Project</h2>
  <p>
  I worked as part of a team at Brown that was part of the broader DARPA ExAI project. The team focused on designing explainable reinforcement learning algorithms,
  using the game Starcraft II as a testbed environment. We implemented several different algorithms on Starcraft II minigames, such as A3C, to look at their performance
  and to begin coming up with ways to make them interpretable. We also made some alterations to the algorithms, such as adding attention components, that allowed us to get
  more interpretable results in small minigames. 
  </p>
</div>
</section>
