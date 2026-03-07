---
title: "Discovering complex quantitative dependencies between interval-based state streams"
collection: publications
category: thesis
permalink: /publication/phd-thesis/
excerpt: ''
date: 2020-07-24
venue: "Université de Lyon, INSA Lyon"
slidesurl: "https://aelouassouli.github.io/files/slides_phd_thesis.pdf"
paperurl: 'https://aelouassouli.github.io/files/phd_thesis.pdf'
citation: "Amine El Ouassouli. Discovering complex quantitative dependencies between interval-based state streams. Artificial Intelligence [cs.AI]. Université de Lyon, 2020. English."
---

The increasing utilization of sensor devices in addition to human-given data make it possible to capture real
world systems complexity through rich temporal descriptions. More precisely, the usage of a multitude of data
sources types (devices, humans) allows to monitor an environment by describing the evolution in time of several of its dimensions through data streams. One core characteristic of such configurations is heterogeneity that
appears at different levels ofthe data generation process: data sources, time models and data models. In such context, one challenging task for monitoring systems is to discover non-trivial temporal knowledge that is directly
actionable and suitable for human interpretation. In this thesis, we firstly propose to use a Temporal Abstraction
(TA) approach to express information given by heterogeneous raw data streams with a unified interval-based
representation, called state streams. A state reports on a high level environment configuration that is of interest
for an application domain. It is defined as a predicate involving data from one or several data sources. Such approach solves problems introduced by heterogeneity, provides a high level pattern vocabulary and also permits
also to integrate expert(s) knowledge into the discovery process. Second, we introduced the Complex Temporal
Dependencies (CTD) that is a quantitative interval-based pattern model. It is defined similarly to a conjunctive
normal form and allows to express complex temporal relations between states. Contrary to the majority of existing pattern models, a CTD is evaluated with automatic statistical assessment of streams intersection avoiding
the use of any significance user-given parameter. Third, we proposed CTD-Miner a first efficient CTD mining
framework. CTD-Miner performs an incremental dependency construction. CTD-Miner benefits from pruning
techniques based on a statistical correspondence relationship that aims to accelerate the exploration search space
by reducing redundant information and to provide a more usable result set. Finally, as discovering pairwise significant time lag dependencies is a core operation in the CTD-Miner process, we proposed the Interval Time Lag
Discovery (ITLD) algorithm. ITLD is based on a confidence variation heuristic that permits to reduce the complexity of the discovery process from quadratic to linear w.r.t a temporal constraint Δ on time lags. To evaluate
our approach, we implemented a motion simulation tool permitting to build data sets corresponding to a wide
range of configurations. We also gathered data from a real world experiment using video cameras and real time
video processing methods to build a real motion data set. Experiments showed that ITLD provides efficiently
more accurate results in comparison with existing approaches. Hence, ITLD enhances significantly the accuracy,
performances and scalability of CTD-Miner. The encouraging results given by CTD-Miner on our real world
motion data set suggests that it is possible to integrate insights given by real time video processing approaches in
a knowledge discovery process opening interesting perspectives for monitoring smart environments.
