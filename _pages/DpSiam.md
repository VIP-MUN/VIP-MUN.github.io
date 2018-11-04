---
title: "DP-Siam Tracker"
permalink: /DpSiam/
author_profile: true
#header:
#  image: "/images/dparch.jpg"
author: Mohamed  Abdelpakey
---
# DP-Siam: Dynamic Policy Siamese Network for Robust Object Tracking



<p class="text-justify">Balancing the trade-off between real-time performance and accuracy in object tracking is a major challenging problem.
 In this paper, a novel dynamic policy gradient Agent-Environment architecture with Siamese network (DP-Siam) is proposed to train the tracker to increase the accuracy and the expected average overlap while performing in real-time. DP-Siam is trained offline with
reinforcement learning to produce a continuous action that predicts the optimal object's location.
    DP-Siam has a novel architecture that consists of three networks: an Agent network to predict the optimal state (bounding box) of the object being tracked, and an Environment network to get the Q-value during the offline training phase to minimize the error of the loss function, and a Siamese network to produce a heat-map.  During the online tracking, the Environment network acts as a verifier to the Agent network action.
    Extensive experiments are performed on six widely used  benchmarks: OTB2013, OTB50, OTB100, VOT2015, VOT2016 and VOT2018. The results show that DP-Siam significantly outperforms the current state-of-the-art trackers.
</p>

## DP-Siam Architecture
<p class="text-justify">In  this section we show the architecture of DP-Siam. Data dimensions are shown in Table I.</p>
<figure>
  <img src="/images/Dparch.jpg">
  <figcaption> DP-Siam Architecture.</figcaption>
</figure>

## Experiments

<p class="text-justify">We evaluated DP-Siam on OTB2013, OTB50, OTB100, VOT2015, VOT2016, and VOT2018.</p>

<figure>
  <img src="/images/Dptable1.jpg" >
  <img src="/images/Dptablel2.jpg" >
  <img src="/images/Dptable3.jpg" >
  <img src="/images/Dptable4.jpg">

</figure>






## samples of easiest sequences

{% include video id="Cku4Api98T8" provider="youtube" %}


{% include video id="RQ6qU2f1PHQ" provider="youtube" %}



{% include video id="NFCW92O2wks" provider="youtube" %}



{% include video id="rSsm6izP1qY" provider="youtube" %}



{% include video id="MUbEcTu6Y3o" provider="youtube" %}

## samples of intermediate sequences


{% include video id="8kAGPQYjE_g" provider="youtube" %}


{% include video id="F16lIL4Lq8Q" provider="youtube" %}



{% include video id="rlHviMcASbw" provider="youtube" %}



{% include video id="pJLEr2DdWT0" provider="youtube" %}



{% include video id="5v713mh8QQU" provider="youtube" %}
## samples of challenging sequences


{% include video id="ghp82zvWANM" provider="youtube" %}


{% include video id="rjfzb5pNQjw" provider="youtube" %}



{% include video id="wH4EkZ_k7I4" provider="youtube" %}



{% include video id="XwrW_rMzJxg" provider="youtube" %}
