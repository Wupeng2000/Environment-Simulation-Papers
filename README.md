# Environment-Simulation-Papers


Contributed by [IDRL lab](https://github.com/idrl-lab).

- [Environment Simulation papers](#Environment Simulation papers)
  - [Introduction](#introduction)
  - [Overview](#Overview)
  - [Papers on Soft Robot](#papers-on-soft-robot)
  - [Papers on Differentiable Simulation](#papers-on-differentiable-simulationparallel)
  - [Papers on Optimization & Control](#papers-on-optimization--control)
  - [Papers on Applications](#papers-on-applications)

## Introduction

Environment Simulation has achieved great success in scientific computing since 2005. In this repo, we list some representative work on Environment Simulation. Feel free to distribute or use it!

Corrections and suggestions are welcomed.

A [script](./ref_convert.py) for converting bibtex to the markdown used in this repo is also provided for your convenience.

## Overview
1. **Soft Robots Modeling: a Structured Overview**, *Costanza Armanini, Fr{\'e}d{\'e}ric Boyer, Anup Teejo Mathew, Christian Duriez, Federico Renda*, arXiv preprint arXiv:2112.03645, 2021. [[paper](https://www.researchgate.net/profile/Costanza-Armanini/publication/356841763_Soft_Robots_Modeling_a_Structured_Overview/links/637b250037878b3e87cb571d/Soft-Robots-Modeling-a-Structured-Overview.pdf)]

## Papers on Soft Robot
1. **Evolution gym: A large-scale benchmark for evolving soft robots**, *Jagdeep Bhatia, Holly Jackson, Yunsheng Tian, Jie Xu, Wojciech Matusik*, Advances in Neural Information Processing Systems, 2021. [[paper](https://proceedings.neurips.cc/paper/2021/file/118921efba23fc329e6560b27861f0c2-Paper.pdf)][[code](https://github.com/EvolutionGym)]
2. **Underwater soft robot modeling and control with differentiable simulation**, *D Tao, J Hughes, S Wah, W Matusik, D Rus*, IEEE Robotics and Automation Letters, 2021. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9392257)]
3. **Chainqueen: A real-time differentiable physical simulator for soft robotics**, *Yuanming Hu, Jiancheng Liu, Andrew Spielberg, Joshua B Tenenbaum, William T Freeman, Jiajun Wu, Daniela Rus, Wojciech Matusik*, **UNKNOWN_JOURNAL**, 2019. [[paper](https://arxiv.53yu.com/pdf/1810.01054.pdf)]
4. **Plasticinelab: A soft-body manipulation benchmark with differentiable physics**, *Zhiao Huang, Yuanming Hu, Tao Du, Siyuan Zhou, Hao Su, Joshua B Tenenbaum, Chuang Gan*, arXiv preprint arXiv:2104.03311, 2021. [[paper](https://arxiv.53yu.com/pdf/2104.03311.pdf)][[code](https://github.com/hzaskywalker/PlasticineLab)]

## Papers on Differentiable Simulation
1. **Combining differentiable PDE solvers and graph neural networks for fluid flow prediction**, *Filipe De Avila Belbute-Peres, Thomas Economon, Zico Kolter*, **UNKNOWN_JOURNAL**, 2020. [[paper](http://proceedings.mlr.press/v119/de-avila-belbute-peres20a/de-avila-belbute-peres20a.pdf)]
2. **Diffaqua: A differentiable computational design pipeline for soft underwater swimmers with shape interpolation**, *Pingchuan Ma, Tao Du, John Z Zhang, Kui Wu, Andrew Spielberg, Robert K Katzschmann, Wojciech Matusik*, ACM Transactions on Graphics (TOG), 2021. [[paper](https://dl.acm.org/doi/pdf/10.1145/3450626.3459832)][[code](https://dl.acm.org/action/downloadSupplement?doi=10.1145%2F3450626.3459832&file=3450626.3459832.vtt)]
3. **Diffpd: Differentiable projective dynamics**, *Tao Du, Kui Wu, Pingchuan Ma, Sebastien Wah, Andrew Spielberg, Daniela Rus, Wojciech Matusik*, ACM Transactions on Graphics (TOG), 2021. [[paper](https://dl.acm.org/doi/fullHtml/10.1145/3490168)]
4. **Brax--A Differentiable Physics Engine for Large Scale Rigid Body Simulation**, *C Daniel Freeman, Erik Frey, Anton Raichuk, Sertan Girgin, Igor Mordatch, Olivier Bachem*, arXiv preprint arXiv:2106.13281, 2021. [[paper](https://arxiv.53yu.com/pdf/2106.13281.pdf)][[code](https://github.com/google/brax)]
5. **Disect: A differentiable simulation engine for autonomous robotic cutting**, *Eric Heiden, Miles Macklin, Yashraj Narang, Dieter Fox, Animesh Garg, Fabio Ramos*, arXiv preprint arXiv:2105.12244, 2021. [[paper](https://arxiv.53yu.com/pdf/2105.12244.pdf)][[code](https://diff-cutting-sim.github.io/)]
6. **NeuralSim: Augmenting differentiable simulators with neural networks**, *Eric Heiden, David Millard, Erwin Coumans, Yizhou Sheng, Gaurav S Sukhatme*, **UNKNOWN_JOURNAL**, 2021. [[paper](https://arxiv.53yu.com/pdf/2011.04217.pdf)][[code](https://sites.google.com/usc.edu/neuralsim)]
7. **Interactive differentiable simulation**, *Eric Heiden, David Millard, Hejia Zhang, Gaurav S Sukhatme*, arXiv preprint arXiv:1905.10706, 2019. [[paper](https://arxiv.53yu.com/pdf/1905.10706.pdf)]
8. **Difftaichi: Differentiable programming for physical simulation**, *Yuanming Hu, Luke Anderson, Tzu-Mao Li, Qi Sun, Nathan Carr, Jonathan Ragan-Kelley, Dur, Fr{\'e}do *, arXiv preprint arXiv:1910.00935, 2019. [[paper](https://arxiv.53yu.com/pdf/1910.00935.pdf)]
9. **Differentiable simulation of soft multi-body systems**, *Yiling Qiao, Junbang Liang, Vladlen Koltun, Ming Lin*, Advances in Neural Information Processing Systems, 2021. [[paper](https://proceedings.neurips.cc/paper/2021/file/8e296a067a37563370ded05f5a3bf3ec-Paper.pdf)]
10. **Efficient differentiable simulation of articulated bodies**, *Yi-Ling Qiao, Junbang Liang, Vladlen Koltun, Ming C Lin*, **UNKNOWN_JOURNAL**, 2021. [[paper](http://proceedings.mlr.press/v139/qiao21a/qiao21a.pdf)]
11. **Scalable differentiable physics for learning and control**, *Yi-Ling Qiao, Junbang Liang, Vladlen Koltun, Ming C Lin*, arXiv preprint arXiv:2007.02168, 2020. [[paper](https://arxiv.53yu.com/pdf/2007.02168.pdf)]
12. **Transformer with Implicit Edges for Particle-Based Physics Simulation**, *Yidi Shao, Chen Change Loy, Bo Dai*, **UNKNOWN_JOURNAL**, 2022. [[paper](https://arxiv.53yu.com/pdf/2207.10860.pdf)][[code](https://github.com/ftbabi/TIE_ECCV2022)]
13. **Pettingzoo: Gym for multi-agent reinforcement learning**, *J Terry, Benjamin Black, Nathaniel Grammel, Mario Jayakumar, Ananth Hari, Ryan Sullivan, Luis S Santos, Clemens Dieffendahl, Caroline Horsch, Rodrigo Perez-Vicente, others*, Advances in Neural Information Processing Systems, 2021. [[paper](https://proceedings.neurips.cc/paper/2021/file/7ed2d3454c5eea71148b11d0c25104ff-Paper.pdf)]

## Papers on Optimization & Control
1. **Learning to control pdes with differentiable physics**, *Philipp Holl, Vladlen Koltun, Nils Thuerey*, arXiv preprint arXiv:2001.07457, 2020. [[paper](https://arxiv.53yu.com/pdf/2001.07457.pdf)]
2. **gradsim: Differentiable simulation for system identification and visuomotor control**, *Krishna Murthy Jatavallabhula, Miles Macklin, Florian Golemo, Vikram Voleti, Linda Petrini, Martin Weiss, Bre Considine, an, Jerome Parent-Levesque, Kevin Xie, Kenny Erleben, others*, arXiv preprint arXiv:2104.02646, 2021. [[paper](https://arxiv.53yu.com/pdf/2104.02646.pdf)][[code](https://gradsim.github.io/)]

## Papers on Applications
1. **Lagrangian neural style transfer for fluids**, *Byungsoo Kim, Vinicius C Azevedo, Markus Gross, Barbara Solenthaler*, ACM Transactions on Graphics (TOG), 2020. [[paper](https://arxiv.53yu.com/pdf/2005.00803.pdf)][[code](https://dl.acm.org/action/downloadSupplement?doi=10.1145%2F3386569.3392473&file=3386569.3392473.vtt)]
2. **Learning particle dynamics for manipulating rigid bodies, deformable objects, and fluids**, *Yunzhu Li, Jiajun Wu, Russ Tedrake, Joshua B Tenenbaum, Antonio Torralba*, arXiv preprint arXiv:1810.01566, 2018. [[paper](https://arxiv.53yu.com/pdf/1810.01566.pdf)][[code](http://dpi.csail.mit.edu)]
3. **Diffskill: Skill abstraction from differentiable physics for deformable object manipulations with tools**, *Xingyu Lin, Zhiao Huang, Yunzhu Li, Joshua B Tenenbaum, David Held, Chuang Gan*, arXiv preprint arXiv:2203.17275, 2022. [[paper](https://arxiv.53yu.com/pdf/2203.17275.pdf)][[code](https://github.com/Xingyu-Lin/DiffSkill)]
4. **Isaac gym: High performance gpu-based physics simulation for robot learning**, *Viktor Makoviychuk, Lukasz Wawrzyniak, Yunrong Guo, Michelle Lu, Kier Storey, Miles Macklin, David Hoeller, Nikita Rudin, Arthur Allshire, H, Ankur a, others*, arXiv preprint arXiv:2108.10470, 2021. [[paper](https://arxiv.53yu.com/pdf/2108.10470.pdf)][[code](https://developer.nvidia.com/isaac-gym)]
5. **Spnets: Differentiable fluid dynamics for deep neural networks**, *Connor Schenck, Dieter Fox*, **UNKNOWN_JOURNAL**, 2018. [[paper](http://proceedings.mlr.press/v87/schenck18a/schenck18a.pdf)]
6. **Differentiable fluids with solid coupling for learning and control**, *Tetsuya Takahashi, Junbang Liang, Yi-Ling Qiao, Ming C Lin*, **UNKNOWN_JOURNAL**, 2021. [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/16764/16571)]
7. **Solver-in-the-loop: Learning from differentiable physics to interact with iterative pde-solvers**, *Kiwon Um, Br, Robert , Yun Raymond Fei, Philipp Holl, Nils Thuerey*, Advances in Neural Information Processing Systems, 2020. [[paper](https://proceedings.neurips.cc/paper/2020/file/43e4e6a6f341e00671e123714de019a8-Paper.pdf)]
8. **Lagrangian fluid simulation with continuous convolutions**, *Benjamin Ummenhofer, Lukas Prantl, Nils Thuerey, Vladlen Koltun*, **UNKNOWN_JOURNAL**, 2019. [[paper](https://openreview.net/pdf?id=B1lDoJSYDH)]
