---
layout: page
title: Work
nav-menu: true
---

<section id="one">
<div class="inner">
  <header class="major">
    <h1>Work</h1>
  </header>
  </div>
  <div class="inner">
    <h2>Image Analysis Intern at Perspectum Diagnostics: June-August(2019)</h2>
    <p>
    <img class="imbox" src="/assets/images/mask_rcnn_large_5.png" alt="An example nuclei prediction mask from MaskRCNN" style="width:512px;height:512px;margin-left:20px">
    Perspectum Diagnostics is a biotech company based in Oxford, England. They work primarily with medical images(MRI, CT, digitized biopsy) and apply technological
    solutions, often machine learning or deep learning based, to provide quantitative metrics and measurements of disease or disease-correlated quantities(e.g. iron levels
    in the liver). As an intern on the Image Analysis team, working partly at their office in San Francisco and partly at their Oxford office, I was helping develop methods for applying deep learning techniques to digital pathology slides. Initially, I worked on the issue of nuclei segmentation. Given some biopsy image, how can you segment all cell nuclei in that image? In my case, the use of solving this problem was
    to measure inflammation in the liver. When I began working, they already had a basic solution in place using a U-Net, a kind of fully convolutional neural network
    designed for biomedical imaging segmentation. However, this approach had serious problems misclassifying overlapping or nearly touching nuclei. Areas of inflammation
    are often densely packed with nuclei, so this problem becomes even more severe in cases where measuring inflammation and segmenting nuclei properly is the most critical.
    I implemented, trained, and tested a new approach, using a MaskRCNN architecture(Example prediction in the image to the right), which was able to individually identify and segment nuclei, even in cases where they are close or overlapping. I also performed several extensive comparison/ablation tests between both the U-Net and MaskRCNN, calculating similarity metrics, applying
    various image preprocessing methods, and comparing different forms of data augmentation, to determine which areas each approach excels in, allowing
    for the potential combination of the two in the future into a more robust predictive method.</p>
  </div>
  <div class="inner">
    <h2>Teaching Assistant for CS1470(Deep Learning): Fall Semester(2019)</h2>
    In the fall of 2019, I will be a Teaching Assistant for my university's Deep Learning course,
    teaching basic concepts of deep learning including convolutional neural networks, RNNs/LSTMs,
    GANs, and basic reinforcement learning(A2C). My responsibilities will include holding TA office hours, running supplemental labs, and
    helping to create and grade assignments.
  </div>
  <div class="inner">
    <h2>Publications Assistant at Texas Digestive Disease Consultants: June-August(2018)</h2>
    <p>As a Publications Assistant, I assisted in creating financial templates based on clinical drug trial protocols and agreements, which were used later to request payments from pharmaceutical companies. I also entered and collected data for both internal practice research projects and research projects funded/run by pharmaceutical companies, as well as helping to generate publications for presentation at various national and international gastrointestinal medical conferences.</p>
  </div>
</section>
