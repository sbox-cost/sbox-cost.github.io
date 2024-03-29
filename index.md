---
title: Workshop on Strict Box-Constrained Optimization (SBOX-COST)
---

## Summary
[![GECCO 2023 logo](/assets/fig/gecco-2023.png){:.float-right width="200px" }](https://gecco-2023.sigevo.org/Workshops#SBOX-COST)

Benchmarking plays a critical role in the design and development of optimization algorithms. The way in which benchmark suites are set up thus influences the set of algorithms recommended to practitioners and biases the goals of algorithm designers. The focus of this workshop is on benchmarking algorithms on problems with box constraints (i.e. upper and lower limits on the input variables defining the domain of the search space). In practical applications, evaluating points outside of the domain is often impossible, or not sensible, and as such, should be avoided. However, in benchmarking as practiced today, problems are well-defined even outside of the stated parameter ranges, which translates to the algorithms being able to safely ignore these ranges and operate on infeasible solutions.

Setting up box constraints represents the simplest type of constraints and gives rise to the so-called box-constrained problems. In this workshop, we will discuss in more detail how the presence of box-constraints impacts the performance of optimization algorithms and provide participants with a new variant of the BBOB suite called SBOX-COST for continuous, single-objective, noiseless optimization. 

<!-- While relying on such a procedure is generally beneficial, as it allows choosing algorithms which perform well on problems with similar characteristics to the practical problem at hand, there are potential ways in which it can bias algorithm choices. One particular aspect in which this can happen is related to the domain of the search space. In practical applications, evaluating points outside of the domain is often impossible, or not sensible, and as such, should be avoided. However, in benchmarking as practiced today, problems are well-defined even outside of the stated parameter ranges, which translates to the algorithms being able to safely ignore these ranges and operate on infeasible solutions. -->
<!-- Setting upper and lower limits of input variables represents the simplest type of constraints and gives rise to the so-called box-constrained problems. In this workshop, we will discuss in more detail how the treatment of box-constraints imposed on the search space impacts the performance of optimization algorithms. We will provide participants with a variant of the BBOB suite for continuous, single-objective, noiseless optimization, which is originally considered by the COCO platform to be unconstrained. In practice however, there are commonly used bounds, which are given as values to use, e.g., for initialization. For the benefit of this workshop, we will convert these recommended values to be tight box-constraints, outside of which evaluation returns no useful information. -->
<!-- With the inclusion of box-constraints, another aspect which biases the benchmarking-based design of algorithms for box-constrained problems is the location of the optimum relative to these domain boundaries. Functions included in the BBOB/COCO setup are rather limited in this sense, as by design they all have substantial optimum-free regions close to the aforementioned commonly used boundaries for all generated problem instances. -->
<!-- We encourage submissions containing benchmark results on the provided box-constrained variation of the BBOB suite of test functions. Discussion of the impact of box-constraints on algorithm performance or on reproducibility is also encouraged. -->

## Important Dates ##

| Submission opening              | February 13, 2023 |
| Submission deadline             | April 17 (AoE),    2023 |
| Notification to authors         | May 3,      2023 |
| Camera-ready papers             | May 10,      2023 |
| Author’s mandatory registration | May 10,      2023 |

## Call for papers

[cfp.txt](/assets/cfp.txt)

## Paper submission

Two types of submissions will be accepted for this workshop:

1. Short papers (up to 4 pages) reporting results of new or existing algorithms on the provided BBOB SBOX-COST suite of (box-constrained) test functions. Please refer to the following link for the data and instructions on how to use it: <https://github.com/sbox-cost/Examples>
You can also find there a LaTeX template  (<https://github.com/sbox-cost/Examples/tree/main/SBOX-COST-template>) and its [PDF](https://raw.githubusercontent.com/sbox-cost/Examples/main/SBOX-COST-template/SBOX_COST_template.pdf).

2. Longer papers (up to 8 pages) discussing aspects related to the presence of box-constraints.

Topics of interest (but not limited to) include:
 * New insights of existing algorithms when applied to box-constrained problems
 * Performance analysis and visualization of algorithms on the provided BBOB SBOX-COST suite of test functions
 * Algorithm design for box-constrained problems 
 * Metrics for benchmarking algorithm performance on and complexity of box-constrained problems
 * Other aspects of box-constrained benchmarking optimization algorithms

### Instructions on submission

For paper submission instructions and templates, please see the GECCO submission instructions: <https://gecco-2023.sigevo.org/Paper-Submission-Instructions>

(see experimental setup), a doi of the zenodo submission with
data and resproducibility steps

You can find an example paper [here](/assets/paper-example.pdf)

### Instructions for generating plots with IOH and COCO

See <https://github.com/sbox-cost/Examples>

### Examples of data

See Zenodo repository: <https://doi.org/10.5281/zenodo.7649077>



## Organizers

|<img class="photo" src="/assets/fig/Anna_d200x250.png">|**Anna Kononova** is an Assistant Professor at the Leiden Institute of Advanced Computer Science, Leiden University, The Netherlands. She received her MSc degree in Applied Mathematics from Yaroslavl State University (Russia) in 2004 and PhD degree in Computer Science from University of Leeds (UK) in 2010. After the total of 5 years of postdoctoral experiences at Technical University Eindhoven (The Netherlands) and Heriot-Watt University (Edinburgh, UK), Anna has spent a number of years working as a mathematician in industry. Her current research interests include analysis of optimisation algorithms and machine learning.|
|<img class="photo" src="/assets/fig/olafmersmann.jpg">|**Olaf Mersmann** is a Professor for Data Science at TH Köln - University of Applied Sciences. He received his BSc, MSc and PhD in Statistics from TU Dortmund. His research interests include using statistical and machine learning methods on large benchmark databases to gain insight into the structure of the algorithm choice problem.|
|<img class="photo" src="/assets/fig/Diederick.jpg">|**Diederick Vermetten**<br>Diederick Vermetten is a PhD student at LIACS. He is part of the core development team of IOHprofiler, with a focus on the IOHanalyzer. His research interests include benchmarking of optimization heuristics, dynamic algorithm selection and configuration as well as hyperparameter optimization.|
|<img class="photo" src="/assets/fig/lopezibanez-small.jpg">| **Manuel López-Ibáñez** is a senior lecturer in the Decision and Cognitive Sciences Research Centre at the Alliance Manchester Business School, University of Manchester, UK. Between 2020 and 2022, he was also a "Beatriz Galindo" Senior Distinguished Researcher at the University of Málaga, Spain. He received the M.S. degree in computer science from the University of Granada, Granada, Spain, in 2004, and the Ph.D. degree from Edinburgh Napier University, U.K., in 2009. He has published 32 journal papers, 9 book chapters and 54 papers in peer-reviewed proceedings of international conferences on diverse areas such as evolutionary algorithms, multi-objective optimization, and various combinatorial optimization problems. His current research interests are experimental analysis and the automatic configuration and design of stochastic optimization algorithms, for single and multi-objective problems. He is the lead developer and current maintainer of the irace software package for automatic algorithm configuration (<http://iridia.ulb.ac.be/irace>) and the EAF package for the analysis of multi-objective optimizers (<https://mlopez-ibanez.github.io/eaf/>).|
|<img class="photo" src="/assets/fig/allmendiger.jpg">|**Richard Allmendinger** is Dr Richard Allmendinger is a Professor of Applied AI at the Alliance Manchester Business School, The University of Manchester, and Fellow of The Alan Turing Institute, and an Advisor to River Capital's AI fund (the first dedicate AI fund in the North of UK). Richard has a background in Business Engineering (Diplom, Karlsruhe Institute of Technology, Germany + Royal Melbourne Institute of Technology, Australia), Computer Science (PhD, The University of Manchester, UK), and Biochemical Engineering (Research Associate, University College London, UK). Richard's research interests are in the development and application of optimization, learning and analytics techniques to real-world problems arising in areas such as management, engineering, healthcare, sports, music, and forensics. Much of his research has been funded by UK funding bodies and industrial partners. Richard is a Member of the Editorial Board of several international journals, Vice-Chair of the IEEE CIS Bioinformatics and Bioengineering Technical Committee, Co-Founder of the IEEE CIS Task Force on Optimization Methods in Bioinformatics and Bioengineering, and contributes regularly to conference organisation and special issues as guest editors.|
| |**Youngmin Kim** is a PhD student at Alliance Manchester Business School (AMBS), The University of Manchester. His research focuses on the development and application of benchmark routines and algorithms for safe optimization. Youngmin has an MSc degree in Statistics from the University of Glasgow, and an MSc degree in Business Analytics from AMBS.|

