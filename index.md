---
layout: page
title: GECCO 2023 Workshop on Strict Box-Constrained Optimization
nav_order: 2
---

See also: <https://gecco-2023.sigevo.org/Workshops#SBOX-COST>

## Summary

Benchmarking plays a critical role in the design and development of optimization algorithms. The way in which benchmark suites are set up thus influences the set of algorithms recommended to practitioners and biases the goals of algorithm designers. While relying on such a procedure is generally beneficial, as it allows choosing algorithms which perform well on problems with similar characteristics to the practical problem at hand, there are potential ways in which it can bias algorithm choices. One particular aspect in which this can happen is related to the domain of the search space. In practical applications, evaluating points outside of the domain is often impossible, or not sensible, and as such, should be avoided. However, in benchmarking as practiced today, problems are well-defined even outside of the stated parameter ranges, which translates to the algorithms being able to safely ignore these ranges and operate on infeasible solutions.
Setting upper and lower limits of input variables represents the simplest type of constraints and gives rise to the so-called box-constrained problems. In this workshop, we will discuss in more detail how the treatment of box-constraints imposed on the search space impacts the performance of optimization algorithms. We will provide participants with a variant of the BBOB suite for continuous, single-objective, noiseless optimization, which is originally considered by the COCO platform to be unconstrained. In practice however, there are commonly used bounds, which are given as values to use, e.g., for initialization. For the benefit of this workshop, we will convert these recommended values to be tight box-constraints, outside of which evaluation returns no useful information.
With the inclusion of box-constraints, another aspect which biases the benchmarking-based design of algorithms for box-constrained problems is the location of the optimum relative to these domain boundaries. Functions included in the BBOB/COCO setup are rather limited in this sense, as by design they all have substantial optimum-free regions close to the aforementioned commonly used boundaries for all generated problem instances.
We encourage submissions containing benchmark results on the provided box-constrained variation of the BBOB suite of test functions. Discussion of the impact of box-constraints on algorithm performance or on reproducibility is also encouraged.

## Important Dates ##

|April ??, 2023  |Workshop paper submission deadline|
|April ??, 2023  |Notification of acceptance        |
|May ??, 2023    |Camera-ready deadline             |
|May ??, 2023    |Author registration deadline      |

## Call for papers

TODO

## Paper submission

TBA

### Instructions on submission

(see experimental setup), a doi of the zenodo submission with
data and resproducibility steps

TODO

### Instructions for generating plots with IOH (ask Diederick) and COCO (ask who?)

TODO

### Examples of data (ask Diederick, Anna)

TODO

## Organizers

| |**Anna Kononova**|
| |**Olaf Mersmann**<br>Olaf Mersmann is a Professor for Data Science at TH Köln - University of Applied Sciences. He received his BSc, MSc and PhD in Statistics from TU Dortmund. His research interests include using statistical and machine learning methods on large benchmark databases to gain insight into the structure of the algorithm choice problem.|
| |**Diederick Vermetten**<br>Diederick Vermetten is a PhD student at LIACS. He is part of the core development team of IOHprofiler, with a focus on the IOHanalyzer. His research interests include benchmarking of optimization heuristics, dynamic algorithm selection and configuration as well as hyperparameter optimization.|
|![](/assets/fig/lopez-ibanez-small.jpg)|**Manuel López-Ibáñez**<br>Dr. López-Ibáñez is a senior lecturer in the Decision and Cognitive Sciences Research Centre at the Alliance Manchester Business School, University of Manchester, UK. Between 2020 and 2022, he was also a "Beatriz Galindo" Senior Distinguished Researcher at the University of Málaga, Spain. He received the M.S. degree in computer science from the University of Granada, Granada, Spain, in 2004, and the Ph.D. degree from Edinburgh Napier University, U.K., in 2009. He has published 32 journal papers, 9 book chapters and 54 papers in peer-reviewed proceedings of international conferences on diverse areas such as evolutionary algorithms, multi-objective optimization, and various combinatorial optimization problems. His current research interests are experimental analysis and the automatic configuration and design of stochastic optimization algorithms, for single and multi-objective problems. He is the lead developer and current maintainer of the irace software package for automatic algorithm configuration (http://iridia.ulb.ac.be/irace) and the EAF package for the analysis of multi-objective optimizers (https://mlopez-ibanez.github.io/eaf/).|
|![](/assets/fig/allmendinger.jpg)|**Richard Allmendinger**<br>Richard is Senior Lecturer in Data Science and the Business Engagement Lead of Alliance Manchester Business School, The University of Manchester, and Fellow of The Alan Turing Institute, the UK's national institute for data science and artificial intelligence. Richard has a background in Business Engineering (Diplom, Karlsruhe Institute of Technology, Germany + Royal Melbourne Institute of Technology, Australia), Computer Science (PhD, The University of Manchester, UK), and Biochemical Engineering (Research Associate, University College London, UK). Richard's research interests are in the field of data and decision science and in particular in the development and application of optimization, learning and analytics techniques to real-world problems arising in areas such as management, engineering, healthcare, sports, music, and forensics. Richard is known for his work on non-standard expensive optimization problems comprising, for example, heterogeneous objectives, ephemeral resource constraints, changing variables, and lethal optimization environments. Much of his research has been funded by grants from various UK funding bodies (e.g. Innovate UK, EPSRC, ESRC, ISCF) and industrial partners. Richard is a Member of the Editorial Board of several international journals, Vice-Chair of the IEEE CIS Bioinformatics and Bioengineering Technical Committee, Co-Founder of the IEEE CIS Task Force on Optimization Methods in Bioinformatics and Bioengineering, and contributes regularly to conference organisation and special issues as guest editors.|
| |**Youngmin Kim**<br>Youngmin Kim is a PhD student at Alliance Manchester Business School (AMBS), The University of Manchester. His research focuses on the development and application of benchmark routines and algorithms for safe optimization. Youngmin has an MSc degree in Statistics from the University of Glasgow, and an MSc degree in Business Analytics from AMBS.|

