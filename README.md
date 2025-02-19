
[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)](https://github.com/HuantWang/SUPERSONIC/graphs/commit-activity)
[![License CC-BY-4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](https://github.com/HuantWang/SUPERSONIC/blob/master/LICENSE)
[![Documentation Status](https://readthedocs.org/projects/supersonic/badge/?version=latest)](https://supersonic.readthedocs.io/en/latest/?badge=latest)

<div align="center">
 <img src="docs/source/_static/img/logo.png">
</div>

<p align="center">
  <i>Automating reinforcement learning architecture design for code optimization.</i>
</p>
<p align="center">
  <i>
    Check
    <a href="http://1.14.76.177:7033/index.html">the website</a>
    for more information.
  </i>
</p>

## Introduction
SUPERSONIC is a tool to automate reinforcement learning (RL) policy searching and tuning. It is designed to help compiler developers to find the right RL architecture and algorithm to use for an optimization task. It finds the right RL exploration algorithm, the reward function and a method for modeling the environment state. 

Given an RL search space defined by the Supersonic Python API, the Supersonic meta-optimizer automatically searches for a suitable RL component composition for an optimization task. It also automatically tunes a set of tunable hyperparameters of the chosen components. No RL expertise is needed to use Supersonic. 

*Check [our paper](https://dl.acm.org/doi/10.1145/3497776.3517769) or [presentation slides](https://github.com/HuantWang/SUPERSONIC/blob/master/docs/Supersonic.pdf) for detailed information.*

## Installation

Supersonic builds upon:
-	Python v3.8 
-	[CompilerGym](https://github.com/facebookresearch/CompilerGym) 
-	[Ray](https://docs.ray.io/en/latest/rllib.html)
	
The system was tested on the following operating systems:
- Ubuntu 18.04
- Fedora 28
- Debian 10

See [INSTALL.md](INSTALL.md) for further details.

## Useage

See [artifact_evaluation](https://github.com/HuantWang/SUPERSONIC/blob/master/AE.md) for an out-of-the-box demo of Supersonic.


## Contributing

We welcome contributions to SuperSonic. If you are interested in contributing please see
[this document](https://github.com/HuantWang/SUPERSONIC/blob/master/CONTRIBUTING.md).

## Citation
If you use Supersonic in any of your work, please cite [our paper](https://dl.acm.org/doi/10.1145/3497776.3517769):

```
@inproceedings{10.1145/3497776.3517769,
author = {Huanting Wang, Zhanyong Tang, Cheng Zhang, Jiaqi Zhao, Chris Cummins, Hugh Leather, and Zheng Wang},
title = {Automating Reinforcement Learning Architecture Design for Code Optimization},
year = {2022},
isbn = {9781450391832},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3497776.3517769},
doi = {10.1145/3497776.3517769},
booktitle = {Proceedings of the 31st ACM SIGPLAN International Conference on Compiler Construction},
pages = {129–143},
numpages = {15},
keywords = {Compiler optimization, reinforcement learning, code optimization},
location = {Seoul, South Korea},
series = {CC 2022}
}
```
