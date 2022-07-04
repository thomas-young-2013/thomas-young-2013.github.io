---
title: "Projects"
permalink: /projects/
author_profile: true
---

From 2017 to 2022, I led the AutoML team and several system projects in the [Data and Intelligence Research (DAIR)](https://cuibinpku.github.io/) Lab at Peking university, including OpenBox, MindWare and HyperTune.


<p align="center">
<img src="/images/openbox.png" width="40%">
</p>

### OpenBox: Generalized and Efficient Blackbox Optimization System
OpenBox is an efficient and generalized blackbox optimization (BBO) system, which supports the following
characteristics : 1) BBO with multiple objectives and constraints, 2) BBO with transfer learning, 3) BBO with
distributed parallelization, 4) BBO with multi-fidelity acceleration and 5) BBO with early stops.

The design of OpenBox follows the following principles.
* Ease of use: Minimal user effort, and user-friendly visualization for tracking and managing BBO tasks. 
* Consistent performance: Host state-of-the-art optimization algorithms; Choose the proper algorithm automatically. 
* Resource-aware management: Give cost-model based  advice to users, e.g., minimal workers or time-budget. 
* Scalability: Scale to dimensions on the number of input variables, objectives, tasks, trials, and parallel evaluations. 
* High efficiency: Effective use of parallel resources, system optimization with transfer-learning and multi-fidelities, etc. 
* Fault tolerance, extensibility, and data privacy protection.

**Keywords**: Blackbox optization as a service, NAS tool, AutoML optimization engine, Distributed system.

**Enterprise Users**: Tencent, Alibaba Group, ByteDance and Kuaishou Technology.

**Github Repository**: [https://github.com/PKU-DAIR/open-box](https://github.com/PKU-DAIR/open-box).

**Achievements**
* OpenBox based solutions got the CHAMPION of [ACM CIKM 2021 AnalyticCup](https://www.cikm2021.org/analyticup) (Track - Automated Hyperparameter Optimization of Recommendation System).
* OpenBox team won the TOP PRIZE (Special Prize) in the open-source innovation competition at [CCF ChinaSoft 2021](http://chinasoft.ccf.org.cn/papers/chinasoft.html).
* Scalable graph learning toolkit - [Pasca](https://github.com/PKU-DAIR/SGL), which adopts Openbox to support neural architecture search functionality, won the Best Student Paper Award at WWW'22.


<p align="center">
<img src="/images/mindware.png" width="35%">
</p>

### MindWare: Efficient Open-source AutoML System
MindWare can automate the process of 1) data pre-processing, 2) feature engineering, 3) algorithm selection, 4) neural architecture design, 5) hyper-parameter tuning, and 6) model ensembling. It is capable of improving
its AutoML power by decomposing the entire large AutoML search space into small ones, and solve each subproblems
jointly and efficiently. The goal is to make machine learning easier to apply both in industry and
academia, and help facilitate data science.

MindWare supports 1) AutoML tasks for tabular, image, text and graph structured data, 2) high-dimensional
and complex search space, 3) transfer-learning and meta-learning, and 4) distributed parallelization.

**Highlights**: Superior end-to-end performance against commercial AutoML services from Google, Oracle, Microsoft and Amazon.

**Github Repository**: [https://github.com/PKU-DAIR/mindware](https://github.com/PKU-DAIR/mindware).


<p align="center">
<img src="/images/hypertune.png" width="40%">
</p>

### HyperTune: Efficient Hyper-parameter Tuning System at Scale
HyperTune is a scalable, robust and distributed tuning system, which is designed to deal with large-scale
hyper-parameter optimization (HPO) and neural architecture search (NAS) tasks. 
Hyper-Tune highlights multiple system optimizations, including (1) automatic resource allocation, (2) asynchronous scheduling, and (3)
multi-fidelity optimizer.

**Keywords**: HPO, NAS, distributed system.

**Enterprise Users**: Kuaishou Technology.

**Github Repository**: [https://github.com/PKU-DAIR/HyperTune](https://github.com/PKU-DAIR/HyperTune).
